# Druact API

## Intro

This is a Drupal 8 module that will enable all modules and set up configuration
that is required to create a simple decoupled website. To find out more please 
visit this blog post:

http://www.gorannikolovski.com/react-js-and-drupal-8-decoupled-website-part-1

## Demo

To see fully functional demo visit the following website:

http://druact.gorannikolovski.com

## Installation

You can download Druact API module on the Github release page:

https://github.com/gnikolovski/druact_api/releases

1. Composer (recommended):

Since this module is not published on drupal.org or on packagist.org you will
need to add the VCS repository to your composer.json file. You need to add this:

"repositories": [
    {
        "type": "vcs",
        "url":  "https://github.com/gnikolovski/druact_api"
    }
]

Then you can run the following command to install it:

```
composer require gnikolovski/druact_api
```

2. Drush:

Since this module is not published on drupal.org you will need to download it 
from the Github and place it in your /modules directory. After that execute the 
following command:

```
drush en druact_api -y
```

3. Manual installation

To install the Druact API module, proceed in the usual way: download and unzip 
it, then place it in the /modules directory for your site. Navigate to the 
Extend page (admin/modules) and install Druact API.

You also need to download the following required modules:

Token https://www.drupal.org/project/token
REST UI https://www.drupal.org/project/restui
Contact message REST https://www.drupal.org/project/contact_message_rest
Contact Storage https://www.drupal.org/project/contact_storage

### AUTHOR

Goran Nikolovski  
Website: (http://www.gorannikolovski.com)  
Drupal: (https://www.drupal.org/user/3451979)  
Email: nikolovski84@gmail.com  

Company: Studio Present, Subotica, Serbia  
Website: (http://www.studiopresent.com)  
Drupal: (https://www.drupal.org/studio-present)      
Email: info@studiopresent.com
