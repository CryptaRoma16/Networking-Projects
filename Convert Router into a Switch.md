ISP default gateway: 192.168.254.254

Router 1 - KING
Not necessry if you dont know the IP- reset the router
Materials: UTP cable straight
connect LAN 1 to computer directly
IP: 192.168.0.1
admin
admin

when you are connected to internet
check the IP address : ipconfig
arp -a (should list all the ip addresses use and unused)
if connected to wire see the ethernet adapter section:

Example: router
Default gate: 10.0.0.1
SM:/24 - if /24 any number accepted
for Switch IP: 10.0.0.X - any number

Example Run the command as admin
netsh interface ip set address
name="Ethernet" static 10.0.0.201
255.255.255.0 10.0.0.200


MY wireless LAN adapter wifi:
default gate: 192.168.254.254
MY HP IP add: 192.168.254.114
SM:/24

MY Ethernet adapter:
default gate: 192.168.254.254
MY HP IP add: 192.168.254.115
SM:/24

In my old outer converted to a switch:
login
go to LAN> disable/uncheck DHCP server setup
Change LAN IP address: 192.168.254.2
SM:/24

Run this command and it will work.. you can now log in using the new IP
netsh interface ip set address name="Ethernet" static 192.168.254.3 2255.255.255.0 192.168.254.2

Troubleshoot: if it is doesn't connect, try restart the router power.

You can now unplug the Cable and connect to
Wireless SSID old router to: PRINCE1
passw: ninja007




