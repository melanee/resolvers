# iceland-resolvers

This is a list of public DNS resolvers supporting the
DNSCrypt protocols.

Adjust the `require_*` options in dnscrypt-proxy to filter that list
according to your needs.

To use that list, add this to the `[sources]` section of your
`dnscrypt-proxy.toml` configuration file:

    [sources.'iceland-resolvers']
    urls = ['https://raw.githubusercontent.com/melanee/resolvers/main/iceland-resolvers.md']
    minisign_key = 'RWTOlBiNAsKzuOfBdZ89LVl8YFr0ZR9Q+nlo7qBR22YYrvtth78tQAys'
    cache_file = 'iceland-resolvers.md'

--


## ams-dnscrypt-nl

Resolver in Amsterdam. Dnscrypt protocol. Non-logging, non-filtering, DNSSEC.

sdns://AQcAAAAAAAAADTUxLjE1LjEyNC4yMDggvBOI9XY-Pex18ckPyRW_torq3-scRfaYUYBjnGDn8WIfMi5kbnNjcnlwdC1jZXJ0LmFtcy1kbnNjcnlwdC1ubA


## ams-dnscrypt-nl-ipv6

Resolver in Amsterdam. Dnscrypt protocol. Non-logging, non-filtering, DNSSEC.

sdns://AQcAAAAAAAAAF1syMDAxOmJjODoxODMwOjIwMTg6OjFdILwTiPV2Pj3sdfHJD8kVv7aK6t_rHEX2mFGAY5xg5_FiHzIuZG5zY3J5cHQtY2VydC5hbXMtZG5zY3J5cHQtbmw

## cs-berlin

Berlin, Germany DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTM3LjEyMC4yMTcuNzUgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz

## cs-de

Frankfurt, Germany DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAACzE0Ni43MC44Mi4zIDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-dk

Denmark DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTM3LjEyMC4yMzIuNDMgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-dus1

Dusseldorf, Germany 1 DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjIxMy4yMDIuMjE2LjEyIDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-dus2

Dusseldorf, Germany 2 DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADzIxMy4yMDIuMjE2LjIzNiAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-dus3

Dusseldorf, Germany 3 DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjg5LjE2My4yMjEuMTgxIDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-dus4

Dusseldorf, Germany 4 DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjg1LjExNC4xMzguMTE5IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw


## cs-finland

Finland DNSCrypt server provided by https://cryptostorm.is

sdns://AQIAAAAAAAAADjE4NS4xMTcuMTE4LjIwIDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw

## cs-is

Iceland DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTgyLjIyMS4xMjguNDQgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz

## cs-lv

Latvia DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADzEwOS4yNDguMTQ5LjEzMyAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM

## cs-nl

Netherlands DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADTE4NS4xMDcuODAuODQgMTNyrVlWMsJBa4cvCY-FG925ZShMbL6aTxkJZDDbqVoeMi5kbnNjcnlwdC1jZXJ0LmNyeXB0b3N0b3JtLmlz


## cs-nl2

Netherlands 2 DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADzE3Mi4xMDcuMjI2LjEwNyAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM


## cs-norway

Oslo, Norway DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADjkxLjIxOS4yMTUuMjI3IDEzcq1ZVjLCQWuHLwmPhRvduWUoTGy-mk8ZCWQw26laHjIuZG5zY3J5cHQtY2VydC5jcnlwdG9zdG9ybS5pcw

## cs-swe

Sweden DNSCrypt server provided by https://cryptostorm.is/

sdns://AQIAAAAAAAAADzEyOC4xMjcuMTA0LjEwOCAxM3KtWVYywkFrhy8Jj4Ub3bllKExsvppPGQlkMNupWh4yLmRuc2NyeXB0LWNlcnQuY3J5cHRvc3Rvcm0uaXM

## dct-de1

DNSCrypt | IPv4 only | Non-logging | Non-filtering | DNSSEC | Düsseldorf, Germany.

