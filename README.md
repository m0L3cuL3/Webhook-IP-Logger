# WebHook IP Tracker

IP Logger using an ip tracker and sends the traffic to a discord channel via webhooks



##  Installation Process
1. Upload the index.php and script.php files to the same level in the tree structure of your web hosting.
2. To connect your webhook, just replace **webhook here** with the link of your webhook
```php
/*<------- WebHooks ------------>*/
$webhook = "webhook here";
```

##  Modification

To change the display of the data, modify this part with Markdown
```php                             
"
IP: {$geoplugin->ip}
Os: $user_os
Navigator: $user_browser
Datation: $time
City: {$geoplugin->city}
Region: {$geoplugin->region}
Region Code: {$geoplugin->regionCode}
Region Nom: {$geoplugin->regionName}
DMA Code: {$geoplugin->dmaCode}
Pays: {$geoplugin->countryName}
Code pays: {$geoplugin->countryCode}
Europeen ?: {$geoplugin->inEU}
Latitude: {$geoplugin->latitude}
Longitude: {$geoplugin->longitude}
Accuracy (Miles): {$geoplugin->locationAccuracyRadius}
Timezone: {$geoplugin->timezone}
"
```

credits to https://github.com/Elyasuuuuu
