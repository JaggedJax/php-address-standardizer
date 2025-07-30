# Address Standardizer

> Based on [Address Standardization Solution (PHP Edition)](http://www.analysisandsolutions.com/software/addr/addr.htm)

This library helps format a delivery address according to USPS addressing standards. Useful for normalizing
addresses for caching.

Accepts full or partial address strings

## Usage

```php
use JaggedJax\AddressStandardizer\Address;
$address = Address::standardize('1600 Pennsylvania Avenue NW Washington, DC 20500 US');
echo $address; // 1600 PENNSYLVANIA AVE NW WASHINGTON DC 20500 US
```

## Changelog

 - 1.1.0 Make it static and add initial typing
 - 1.0.0 Initial refactor (namespaced, cleaned up naming, composer, etc)