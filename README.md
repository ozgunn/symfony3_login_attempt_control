# symfony3_login_attempt_control

Pre-login IP checks for Symfony 3

### Features:
- Limits the maximum number of login attempts that can be made from an IP address in a given period of time.
- Limits the number of user sessions that can be made from an IP address.
- Blacklist/Whitelist feature.
  - Prevents login from the IP address in the Blacklist.
  - Exempts the IP address in the whitelist from the session number limit.
