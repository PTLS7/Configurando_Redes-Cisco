# Simulando_Redes-Cisco

Simulando a Rede de uma Empresa -  Programa: Cisco Packet Tracer


Divindindo em 4 Departamentos:
 1- Administração (ADM)
 2- TI (TI)
 3- Comercial (CM)
 4 - Produção (PD)

Utilizando  18 Computadores(Separados entre os departamentos) e 2 Switchs de 24 portas: FastEthernet e 2 portas: GigabitEthernet

Configuração da Rede nos Computadores:
 10.20.20.0/24 - segmentado 4 vezes(/26)
 SubMask: 255.255.255.192

Switch Configuração:
  Criado 4 VLANS no dois Switchs para Conecção, sendo elas:
     5 - ADM
     6 - TI
     7 - CM
     8 - PD
  Na Porta GigabitEthernet 0/1 dos Switchs que conectam entre si, foram configuradas no formato Trunks - Permitindo a conexão  das VLAN 5, 6, 7, 8
  
  


