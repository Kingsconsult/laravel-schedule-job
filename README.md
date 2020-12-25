### Laravel Schedule Job

## This repo is the code snippets for my article on [Schedule a task to run at a specific time in laravel (CronJob)](https://dev.to/kingsconsult/schedule-a-task-to-run-at-a-specific-time-in-laravel-cronjob-5aaf). This article will teach you how to create a task in Laravel that will run at your specific time

## How to Run
**1. Fork or Clone the repo to your machine**

**2. Composer install**

**3. Copy the .env.example and create .env file**

> cp .env.example .env


**5. Setup your example configuration**

![.env file](https://res.cloudinary.com/kingsconsult/image/upload/v1608900624/Schedule%20Job/3_xjtiyx.png)

**6. Run the scheduler on the terminal**

> php artisan schedule:work
