## Rapport d'Activités réalisés durant la période de stage au sein de Safe Digital Consulting

- Dépannage pour la société Bus Bastiais, suite à la coupure intermittente de la box internet. Nous avons détecté un défaut électrique sur la ligne ADSL et avons signalé cela à Orange, qui est intervenu dans la journée.

- Nous avons été contactés par pilotagehautecorse.com suite à une panne des boîtes mail. Nous avons remarqué que les enregistrements MX (pointage dans un annuaire vers l'adresse du serveur de mail) n'étaient plus valides et qu'il fallait les modifier. Cependant, la société détenant les propriétés du nom de domaine n'existe plus, et la personne à qui appartient le nom de domaine est introuvable. Nous avons donc fait de l'OSINT (recherche sur internet) pour le retrouver et l'avons contacté afin de modifier les enregistrements MX et de faire un transfert de propriété.

- Panne de neuf caméras dans un hôtel au Cap. Il y a un manque de balisage et de documentation. Une journée doit être réservée pour tester et tracer chaque câble de l'hôtel ; nous ne l'avons pas encore fait.

- Diagnostic d'un problème de connexion dans un camping à un camping. Après vérification du câble Ethernet tout indiquait qu'il était rompu (Aucune continuité). Nous l'avons donc tiré et avons remarqué qu'il avait été mangé par un rongeur. Nous avons donc décidé de tenter de le remplacer, sans succès suite à un blocage au niveau de la gaine. Une nouvelle gaine devra donc être nécessaire pour faire passer le câble.

- Création d'une boîte mail d'archivage Exchange pour y mettre tous les mails de plus de 2 190 jours sur une boîte mail utilisée par une entreprise.

- Audit du Wi-Fi à un hôtel à Calvi, quatre étages plus le rez-de-chaussée avec trois AP par ailes, nous devrons donc installer (idéalement) + de 100 AP (point d'accès Wi-Fi).

- Création d'un laboratoire avec des AP et un routeur Ruijie pour tester sa viabilité en monde professionnel. 

- Serveur très lent, nous avons donc testé et vérifié l'observateur d'événements. Nous avons remarqué que la lenteur venait du contrôleur HPE suite à une batterie hors d'usage, vidant donc le cache à chaque redémarrage et le rendant inopérant (le cache, qui rend la lecture et l'écriture plus rapide). Étant donné que le serveur est très vieux et que certains services ne seront plus utilisés sur ce serveur, nous avons décidé de proposer un micro PC à l'entreprise, en attendant l'acceptation du devis. 

- 3CX étaient en panne après vérification et prise à distance du serveur Windows 2012R2 gérant la VM (machine virtuelle) 3CX, nous avons remarqué que la VM était éteinte ; nous l'avons donc redémarrée (et paramétré le démarrage automatique au démarrage de Windows server 2012R2), fait un nouvel essai, et cela ne marchait toujours pas. Nous avons donc remarqué que l'interface Ethernet physique liée à la machine virtuelle était déconnectée ; nous l'avons donc reconnectée, et le service téléphonique a redémarré au bout de vingt minutes. 

- Multipleses pannes sur des ordinateurs qui étaient très bruyants et lents ; il suffisait simplement de les souffler.

- Configuration d'un boîtier d'appel VoIP (technologie de téléphonie sur réseau IP) d'ascenseur avec Yeastar comme provisionneur. Nous avons aussi regardé comment configurer des envois d'appel rapide en appuyant sur un simple bouton (nécessite d'aller sur l'interface web du boitier). 

- Montage d'un ordinateur permettant le clonage des disques durs rapidement pour les ordinateurs clients. Nous avons donc utilisé un boîtier totalement ouvert, dit Benchmark (les composant comme la carte mère, le processeur, la mémoire RAM, et le disque avec un système d'exploitation avaient déjà été montés et configurés).

- Réinitialisation du mot de passe à distance d'un Chromecast. La personne devant recevoir un SMS en chat RCS de Google n'était pas connectée à Internet. Nous l'avons remarqué en lui envoyant un chat RCS et celui-ci a échoué, tandis que le SMS a bien été reçu suite à une réponse de sa part. Nous lui avons donc indiqué de se connecter au Wi-Fi. Suite à la connexion Wi-Fi de cette personne, elle a reçu le code, nous l'as communiqué, nous avons initialisé le mot de passe, et nous le lui avons partagé de manière sécurisée avec Bitwarden.

- Nous avons assisté à un webinaire Ruijie montrant l'aisance avec laquelle il était possible de configurer tout un reseau d'entreprise (mise en place d'un routeur, de commutateurs, de VLAN, de NAT/PAT...).

- Mise en place rapide d'un serveur OpenVPN avec un routeur Unifi au bureau et NAT sur une box Orange (Création du serveur, et de l'utilisateur).

