# Versionamento da atividade Linux  

## 📌 Versão 1.0
``` 
A instalação do Oracle Linux 8.6 está concluída. O usuário root foi logado.
``` 

> Snapshot File: {e5bd9d5d-5f5c-42ca-bfae-2ec33de45d8a}.vhd

## 📌 Versão 2.0
``` 
VM VLAN configurada em modo BRIGDE. Foram realizados os ajustes necessários.
``` 
> Alterações nos arquivos:
* /etc/sysconfig/network-scripts/ifcfg-enp0s3 
* /etc/resolv.conf

``` 
Um IP estático foi configurado para a rede, IP: 192.168.0.115
```   
> O arquivo /etc/sysconfig/network-scripts/ifcfg-enp0s3 foi alterado. Mudando do modo DHCP para estático.  
```
Adicionando IP estático: 192.168.0.115, máscara de rede: 255.255.255.0 e gateway: 192.168.0.1
```
> O arquivo /etc/resolv.conf foi alterado. Adicionando Google DNS: 8.8.8.8 e 8.8.4.4

> Snapshot File: {c16a8951-a953-4ce4-9bce-12d45735a9d0}.vhd

### 📌 Versão 2.1
``` 
Máquina virtual atualizada. Instalação e atualização de pacotes.
``` 
> Snapshot File: {4de35b40-d10d-4481-8fea-80e1b968189d}.vhd

## 📌 Versão 3.0
``` 
Relação de confiança entre VMs estabelecida.
``` 
> Alterações no diretório /root/.ssh  
> Arquivo "authorized_keys" criado em ambas as máquinas para armazenar as chaves.

> Snapshot Files: 

* VM1 (Oracle Linux 1) :{9d330f06-d8ae-4966-97ea-4398f3ca850a}.vhd  IP: 192.168.0.200

* VM2 (Oracle-Linux) : {397536df-3c06-4298-a0c4-c2f711dd6182}.vhd   IP:192.168.0.115

### 📌 Versão 3.1
```
Correções de bugs. Compartilhamento de arquivos via servidor samba.
```
> Alterações no diretório /etc/samba. O arquivo smb.conf foi alterado.

> Snapshot Files:  

* VM1 (Oracle Linux 1) : {51fac9a7-1e78-4cfd-abb6-d7481010d502}.vhd    IP: 192.168.0.200

* VM2 (Oracle-Linux) : {0dc8ded3-0432-475d-94fa-a2c3241de37b}.vhd   IP:192.168.0.115

### 📌 Versão 3.2
```
Atualizações e correções de bugs.
```
```
Relação de confiança entre máquinas reconstruídas.
```
> Alterações no diretório /root/.ssh. Arquivo "authorized_keys" criado em ambas as máquinas para armazenar as chaves.  

> Snapshot Files:  

* VM1 (Oracle Linux 1) : {8f49992b-39e8-49b1-a427-4b284e1fec73}.vhd    IP: 192.168.0.200  
* VM2 (Oracle-Linux) : {0fb75d1b-b455-4798-82cb-1d695bbd30fa}.vhd      IP:192.168.0.115


## 💻 Ambiente de realização da atividade
```
Oracle Linux 8.6.0
```
