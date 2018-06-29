# **Move Certificates**
## Description
Moves certificates from the user certificate store to the system store. Also removes the *Network may be monitored* warning.

## Changelog
v1.2

  * Added missing system folder and placeholders

v1.1

  * Added more info to README

v1

  * Initial release

## Notes
If for some reason you do not want all your certificates moved from the user store to the system store, you can specify which certificate to move in /common/post-fs-data.sh by replacing the * with the name of the certificate; i.e.,

`mv -f /data/misc/user/0/cacerts-added/12abc345.0 $MODDIR/system/etc/security/cacerts`


