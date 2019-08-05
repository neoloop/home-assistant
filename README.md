# Home Assistant

Pense pete en français pour installer Home assistant sur un **Proxmox** (machine virtuel)

# Installation  Proxmox
Proxmox Virtual Environment (VE) est une solution de virtualisation libre basée sur l’hyperviseur Linux KVM

## Pour télécharger l’image ISO de Proxmox VE rendez-vous  [ICI](https://www.proxmox.com/en/downloads/category/iso-images-pve)

 - Il faut faire une clé USB bootable :
 - Pour faire une clé USB bootable avec Proxmox, il faut utiliser un logiciel  comme  [Etcher.io](https://etcher.io/)  et avoir une clé USB d’au moins 1Go. Mettre la clef USB sur la machine et démarrer dessus, suivre les instructions.

# Installation de home assistant sur Proxmox

Allez sur le Shell Proxmox.
entrez cette ligne 

    wget -qO - https://raw.githubusercontent.com/whiskerz007/proxmox_hassos_install/master/install.sh | bash -s local-lvm

https://github.com/whiskerz007/proxmox_hassos_install
