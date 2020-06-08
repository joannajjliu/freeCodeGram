# Introduction
- Code from freeCodeCamp's "Laravel PHP Framework Tutorial - Full Course for Beginners (2019)"
    - Creating an Instagram clone in Laravel

## Starting the file
- run "php artisan serve" -> page will show up in port 8000

## Project build process (for reference only, shouldn't need to do again)
- Amazing built-in authentication: Add "Login" and "Register" authentication options, and pages:
    - Install "php artisan make:auth"
        - In the latest php version, this has been replaced by "composer require laravel/ui" > "php artisan ui vue --auth"
- "npm install" > "npm run dev" once or twice (based on instructions) to compile the frontend
- Instructions for databases (need to setup a db, using sqlite in this tutorial)
    - vim database/database.sqlite 
    - in .env, change to "DB_CONNECTION=sqlite", and delete any other "DB_..." lines (won't be using in this tutorial)
    - run "php artisan migrate" in cmdline to generate users, and password tables