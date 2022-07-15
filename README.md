# rpi
## IP Estática

Se debe modificar el archivo /etc/dhcpcd.conf

´´´
#interface eth0
#inform 192.168.1.103
#static routers=192.168.1.1
#static domain_name_servers=200.28.4.129 200.28.4.130

interface eth0
static ip_address=192.168.1.103/24
static routers=192.168.1.1
static domain_name_servers=200.28.4.129 200.28.4.130
´´´
