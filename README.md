ARP(Address Resolution Protocol) was a protocol that I worked with during my internship.

This code creates simple ARP package and then broadcasts it to get the MAC address of the device whose IP address is known. This is ARP Request. Finally it captures the ARP Reply package and gets the MAC address.

After you compile it, you should run it as root. It needs permissions. While you running it, you should give 2 parameters: interface_name and target_ip. Otherwise it returns -1.
