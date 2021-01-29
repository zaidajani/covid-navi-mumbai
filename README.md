# covid-navi-mumbai

COVID19 showcasing website made using HTML, CSS, PHP and JavaScript 

For website info, check out sitemap.xml.

## First step, start the xampp server and make a file as getData.php

The content should be as follows.

```php
<?php

    $servername = "localhost";
    $username = "";
    $password = "";
    $name = "covidnav_navi_mumbai";

    $conn = mysqli_connect($servername, $username, $password, $name);
        
```

* If you have passwords and database on cloud, then fill the info above as per you.

Then just start server and you will see the web application in action.

## Make a `case_data` Table in the database

Schema should be:
places
total cases
deceased

## To update the data, update data in the database

## Enjoy your application
