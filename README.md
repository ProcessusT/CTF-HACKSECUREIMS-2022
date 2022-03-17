# CTF-HACKSECUREIMS-2022
Les challenges que j'ai fais pour le CTF de la HackSécuReims 2022


La vidéo de résolution des challenges est dispo sur ma chaine Youtube :
https://youtu.be/Hl4wKvphOH0


-------------------------------------------------------------------------------------


Le premier challenge magic.2022.7z est un conteneur docker d'une machine boot2root dans l'univers d'Harry Potter
Pour l'installation :

7z x ./magic.2022.tar.7z

docker import ./magic.2022.tar

docker run --name magic -h magic -p 0.0.0.0:8080:80 -p 0.0.0.0:2222:22 -p 0.0.0.0:22222:2222 -d magic /bin/sh /root/start.sh


-------------------------------------------------------------------------------------


Le second challenge physmem.7z est un dump de mémoire dans lequel on doit retrouver un processus en cours d'exécution


-------------------------------------------------------------------------------------


Le troisième challenge AppData.zip est un extrait du répertoire AppData d'un utilisateur dont le mot de passe de session est "iambatman".
