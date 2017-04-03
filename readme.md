## ckanext-en-nz
This repository contains the translation for New Zealand English for CKAN. 

Its primary function is to rename organization to collection.

## Installing
* Copy en_NZ directory to /usr/lib/ckan/default/src/ckan/ckan/i18n

## Configuration
Change the default language in the /etc/ckan/default/production.ini
ckan.locale_default = en_NZ

## Updating the translation
See CKAN's [i18n](http://docs.ckan.org/en/ckan-2.6.1/contributing/i18n.html) documentation for requirements.

# Compiling
To compile use the following command

```
pybable -f -i ckan.po -o ckan.mo
```
