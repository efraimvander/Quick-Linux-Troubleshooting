# Network Troubleshooting


## Verificar conectividade
ping -c 4 8.8.8.8

ping -c 4 google.com


## Ver rotas
ip route


## Ver estado das interfaces
ip -c a
ethtool eth0


## Resolver DNS
resolvectl status
nslookup google.com


## Ver conexões abertas
ss -tulpn


## Testar portas
nc -vz IP PORT
