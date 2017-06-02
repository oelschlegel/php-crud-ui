# PHP-CRUD-UI

Single file PHP script that adds a UI to a [PHP-CRUD-API](https://github.com/mevdschee/php-crud-api) project

## Requirements

  - curl

## Installation

1. Copy ui.php to your server.

2. Open a text editor and uncomment the code at the very bottom and edit the URL to point to the location of your api.php:
<pre>session_start();
$ui = new PHP_CRUD_UI(array(
    'url' => 'http://localhost/api.php/',
));
echo $ui->executeCommand();</pre>

3. Point your web browser to ui.php
