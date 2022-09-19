# IPSEC Active Users Message Of The Day
This is a simple script to output the current connected IPSEC VPN users that was written to be used as part of the message of the day at login.

To install this message simply drop file `51-vpn-user-status` into your motd directory. Depding on your install you may need to do some additional work to get it to display how you want. For ubuntu this will display directly below the default System information. To install on ubuntu just drop the file into `/etc/update-motd.d` then run `sudo chown root:root 51-vpn-user-status` and `sudo chmod 755 51-vpn-user-status`. Then you should see it appear the next time you login.
