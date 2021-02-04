# Privs Switcher
Makes you able to grant/revoke privileges on a timed basis.
## Use
The default `grant` and `revoke` commands still work, but they are overwritten with the syntax as additionnal/optionnal params.

`grant <playername> <time-optional> <privstring>`

`grantme <time-optional> <privstring>`

`revoke <playername> <time-optional> <privstring>`

`<time>` param syntax:

- 1s - one second.
- 1m - one minute.
- 1h - one hour.
- 1D - one day (24 hours).
- 1W - one week (7 days).
- 1M - one month (30 days).
- 1Y - one year (360 days).

Additional time syntax can *probably* be added.

### Additionnal informations
The `grant` command normally requiring the `grant` privilege will *still require* the `grant` privilege.
The only command affected is `revoke`, that is usable with the `revoke` and `switcher` privilege.
