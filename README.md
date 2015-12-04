# Ansible role to install NGINX with PHP5-FPM.

[![Build Status](https://travis-ci.org/fabianfreyer/ansible-nginx_php5-fpm.svg?branch=master)](https://travis-ci.org/fabianfreyer/ansible-nginx_php5-fpm)

## Dependencies

Debian-Based distribution

## Variables

Variable          | Description
----------------- | ---------------------------------------------------------------------------------
`php5_packages`   | A list of Packages (e.g. `php5-gd`) to be installed.
`tunables`        | A list of tunables to be adjusted in /etc/php5/fpm/php.ini

