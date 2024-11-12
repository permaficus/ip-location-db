# [ip-location-db](https://github.com/sapics/ip-location-db)/dbip-city-mmdb

## Download

| Database | Type | License | Updated | IPv4 | IPv6 | IPv4-num | IPv6-num |
|---|---|---|---|---|---|---|---|
| [DB-IP Lite](https://github.com/sapics/ip-location-db/tree/main/dbip-city/)<br><br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/dbip-city?color=success&style=flat-square&label=GZ)](https://www.npmjs.com/package/@ip-location-db/dbip-city)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/dbip-city-7z?color=success&style=flat-square&label=7z)](https://www.npmjs.com/package/@ip-location-db/dbip-city-7z)<br>[![npm version](https://img.shields.io/npm/v/@ip-location-db/dbip-city-mmdb?color=success&style=flat-square&label=MMDB)](https://www.npmjs.com/package/@ip-location-db/dbip-city-mmdb) | City | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) <br> by [DB-IP](https://db-ip.com/) | Monthly | [CSV.gz](https://unpkg.com/@ip-location-db/dbip-city/dbip-city-ipv4.csv.gz)<br>[CSV.7z](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-city-7z/dbip-city-ipv4.csv.7z)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-city-mmdb/dbip-city-ipv4.mmdb) | [CSV.gz](https://unpkg.com/@ip-location-db/dbip-city/dbip-city-ipv6.csv.gz)<br>[CSV.7z](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-city-7z/dbip-city-ipv6.csv.7z)<br>[MMDB](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-city-mmdb/dbip-city-ipv6.mmdb) | [CSV.gz](https://unpkg.com/@ip-location-db/dbip-city/dbip-city-ipv4-num.csv.gz)<br>[CSV.7z](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-city-7z/dbip-city-ipv4-num.csv.7z) | [CSV.gz](https://unpkg.com/@ip-location-db/dbip-city/dbip-city-ipv6-num.csv.gz)<br>[CSV.7z](https://cdn.jsdelivr.net/npm/@ip-location-db/dbip-city-7z/dbip-city-ipv6-num.csv.7z) |


## MMDB Format

```
country_code, city, state1, state2, latitude, longitude, postcode, timezone
```


### country_code

`country_code` is the two-letter code defined in [ISO 3166-1 alpha-2](https://wikipedia.org/wiki/ISO_3166-1_alpha-2).
You can get the `country name, capital, continent, currency, languages, etc.` from the `country_code` by [Countries Database](https://github.com/annexare/Countries) in JSON, CSV, SQL format.


## Referenced Database and License



### [DB-IP](https://db-ip.com/) database [Update: Monthly]

You could download and read the license from [ip-to-asn-lite](https://db-ip.com/db/download/ip-to-asn-lite) or [ip-to-country-lite](https://db-ip.com/db/download/ip-to-country-lite) or [ip-to-city-lite](https://db-ip.com/db/download/ip-to-city-lite).
Most of the AS Organization name used in [asn](https://www.npmjs.com/package/@ip-location-db/asn) uses [ip-to-asn-lite](https://db-ip.com/db/download/ip-to-asn-lite) database.
We also use [ip-to-asn-lite](https://db-ip.com/db/download/ip-to-asn-lite) to get AS Number from ip address as a supplemental.

These database are licensed under a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), so, **you must create attribution to [DB-IP.com](https://db-ip.com/) for using DB-IP database**.<br>
In the case of a web application, you must include a link back to DB-IP.com on pages that display or use results from the database. You may do it by pasting the HTML code snippet into your code: `<a href='https://db-ip.com/'>IP Geolocation by DB-IP</a>`.<br>
If you need better accuracy or no attribution or daily updates, please use the [Commercial Version of db-ip](https://db-ip.com/db/ip-to-country).
