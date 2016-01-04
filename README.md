fma_layerednavigation
=================================

FME Addons Magento AJAX layered navigation

For more information please visit https://www.fmeaddons.com/magento/free-ajax-layered-navigation-extension.html

*Please note that we are not the developer of this extension. In this repo we only added modman and composer support. We will not provide any support for this repository. If you have any problems on integration, please use the official link mentioned above.*


Installation
------------

Add the `require` and `repositories` sections to your composer.json as shown below and run `composer update`.


```
{
    ...   
	
    "repositories": [
        {"type": "git", "url": "https://github.com/kirchbergerknorr/fma_layerednavigation"}
    ],
    
    "require": {
        "kirchbergerknorr/fma_layerednavigation": "*"
    },  
	
    ...
}
```