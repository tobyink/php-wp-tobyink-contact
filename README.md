# php-wp-tobyink-contact
Simple email contact form plugin for Wordpress (uses Bootstrap 4 classes)

## Features

* Simple, one PHP file (under 250 lines of code including HTML), so pretty easy to modify to your needs
* Supports ReCAPTCHA v2 (the tick box)
* Multiple destination addresses for different categories of message

## Config

* **ReCAPTCHA Key** and **ReCAPTCHA Secret** — codes from ReCAPTCHA
* **Addresses (JSON)** — list of categories and email addresses to send messages to. For example:
```
[
  [ "General Enquiries", "enquiries@example.net" ],
  [ "Sales",  "sales@example.net" ],
  [ "Customer Support",  "support@example.net" ]
]
```
