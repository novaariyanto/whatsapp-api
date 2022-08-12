# [whatsva.id] WhatsApp API PHP SDK

 Whatsva/waapi PHP library for WhatsApp API to send the whatsappp messages in PHP provided by whatsva.id
# Installation

Just download whatsva.class.php or use Composer: 

```
composer require whatsva/waapi
```


# Example usage

```php
<?php
require_once ('vendor/autoload.php'); // if you use Composer
//require_once('ultramsg.class.php'); // if you download ultramsg.class.php

$instance_key="Mqw66dHfmw2k"; // whatsva.id token
$jid="62895361034833"; // whatsva.id instance id
$message = "hello";
$client = new Whatsva();

$api=$client->sendMessageText($instance_key,$jid,$message);
print_r($api);
```

# Support
Use **Issues** to contact me