# Module installation

## Composer

Go to your document root directory.

### Module installation

You can now install the module with the following command line:

```
composer require hipay/hipay-fullservice-sdk-magento2
```

After the Composer installation, you must run these command lines:  

`bin/magento module:enable --clear-static-content HiPay_FullserviceMagento`  
`bin/magento setup:upgrade`  
`bin/magento cache:clean`  

If no errors are displayed, the module is installed.  
You can then go to your Magento Admin Panel.