# Quickstart

## Run Application

1. Set values in `.env` file.

2. Run container

    ```bash
    sudo docker-compose up -d
    ```

3. Run on browser on https://localhost (or any hostname that you config in `.env`)

## Login as Wordpress Admin

Open https://localhost/wp-admin, then login with this credentials:

* username: `admin`
* password: `password`

## Activate Divi Themes

1. Login as admin
2. Go to **Appearances** > **Theme** menu
3. Activate **Divi** theme

# Developer Guide

## Access to Database

Access to database with these credentials:

* host: `localhost` (or any you set in `.env`)
* username: `mysqluser` (or any you set in `.env`)
* database: `wpdb` (or any you set in `.env`)
* password: `password` (or any you set in `.env`)
* root password: `rootpassword` (or any you set in `.env`)

## Access Logs

Go to container's bash, then see files in `/var/logs`.
