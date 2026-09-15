<img src="./assets/img/photo.jpg" alt="Personal Photo" width="350">

# Andrey Fits 

## Backend Developer

Address: Brest, Belarus

Email: [andreyfits@gmail.com](mailto:andreyfits@gmail.com)

Phone: +375 44 729-10-96

## Social

- LinkedIn: [Andrei Fits](https://www.linkedin.com/in/andreifits/)
- Instagram: [@andreyfits](https://www.instagram.com/andreyfits/)
- Telegram: [@andreyfits](https://t.me/andreyfits)

## About me

Senior Backend Engineer with 6+ years of experience in large-scale platforms, including B2B iGaming, enterprise e-commerce, and hosting infrastructure. Proficient in PHP, Laravel, Symfony components, MySQL, Redis, REST APIs, PHPUnit, and background jobs, with hands-on experience in high-load systems, back-office tooling, and platform optimization. Focused on improving performance, scalability, and reliability of production systems serving millions of users and hundreds of thousands of websites, as well as building internal tools to streamline operational workflows.

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

- PHP
- Symfony
- Laravel
- PHPUnit
- MySQL
- PostgreSQL
- Redis
- Git
- HTML5
- CSS3
- JavaScript Basics
- Linux
- Docker
- Grafana
- Kibana

## Work Experience

### Senior Backend Developer

Apr 2025 - Current

Softgamings - Global iGaming provider serving 100M+ players with 50B+ annual transactions

- Developed a backoffice tournament testing interface from scratch, reducing manual validation effort by 70% by enabling internal checks of player status, balances, bets, wins, and free-round distribution
- Optimized MySQL queries and Laravel-based API flows, reducing response times by 30-40% during peak player activity
- Implemented cron-based background jobs to migrate thousands of players between database shards, ensuring scalability and data consistency
- Added new endpoint validations across loyalty APIs, reducing invalid loyalty states and manual rechecks by 50%
- Maintained backend APIs, covered core business logic with PHPUnit tests, and monitored Kafka event flows and production systems using Grafana and Kibana, ensuring stability of business-critical flows

### Senior Backend Developer

Mar 2023 - Apr 2025

Webhost1 - Large hosting platform serving 130K+ active websites in production

- Developed and maintained Symfony backend services for a hosting platform serving 130,000+ active websites
- Implemented and supported Vue-based frontend components integrated with Symfony APIs
- Rewrote a legacy VDS/VPS purchasing module, improving reliability for core revenue-generating flows
- Designed and implemented Stripe-based payment workflows, handling high-volume recurring and one-time payments
- Built a real-time online chat using Go and WebSockets, increasing message exchange speed by 80%
- Optimized backend code and MySQL queries, reducing response times and lowering production incidents on high-load services

### Backend Developer

Nov 2021 - Mar 2023

EPAM - Global engineering company serving 345+ Forbes Global 2000 clients across 55+ countries

- Developed and maintained PHP backend services for a high-load enterprise e-commerce platform serving 21M+ customers
- Supported backend systems handling 30M+ products and complex business logic
- Refactored legacy PHP code and optimized SQL queries, improving performance and stability
- Collaborated with distributed teams across multiple regions, ensuring reliable delivery

### Backend Developer

Jul 2020 - Nov 2021

EffectiveSoft - Global software engineering company with 23+ years of experience and 1,000+ projects

- Developed and maintained a production website supporting 70+ category launches for enterprise clients (Uber, Robinhood, Newsela)
- Ensured platform performance and reliability linked to 5X–8X valuation growth
- Refactored and optimized legacy PHP code, reducing technical debt and improving long-term stability

### Backend Developer

Mar 2017 - Jun 2020

Siteguarding - Investigated and remediated security incidents across hundreds of websites

- Removed malware from hundreds of compromised websites, cleaning PHP/JavaScript codebases and databases
- Restored affected websites to production state within hours, improving availability and post-incident performance
- Identified attack vectors via log and database analysis, preventing recurring security incidents
- Optimized backend code and database queries after cleanup, stabilizing performance and reducing repeat infections

## Code Example

**Task:** *The array of integers is given. It is necessary to shift the zero elements to the end of the array, while maintaining the relative order of the non-zero elements.*

```php
function shiftZeroValues($arr)
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
    printf("[%s] => [%s]\n", implode(', ', $arr),  implode(', ', shiftZeroValues($arr)));
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
