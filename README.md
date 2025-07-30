# Address Standardizer

> Based on [Address Standardization Solution (PHP Edition)](http://www.analysisandsolutions.com/software/addr/addr.htm)

This library helps format a delivery address according to USPS addressing standards. Useful for normalizing
addresses for caching.

Recommended only on Street Lines, not full address! US Addresses only!

## Usage

```php
use JaggedJax\AddressStandardizer\Address;
$address = Address::standardize('1600 Pennsylvania Avenue');
echo $address; // 1600 PENNSYLVANIA AVE
```

## Changelog

 - 1.1.1 Transliterate Euro chars to US ASCII equivalent rather than dropping them
 - 1.1.0 Make it static and add initial typing
 - 1.0.0 Initial refactor (namespaced, cleaned up naming, composer, etc)