sdns://AQcAAAAAAAAAFDEwMy4xNTguMjIzLjE2Mjo4NDQzIB9z-95JSBqhYTv8UIQqUs65Ym2DYNXzBf5cN-kH8Pt9FzIuZG5zY3J5cHQtY2VydC5kY3QtZGUx

## dnscrypt-de-blahdns-ipv4

Blocks ad and Tracking, no Logging, DNSSEC, Hosted in Germany. By https://blahdns.com/

sdns://AQMAAAAAAAAAEjc4LjQ2LjI0NC4xNDM6ODQ0MyCFE6lrxOCDS5UNY7UC6NPi1U0ElmsmApM06QcduiP8KxsyLmRuc2NyeXB0LWNlcnQuYmxhaGRucy5jb20


## dnscrypt-de-blahdns-ipv6

Blocks ad and Tracking, no Logging, DNSSEC, Hosted in Germany. By https://blahdns.com/

sdns://AQMAAAAAAAAAG1syYTAxOjRmODpjMTc6ZWM2Nzo6MV06ODQ0MyCFE6lrxOCDS5UNY7UC6NPi1U0ElmsmApM06QcduiP8KxsyLmRuc2NyeXB0LWNlcnQuYmxhaGRucy5jb20


## dnscrypt.eu-nl

Free, non-logged, uncensored. Hosted by RamNode.

sdns://AQcAAAAAAAAADjE3Ni41Ni4yMzcuMTcxIGfADywhxVSBRd18tGonGvLrlpkxQKMJtiuNFlMRhZxmJTIuZG5zY3J5cHQtY2VydC5yZXNvbHZlcjEuZG5zY3J5cHQuZXU


## dnscrypt.eu-nl-ipv6

Free, non-logged, uncensored. Hosted by RamNode.

sdns://AQcAAAAAAAAAGlsyYTAwOmQ4ODA6MzoxOjphNmMxOjJlODldIGfADywhxVSBRd18tGonGvLrlpkxQKMJtiuNFlMRhZxmJTIuZG5zY3J5cHQtY2VydC5yZXNvbHZlcjEuZG5zY3J5cHQuZXU

## ffmuc.net

An open (non-logging, non-filtering, non-censoring) DNSCrypt resolver operated by Freifunk Munich with nodes in DE.
https://ffmuc.net/

sdns://AQcAAAAAAAAADzUuMS42Ni4yNTU6ODQ0MyAH0Hrxz9xdmXadPwJmkKcESWXCdCdseRyu9a7zuQxG-hkyLmRuc2NyeXB0LWNlcnQuZmZtdWMubmV0


## ffmuc.net-v6

An open (non-logging, non-filtering, non-censoring) DNSCrypt resolver operated by Freifunk Munich with nodes in DE.
https://ffmuc.net/

sdns://AQcAAAAAAAAAGlsyMDAxOjY3ODplNjg6ZjAwMDo6XTo4NDQzIAfQevHP3F2Zdp0_AmaQpwRJZcJ0J2x5HK71rvO5DEb6GTIuZG5zY3J5cHQtY2VydC5mZm11Yy5uZXQ


## meganerd

DNSCrypt server by MegaNerd.nl (IPv4) - https://meganerd.nl/encrypted-dns-server
Hosted in Amsterdam (AMS1), The Netherlands.

Non-logging, non-filtering, supports DNSSEC.

sdns://AQcAAAAAAAAADjEzNi4yNDQuOTcuMTE0IPyq3HBOXuNgu6FO4pU71Si6CTV6kPD85NA6AThr_6tiGDIuZG5zY3J5cHQtY2VydC5tZWdhbmVyZA


## meganerd-doh-ipv6

DoH server by MegaNerd.nl (IPv6) - https://meganerd.nl/encrypted-dns-server
Hosted in Amsterdam (AMS1), The Netherlands.

Non-logging, non-filtering, supports DNSSEC.

