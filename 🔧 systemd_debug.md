
# Systemd Troubleshooting


## Ver status de um serviço
systemctl status servicename


## Ver logs
journalctl -u servicename -xe


## Ver falhas de boot
journalctl -b -1


## Listar serviços falhados
systemctl --failed


## Reiniciar daemon
systemctl daemon-reload
