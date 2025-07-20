### Admin
Router>enable or en

### Config
Router#config t

### Change name
Router(config)#hostname R0

### Unnecessary command
R0(config)#no ip domain-lookup

### Set pass
R0(config)#enable secret password

### Del pass
R0(config)#no enable secret

### Go to Interface
R0(config)#interface fa0/0

### Set IP
R0(config-if)#ip address 192.168.10.1 255.255.255.0

### Up link
R0(config-if)#no shutdown

### Save command of router
R0#copy running-config startup-config

### IP Route
R0(config)#ip route {net address which is not neighbour, in which network it wants to go, that net address ends with .0} {that network mask address} {gateway}

### Show Ip Route
R0#show ip route









