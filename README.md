# Speed-linux-Update
Petit code bash pour mettre a jour votre système linux en une seul commande

  Commande utiliser dans le script Red-Hat :
    
    
    
    
    
    - dnf update
    - flatpak update
    - reboot
    - grub2-mkconfig -o /boot/grub2/grub.cfg
    - dnf list kernel
  

  Commande utiliser dans le script Debian(ubuntu,mint,pop os,...)
  
  
  /!\ Je ne peux pas garantir le fonctionnement du script pour debian





    - apt-get update
    - apt-get upgrade
    - flatpak update
    - reboot
    - grub2-mkconfig -o /boot/grub2/grub.cfg



Pour rendre le script executable:





  chmod -x script_Red-Hat.sh 
  chmod -x script_Debian.sh


Executer le script:





  ./script_Red-Hat.sh 
  ./script_Debian.sh  
