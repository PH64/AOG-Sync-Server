# AOG-Sync-Server
Installation of Syncthing on Raspberry for use with AOG


Syncthing est une application open source de synchronisation de fichiers disponible pour Windows, Mac, Linux, Android... Aucun compte ni enregistrement préalable à l'utilisation auprès d'un tiers n'est nécessaire, ni même optionnelle. La sécurité et l'intégrité des données sont intégrées dans la conception du logiciel. 
Le principe est de synchroniser des fichiers d’une machine à une autre sans passer par un service d’hébergement. Pour que cette synchronisation puisse se faire, il faut que les 2 machines soient en marche.

![image](https://github.com/PH64/AOG-Sync-Server/blob/b43ced467cb1ac56051254439b47a672c9725b88/ordi.jpg)

Pour une utilisation de plus de 2 machines, il peut être intéressant d’utiliser un serveur, qui sera toujours en fonctionnement, chaque machine communicant avec ce serveur.

![image](https://github.com/PH64/AOG-Sync-Server/blob/b43ced467cb1ac56051254439b47a672c9725b88/serveur.jpg)

Dans le cas de l’utilisation d’AgOpenGPS, la quantité de données étant peu importante, une solution simple et économique est d’installer Syncthing sur un Raspberry Pi.

Cette solution permet la synchronisation des parcelles entre tracteur mais n’est en aucun cas une solution pour la sauvegarde de données.