sdns://AgcAAAAAAAAAKFsyMDAxOjE5ZjA6NTAwMTpjYmI6NTQwMDowM2ZmOmZlMDc6ZjcwZF2gzBBg05yDKbYrb7x9DW35MJhpuYHn5jktXNj6QI9NgOYgRE69Z7uD-IB7OSHpOKyReLiCvVCq2xEjHwRM9fCN984VY2hld2JhY2NhLm1lZ2FuZXJkLm5sBC9kb2g


## meganerd-ipv6

DNSCrypt server by MegaNerd.nl (IPv6) - https://meganerd.nl/encrypted-dns-server
Hosted in Amsterdam (AMS1), The Netherlands.

Non-logging, non-filtering, supports DNSSEC.

sdns://AQcAAAAAAAAAJ1syMDAxOjE5ZjA6NTAwMTpjYmI6NTQwMDozZmY6ZmUwNzpmNzBkXSD8qtxwTl7jYLuhTuKVO9Uougk1epDw_OTQOgE4a_-rYhgyLmRuc2NyeXB0LWNlcnQubWVnYW5lcmQ


## pwoss.org-dnscrypt

No filter | No logs | DNSSEC | Nuremberg, Germany (netcup) | Maintained by https://pwoss.org/ (Dan)

sdns://AQcAAAAAAAAAEzQ1LjE0Mi4xNzYuMTcwOjQ0MzQgZF8FTkuFVFw6YP5x8ydebnTb8ONP7Ti6P0K1REyhUHgZMi5kbnNjcnlwdC1jZXJ0LnB3b3NzLm9yZw

## scaleway-ams

DNSSEC/Non-logged/Uncensored in Amsterdam - DEV1-S instance donated by Scaleway.com
Maintained by Frank Denis - https://fr.dnscrypt.info

sdns://AQcAAAAAAAAADTUxLjE1LjEyMi4yNTAg6Q3ZfapcbHgiHKLF7QFoli0Ty1Vsz3RXs1RUbxUrwZAcMi5kbnNjcnlwdC1jZXJ0LnNjYWxld2F5LWFtcw


## scaleway-ams-ipv6

DNSSEC/Non-logged/Uncensored in Amsterdam - IPv6 only - DEV1-S instance donated by Scaleway.com
Maintained by Frank Denis - https://fr.dnscrypt.info

sdns://AQcAAAAAAAAAFlsyMDAxOmJjODoxODIwOjUwZDo6MV0g6Q3ZfapcbHgiHKLF7QFoli0Ty1Vsz3RXs1RUbxUrwZAcMi5kbnNjcnlwdC1jZXJ0LnNjYWxld2F5LWFtcw

## sth-dnscrypt-se

Resolver in Stockholm, Sweden. DNSCrypt server. Non-logging, non-filtering, DNSSEC.

sdns://AQcAAAAAAAAADTQ1LjE1My4xODcuOTYgeXlaphvMhHruyoIiBZWFCQqgabN91D0bQEBb3nJ9yUYfMi5kbnNjcnlwdC1jZXJ0LnN0aC1kbnNjcnlwdC1zZQ


## uncensoreddns-dk-ipv4

Also known as censurfridns.
DoH, no logs, no filter, DNSSEC, unicast hosted in Denmark - https://blog.uncensoreddns.org

sdns://AgcAAAAAAAAADDg5LjIzMy40My43MaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhl1bmljYXN0LnVuY2Vuc29yZWRkbnMub3JnCi9kbnMtcXVlcnk


## uncensoreddns-dk-ipv6

Also known as censurfridns.
DoH, no logs, no filter, DNSSEC, unicast hosted in Denmark - https://blog.uncensoreddns.org

sdns://AgcAAAAAAAAAElsyYTAxOjNhMDo1Mzo1Mzo6XaDMEGDTnIMptitvvH0NbfkwmGm5gefmOS1c2PpAj02A5iBETr1nu4P4gHs5Iek4rJF4uIK9UKrbESMfBEz18I33zhl1bmljYXN0LnVuY2Vuc29yZWRkbnMub3JnCi9kbnMtcXVlcnk