- Mise en place d'un VPN Tailscale sur un serveur en affichant le sous-réseau, et sur le client en se connectant simplement au compte. Aucune autre configuration n'est nécessaire avec Tailscale.

- Commande d'une ligne fibre 1 gigabit par seconde symétrique chez le fournisseur Destiny en tant qu'opérateur pour un client.

- Impossible de prendre la main sur un serveur à. Le serveur était en cours d'arrêt mais avait planté. Usage de Claude en PowerShell pour débloquer la situation.

- Conflit d'IP dans un réseau d'experts comptables empêchant la prise à distance de leur serveur. Il y avait un conflit d'IP suite à l'installation d'un nouveau routeur chez eux.

- Le remplacement d'un Fortinet par un Router Unify, afin d'avoir la console en ligne, un paramétrage plus avancé et plus simple, ainsi que de meilleures performances.

- Diagnostic d'une panne mail : le Fortinet, étant mis au rebut, disposait d'un relais SMTP, empêchant donc la société de recevoir des mails tant qu'il n'y a pas de correction sur l'enregistrement MX de leur domaine.

- Un ordinateur portable avait une erreur de BIOS. Nous avons donc désactivé puis réactivé le Secure Boot et mis à jour les drivers de la carte-mère après redémarrage de celui-ci. BitLocker nous a demandé une clé dont nous n'avons pas accès. Nous avons donc tenté, en un premier temps, de déchiffrer l'ordinateur sans cette clé avec Kali Linux, ce qui a bien sûr échoué. Après recherche avec le client pendant plusieurs heures, nous avons trouvé le compte Microsoft qui disposait de la clé BitLocker pour cet ordinateur.

- Dépannage d'un utilisateur sur macOS. Il ne trouvait plus le dossier Téléchargements. Nous avons ouvert Finder pour l'aider à retrouver le dossier (celui-ci devait être développé).

- Mise à jour vers la version 12 du logiciel métier de Negroni Voyages pour leurs postes informatiques. L'agent IA Claude a pu faire 6 postes en journée, durant la pause de midi à 14h, et s'occupera de 12 autres postes à partir de 18h via un cron.

- Recherche et devis pour une mairie d'un projecteur à moins de 300 € hors taxe, avec capacité de projeter sans fil en HD (720p minimum).

- Installation d'un photocopieur professionnel et de deux pieds pour écran dans un bureau d'avocat.

- Mise en place d'un VPN avec OpenVPN et un routeur Unify et configuration du client VPN sur deux postes clients (Création du serveur, des utilisateurs et configurations de postes clients).

- Création compte exchange via OVH sunrise pour qu'un nouveau salarié puisse avoir sa propre adresse email.

- Installation starlink mini pour Marie de nuceta en remplacement d'une box 4G (et en attente de l'arrivée de la fibre).

- Diagnostic et remise en service d'un téléphone yeahlink du a prise RJ45 défaillante (nous avons branché l'antenne directement dans la baie réseau, son antenne lui permet de capter sur une très longue distance).

- Remplacement de 2 AP dans un hôtel : les AP ne sont pas remontés toute seule, malgré le fait que ce soit des Unifi. Nous avons donc dû installer en plus un switch Unifi pour remplacer deux autres switch 8 ports et ainsi avoir du PoE+ (budget PoE proche de la limite de 45W mais correct).

- Configuration à distance d'une AP dans un hôtel en Balagne afin de créer un Wi-Fi (évènement).

- Mise en place d'une tablette connectée en Bluetooth au système de haut-parleurs d'un hôtel, afin d'empêcher les coupures lors de la lecture de la musique (anciennement fait avec un PC de la réception, trop loin). 

- Mise en place avec Yealink de l'application pour smartphones, afin de permettre de reçevoir et émettre des appels depuis un téléphone fixe et mobile (configuration pour l'utilisateur d'être autorisé à avoir 2 téléphones).

- Diagnostic et résolution d'une panne, suite à la disparition mystérieuse de mails : tous les mails disparus (selon l'utilisateur), avaient en réalité été déplacés automatiquement dans la boîte d'archivage, car ils avaient plus de 6 mois. Nous lui avons indiqué où ils se trouvaient. 

- Achat et configuration d'une licence Office 365 pour un nouvel utilisateur afin qu'il est une adresse email.

- Appel d'un utilisateur ne pouvant plus se connecter à sa session de bureau à distance. La raison étant que l'Active Directory était paramétrée pour invalider les mots de passe au bout de six mois. Nous avons désactivé ce paramétrage, modifié le mot de passe de l'utilisateur et lui avons donné ensuite.
