# Let's run Doom on Lichee RV Dock!

This is a custom `buildroot` based system with `SDL2`, `DirectFB` and `chocolate-doom`. Unpacked system is ca. 120MB. Login as root:

```
u:root
pwd: licheerv
```

Wifi is also activated, modify `/etc/wpa_supplicant.conf` as needed (use `nano` for that). `dropbear` server is installed so you can login with `ssh`.
There are DirectFB demos installed also. You can try those out, eg. (press 'q' to exit):

```
# df_andi
```
or 

```
# df_neo
```
But then there is the Doom (with preinstalled original WAD). Hopefully its OK for everybody...
To setup everything:
```
# chocolate-doom-setup
```
You can save and run Doom from setup or exit and then:
```
# chocolate-doom
```
There are also 'chocolate-heretic' and 'chocolate-hexen' but these are not playeable for now.
Enjoy!

