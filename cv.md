![Personal Photo](./images/photo.jpg "Andrey Fits")

# Andrey Fits

### PHP Developer

## Contact

- Phone: +375 44 729-10-96
- Email: [andreyfits@gmail.com](mailto:andreyfits@gmail.com)
- LinkedIn: [Andrei Fits](https://www.linkedin.com/in/andreifits/)
- Telegram: [Andrey Fits](https://t.me/andreyfits)
- Address: Brest, Belarus

## About me

Experienced PHP Developer with experience working in the information technology and services industry. Skills in
programming on PHP, MySQL, and other information technology. As someone who takes responsibility for his
own personal development, I'm continually evaluating and upgrading my skills in order to stay at the cutting plane
of web development. Created backend part of Consumer Fusion(Web Portal for business management), Internal CRM system
for Oxagile, Websites on the WordPress, and CraftCMS for Effectivesoft Corporation.

## Skills

- HTML5
- CSS3
- JavaScript Basics
- PHP
- MySQL
- Git
- Linux
- Docker

## Code Example

**Task:** *The array of integers is given. It is necessary to shift the zero elements to the end of the array, while maintaining the relative order of the non-zero elements.*

```php
function ShiftZeroValues($arr)
{
    $index = 0;
    $nullCount = 0;
    
    while ($index < count($arr) - $nullCount) {
        if ($arr[$index] === 0) {
            array_splice($arr, $index, 1);
            $arr[] = 0;
            $nullCount++;
        } else {
            $index++;
        }
    }
    
    return $arr;
}

function test($arr)
{
    printf("[%s] => [%s]\n", implode(', ', $arr),  implode(', ', ShiftZeroValues($arr)));
}

test([0, 1, -8, 2, 0, 5, 0]); // [1, -8, 2, 5, 0, 0, 0]
test([4, 0, 6, 0, 0, -5]);    // [4, 6, -5, 0, 0, 0]
test([2, 5, 9, 1, -7]);       // [2, 5, 9, 1, -7]
```

## Work Experience

### PHP Developer

[Oxagile](https://www.oxagile.com/)

Jul 2021 - Oct 2021

- Development frontend and backend parts of the admin panel
- Was involved in estimations
- Discussions and meetings with the customer
- Improvements after comments of QA, customer, and designer
- Made code review and code refactoring of colleagues (GitLab)

### PHP Developer

[EffectiveSoft Corporation](https://www.effectivesoft.com/)

Jul 2020 - Jun 2021

- Developed and designed the whole backend part
- Was involved in estimations
- Was involved in meetings with the customer
- Improvements after comments of QA, customer, and designer
- Made code review and code refactoring of colleagues (BitBucket)
- Support and release in production helped with the selection and configuration of server technologies

## Recent projects

### CRM system for removing illegitimate negative reviews

[Consumer Fusion](https://consumerfusion.com/)

Consumer Fusion is the only All-in-One Reputation Management Solution that specializes in removing illegitimate negative reviews on over 60+ online review sites.

Technologies
- PHP(Symfony)
- PostgreSQL
- HTML
- CSS(Bootstrap)
- JavaScript

### The business card of the company

[Gold Front](https://www.goldfront.com/)

Gold Front is an award-winning creative studio in San Francisco. They help companies find their greatness and tell their story-through branding, advertising, and video production.

Technologies
- PHP(CraftCMS)
- MySQL
- HTML
- CSS(SCSS)
- JavaScript

### Corporate Website

[GiftNow](https://www.giftnow.com/)

GiftNow, a digital gifting service offered by Loop Commerce allows shoppers to purchase a gift online without needing to know the recipient’s preferred size or color, or even the shipping address.

Technologies
- PHP(CraftCMS)
- MySQL
- HTML
- CSS(SCSS)
- JavaScript
