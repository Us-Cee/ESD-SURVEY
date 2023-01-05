# php-survey-builder

*php-survey-builder* is a PHP web application that lets you create surveys and collect survey responses. The results can be viewed on charts and exported to CSV. The survey data is stored within a sqlite3 database by default, and can also be stored in a mysql or postgresql database.  Edit config/Database.ini to use mysql or postgresql.

Enterprise and Resource Development Survey. This is a survey with drop-down selections and scoring/weighting. To assess the viability of adding a supplier to an approved retailer suppliers list, based on BBBEE scoring, capability, Quality and Logistics capabilities.

![screenshot of php-survey-builder](https://raw.github.com/phpdave11/php-survey-builder/master/screenshots/survey_edit.png)

## Default login

The default login is 'root@localhost' with a password of '12345'. You can add and remove logins from the Users tab.

## Quick Start
```sh
git clone https://github.com/phpdave11/php-survey-builder.git
cd php-survey-builder
php -S localhost:8080
```

## Troubleshooting

Be sure that your data/ directory is writable by your web server.
