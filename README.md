# $\color{#D4101D}{VIRTUALISATION - port forwarding}$
Cet article montre une façon d'accéder à une page web d'une machine virtuelle (sur laquelle j'installe le serveur nginx), un accès depuis le navigateur du host (et non de la machine virtuelle même).

<img src="https://raw.githubusercontent.com/abiForSofteam/virtualisation/main/img1.png">

## Installation du serveur web nginx sur la machine virtuelle
En ligne de commande, l'installation du serveur web nginx se fait de la façon suivante:  

**sudo apt-get install nginx -y**

<img src="https://raw.githubusercontent.com/abiForSofteam/virtualisation/main/nginx_install.png">


## Vérification de l'état du serveur
La Vérification de l'état du serveur se fait par la commande suivante:  

**service nginx status**

<img src="https://raw.githubusercontent.com/abiForSofteam/virtualisation/main/nginx_status.png">

<img src="https://raw.githubusercontent.com/abiForSofteam/virtualisation/master/img2.png">
<img src="https://raw.githubusercontent.com/abiForSofteam/virtualisation/master/img3.png">
