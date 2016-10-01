# mysql-dump-every-country-state
I have gone through so many online resource to get list of countries and it's primary information like iso, iso3, currency format etc. but all the resource i found are not completed. Here i found one mysql dump file contains a single SQL dump for two tables – region and subregion.

Region contains 248 entries, with the following data for each country: ISO code, 3 digit ISO code, fips code, country name, continent, currency code, currency name, phone prefix, postal code regex, languages and geonameid. Subregions contains region ID, name and timezone. The timezone format is “America/Los_Angeles”, “Europe/Madrid”, etc. Unfortunately, some states have multiple timezones and this is not taken into account.
