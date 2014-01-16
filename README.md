bcp38 compliance via ipset for ipv6 and ipv4

Blocking address ranges can get painful with iptables. The 
ipset tool in linux makes it easy.

this will be a script intended to enable bcp38 filtering on a border
gateway router, suitable for hooking into the firewall code at the
right point, somewhere.

