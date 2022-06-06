# Augmented Reality Test

This project used AR.js to 

## Requirements
* Install [Node.js](https://nodejs.org/en/) 

## Setup
* Open the index.html and replace the LATITUDE and LONGITUDE
* optional: replace the image in the `assets` folder
* generate a SSL certificate
    * example: (Windows with [OpenSSL v1.1.1o](https://slproweb.com/products/Win32OpenSSL.html)) ` openssl req -config "C:\Program Files\OpenSSL-Win64\bin\cnf\openssl.cnf" -newkey rsa:2048 -new -nodes -x509 -days 3650 -keyout key.pem -out cert.pem`

## Start the server
* `npm run dev`
* Open the link displayed in the logs in a broswer
* Example:
    ```
    Available on:
        https://192.168.1.10:8080
        https://127.0.0.1:8080
    ```