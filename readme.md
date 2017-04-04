## ckanext-en-nz
This repository contains the translation and modifications of the English Language for web sites related to Landcare Research for CKAN.

Its primary function is to rename organization to collection.

## Installing
* Copy en_LRNZ directory to /usr/lib/ckan/default/src/ckan/ckan/i18n

## Configuration
Change the default language in the /etc/ckan/default/production.ini
ckan.locale_default = en_LRNZ

## Updating the translation
See CKAN's [i18n](http://docs.ckan.org/en/ckan-2.6.1/contributing/i18n.html) documentation for requirements.

# Compiling
To compile use the following command

```
pybable compile -f -i ckan.po -o ckan.mo
```
