nano /etc/network/interfaces

auto gre30
  
  iface gre30 inet tunnel
  
  address 10.10.10.1
  
  netmask 255.255.255.252
  
  mode gre
  
  local 198.51.100.1
  
  endpoint 203.0.113.1
  
  ttl 255
