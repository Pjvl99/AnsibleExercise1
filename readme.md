# Vagrant

## Instrucciones para correr el ejercicio

- Descargar e instalar hipervisor
  - [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
  
- Descargar e instalar Vagrant
  - [Vagrant](https://www.vagrantup.com/downloads)

- Instalar plugin de hipervisor
  - vagrant plugin install vagrant-[PROVIDER]

- Reemplazar _PROVIDER_ por:
  - VirtualBox -> vbguest
  - VMWare fusion -> vmware-desktop

### Indicaciones para el ejercicio1-shell

- Correr los siguientes comandos dentro del directorio de ejercicio1-shell: 
  - "vagrant up"
  - "vagrant ssh"

- Una vez dentro de la máquina virtual correr el siguiente comando:
  - "cd app && node app.js"
  
### Indicaciones para el ejercicio1-ansible

- Tener instalado ansible:
  - "pip install ansible" (Windows/Mac)
  - "sudo apt install ansible" (Linux)

- Correr los siguientes comandos dentro del directorio de ejercicio1-ansible: 
  - "vagrant up"
  - "vagrant ssh"

- Una vez dentro de la máquina virtual correr el siguiente comando:
  - "cd app && node app.js"


### Extra

- Recomendable usar la vm.box llamada "ubuntu/focal64"
