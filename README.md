# BeatBot

BeatBot est un bot musical pour Discord

## Installation

```py
- pip3 install -U discord.py pynacl youtube-dl python-dotenv
- Editer le fichier .env avec vos infos (app token / guild id) 
- Installer FFMPEG et l'ajouter aux variables d’environnement
- python3 ./bot.py
```

## Utilisation 

```md- 
- help 
!help
Affiche l'aide

- !connard
Invoque le Bot (peu se conduire comme un con)

- !whois
Affiche les infos utilisateur
Prend le pseudo en parametre pour afficher 
les infos d'un autre membre.

[ex: !whois @pseudo ]

- !hello
Salutations + liste des membres du serveur
```
#### COMMANDES MULTIMEDIA

```md-
- Play
!play (YT/BC/SC) URL // strings (ou !p)

- Pause
!pause (ou !pa

- Reprendre
!resume (ou !res)

- Suivant
!next (ou !n)

- Stop
!stop

- Monter/Baisser le volume
!volume int [0-100] (ou !vol)

- Looper la lecture
!loop

- Demander la lecture en cours
!now (ou !nw)

- Montrer le contenu de la playlist
!list (ou !ls)

- Supprimer une track après un !list
!remove int [track  index] (!rm int)

-Supprimer le dernier morceaux ajouté à la liste
!removelast 
```

## Contribution
Les requêtes Pull sont les bienvenues.
Pour les changements majeurs, veuillez d'abord ouvrir un ticket pour discuter de ce que vous souhaitez modifier..

Veuillez vous assurer de mettre à jour les tests.

## License
CC-BY-SA


### TODO : 
```md-
- Faire en sorte qu'on ne soit pas obligé d'être dans un canal vocale pour lancer les commandes multimedia

- Refactorisation (partitionner en cogs)

- Debugger l'option LOOP (soucis de volume)

- Mettre à jour la doc

- Bouton replay (reaction ?)

- Corriger l'heure de décallage du timestamp YT
 
- Les playlists YT font planter le bot

- Bug trigg ciao bande de naze

```
