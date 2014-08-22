vultr-api-client
================

API Client for Vultr.com

Simply pass your [API token](https://my.vultr.com/settings/), and it will retrieve a list of information

    <?php
    $token = 'your_token';
    $vultr = new Vultr($token);
    var_dump($vultr);
    ?>
