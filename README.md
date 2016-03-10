# Address Standardizer

> Based on [Address Standardization Solution (PHP Edition)](http://www.analysisandsolutions.com/software/addr/addr.htm)

This library helps format a delivery address according to USPS addressing standards.  Useful for normalizing
addresses for caching (best when used with a 3rd-party solution).

## Usage

```php
$standardizer = new \Galahad\AddressStandardizer\AddressStandardizer();
$address = $standardizer->standardize('1600 Pennsylvania Avenue NW Washington, DC 20500 US');
echo $address; // 1600 PENNSYLVANIA AVE NW WASHINGTON DC 20500 US
```