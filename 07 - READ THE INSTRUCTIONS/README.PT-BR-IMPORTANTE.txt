##ATENÇÃO##

••• A VM EVE-NG ESTÁ CONFIGURADA COM UM ENDEREÇO ​​IP ESTÁTICO •••
••• MUDE PARA SUA LAN DOMÉSTIVA PARA OBTER ACESSO À WEB GUI •••

• A PARTIR DO EVE-NG CONSOLE, SIGA ESTES PASSOS. •

• Alterando manualmente o pnet0
• Você pode editar o arquivo de rede diretamente usando NANO.

nano /etc/network/interfaces

• A seção de gerenciamento deve ter a seguinte aparência:

iface eth0 inet manual

auto pnet0
iface pnet0 inet static

address 192.168.1.254
netmask 255.255.255.0
gateway 192.168.1.1
dns-nameservers 8.8.8.8 1.1.1.1
bridge_ports eth0

bridge_stp off

• SUBSTITUA

192.168.1.100 = IP desejado do EVE-NG
255.255.255.0 = máscara de rede
192.168.1.1 = gateway local

• FINALMENTE

Ctrl+O (salvar)
Enter (confirmar)
Ctrl+X (sair)

•••••••• CREDENCIAIS (INCLUINDO TODOS OS DISPOSITIVOS) ••••••••

USUÁRIO: admin
SENHA: Evelab@2025

## SHELL/CONSOLE EVE ##

USUÁRIO: root
SENHA: Evelab@2025