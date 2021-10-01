# TD-3-Monnaie-Numerique

## Installing dependencies

Nous avons supposé que nous aurions besoin de Javascript pour la suite du TD, donc d'entrée de jeu nous avons décidé d'installer node.js et npm via les commande :
* `sudo apt install nodejs`
* `sudo apt install npm`

![version node et npm](https://user-images.githubusercontent.com/62909821/135616740-6606814c-a453-47ee-810e-2b1927c096a7.PNG)


Avant de télécharger geth via PPAs il était recomandé de lancer la commande : `sudo apt-get install software-properties-common`. Ce logiciel fournit une abstraction des référentiels apt utilisés.

## Installing Geth 

Pour l'installation de Geth nous avons suivi le tutoriel suivant : https://developernote.com/2020/11/a-proper-ubuntu-18-04-installation-for-running-ethereum-node/ .
Ansi nous avons lancé le script suivant :

```shell
sudo add-apt-repository -y ppa:ethereum/ethereum
sudo apt-get update
sudo apt-get install ethereum
```

Finalement nous avons pu vérifier que l'intallation s'était bien déroulée avec la commande `geth -h` qui nous a renvoyé :

![geth version](https://user-images.githubusercontent.com/62909821/135616717-c7e50aff-9ec2-4cb2-8be8-a8c562a345a2.PNG)

## Running Geth on the rinkeby network

Pour lancer Geth sur le réseau nous avons seulement lancé la commande : `geth --rinkeby`.
Cette commande utilise le mode de synchronisation "Snap" qui est le mode de synchronisation par défaut.

![sync mode](https://user-images.githubusercontent.com/62909821/135617574-fe56b0ae-4806-42e5-a477-1b8c5d67d6ce.PNG)


## Turning Geth into a service 

## Open the RPC API to interact with your node (2 pts)

## Connect to the Geth console and extract last block number (2 pts)

## Connect to the Geth console and show events data from a specific transaction (2 pts)

## Configure truffle to deploy a smart contract through your node (2 pts)

## Ressources

* https://geth.ethereum.org/docs/install-and-build/installing-geth#install-on-ubuntu-via-ppas
* https://priyalwalpita.medium.com/setting-up-the-go-ethereum-geth-environment-in-ubuntu-linux-67c09706b42
* https://priyalwalpita.medium.com/setting-up-the-go-ethereum-geth-environment-in-ubuntu-linux-67c09706b42

