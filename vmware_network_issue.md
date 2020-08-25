I was facing an issue with internet connectivity in my kali linux vm. Upon using ifconfig  I realized that there was no eth0 interface.
If so, do the following

Add the following lines in <b>/etc/network/interfaces/</b>

<i>auto eth0 <br>
allow-hotplug eth0 <br>
iface eth0 inet dhcp </i>
