![Personal Photo](./assets/img/photo.jpg "Andrey Fits")

# Andrey Fits 

## PHP Developer

Address: Brest, Belarus

Email: [andreyfits@gmail.com](mailto:andreyfits@gmail.com)

Phone: +375 44 729-10-96

## Social

- LinkedIn: [Andrei Fits](https://www.linkedin.com/in/andreifits/)
- Instagram: [@andreyfits](https://www.instagram.com/andreyfits/)
- Telegram: [@andreyfits](https://t.me/andreyfits)

## About me

Experienced PHP Developer with experience working in the information technology and services industry. Skills in
programming on PHP, MySQL, and other information technology. As someone who takes responsibility for his
own personal development, I'm continually evaluating and upgrading my skills in order to stay at the cutting plane
of web development. Created backend part of Consumer Fusion(Web Portal for business management), Internal CRM system
for Oxagile, Websites on the WordPress, and CraftCMS for Effectivesoft Corporation.


## Education

### Software technician

MGVR College of Engineering

Department of Computer Technologies: Information technology

2011-2014

### The teacher-programmer 

Belarusian State University of Informatics and Radioelectronics

Faculty of Radioengineering and electronics: Information Radiotechnologies

2014-2018

## Skills

- HTML5
- CSS3
- JavaScript Basics
- PHP
- MySQL
- Git
- Linux
- Docker


## Work Experience

### PHP Developer

Apr 2023 - Jun 2023

[Lime Vizio](https://www.limevizio.com/)

- Planning
- Development of new features
- Fixing Bugs in PHP code
- Search and elimination of bugs
- Refactoring old code
- Made code review and code refactoring of colleagues

### PHP Developer

Nov 2021 - Feb 2023

[EPAM Systems, Inc.](https://www.epam.com/)

- Developed the backend part
- Sprint Planning & Backlog grooming
- Search and elimination of bugs
- Refactoring old code
- Was involved in meetings with customers
- Made code review and code refactoring of colleagues (GitHub)

### PHP Developer

Jul 2021 - Oct 2021

[Oxagile](https://www.oxagile.com/)

- Development frontend and backend parts of the admin panel
- Was involved in estimations
- Discussions and meetings with the customer
- Improvements after comments of QA, customer, and designer
- Made code review and code refactoring of colleagues (GitLab)

### PHP Developer

Jul 2020 - Jun 2021

[EffectiveSoft Corporation](https://www.effectivesoft.com/)

- Developed and designed the whole backend part
- Was involved in estimations
- Was involved in meetings with the customer
- Improvements after comments of QA, customer, and designer
- Made code review and code refactoring of colleagues (BitBucket)
- Support and release in production helped with the selection and configuration of server technologies

## Recent projects

### Ecommerce

[Blossom Flower](https://www.blossomflowerdelivery.com/)

Blossom Flower Delivery is committed to quality and service. Our guarantee is our personal commitment to our customers to create long term relationships. Your satisfaction is our Number One priority, not just because it’s our job, but because we really do care.

Technologies
- PHP
- Woocommerce
- MySQL
- HTML
- CSS
- JavaScript
- JQuery
- API
- Bootstrap

### Retail & Distribution

[Wayfair Inc.](https://wayfair.com/)

Wayfair Inc. is an American e-commerce company that sells furniture and home goods. Formerly known as CSN Stores, the company was founded in 2002. Their digital platform offers 14 million items from more than 11,000 global suppliers.

Technologies
- PHP
- Python
- MSSQL
- HTML
- CSS
- JavaScript

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

## Languages

English — Intermediate

Russian — Native

Belarusian — Native

## Interests

- Travel
- Read
- Music
- Fitness
- Programming
