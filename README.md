# magento2-sample-module
Minimal setup for a Magento2 module

##Prerequests:
Working Magento2 installation

##Add the module to your Magento2 installation
* Copy this Project to your app/code folder
* Clear caches 
* Run php bin/magento module:enable Bpoiss_MyModule in your Magent2 base directory

Open your magento2 installation in your browser and add `/mymodule/index/index` to the URL to go to a predefined Controller Action that simply renders a template file.
