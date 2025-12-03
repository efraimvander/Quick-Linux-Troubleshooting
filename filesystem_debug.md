
# Filesystem Troubleshooting


## Espaço em disco
df -h


## Arquivos grandes
find / -type f -size +500M 2>/dev/null


## I/O lento
iotop -oPa


## Inodes
df -i


## Ver erros em disco
dmesg | grep -i error
e2fsck -n /dev/sdX
