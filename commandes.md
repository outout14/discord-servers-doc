# Commandes disponibles sur le serveur
*Plein* de commandes sont disponibles dans le chat en plus des commandes définies par Discord.
Dans ce fichier, je ferai le tour des commandes avec un petit descriptif.

- [Matbot](#matbot)
    - [Niveaux](#niveaux)
    - [Recherche](#recherche)
- [Aethex](#aethex)
    - [Musique](#musique)
- [TypicalBot](#typicalbot)
    - [Images](#images)

## Matbot
- `!blagueperroquet`: une petite blague de ouf.
- `!hitboxmoney`: Lien vers la chaine hitbox de Matbob pour pouvoir faire une donation
- `!youtubemoney`: Lien vers la page Tipeee de Matbob pour pouvoir faire un don
- `!niveaux`: Voir les grades possible ainsi que le niveau requis pour l'avoir. Plus d'information sur le système de niveaux [icitte](niveaux.md).

### Niveaux
Les commandes définies par le bot
- `!rank`: Affiche votre rang actuel
- `!levels`: Envoie un lien pour voir la leaderboard.

Aperçu de la leaderboard

## Recherche
- `!youtube <lien | termes à rechercher>`: Affiche la vidéo correspondante (quand le bot veut bien marcher :P )
- `!imgur <recherche>`: Affiche l'image correspondant aux termes de la recherche.

## Aethex
Le bot qui m'éclate dans les mains au mauvais moment ^^'

:x: Ce bot repose sur un système de *shards* (ensemble de serveurs). Concrètement, si le bot est affiché "en ligne" mais que la commande ne fonctionen pas, c'est certainement une *shard* qui est cassée.

- `-help`: Est supposé afficher l'aide

### Musique
:construction: Les commandes qui vont suivre sont encore en paufinement ou de résolution de bugs à l'heure de l'écriture.

- `-play <recherche | url>` `-stream`: Lit une musique dans le channel vocal désigné par un administrateur
- `-skip`: Passe la musique en cours de lecture
- `-stop`: Arrête la musique en cours et vide la file d'attente
- `-pause`: Une petite pause café ? :coffee:
- `-resume`: Reprendre là ou c'était arrêté
- `-queue [page]`: Voir la file d'attente
- `-volume [volume]`: Ajuster le volume. Par défaut, la valeur est de **50/100**. Si aucun volume est fourni, l'actuel sera affiché

Il y a évidemment beaucoup de commandes pour ce bot. Pour en savoir plus, allez donc [voir la doc](https://aethex.xyz/documentation/reference/commands).

## TypicalBot
Certaines commandes ont des alias. Elles sont affichées l'une à côté de l'autre si c'est le cas
- `$ping`: Pong
- `$help`: Affiche un petit message dans vos MP
- `$commands` `$cmds`: Affiche la liste des commandes. Y'a une ribambelle
- `$shoot`: Tirer sur quelqu'un
- `$stab`: Planter un couteau dans quelqu'un

### Images
Cette section regroupe les commandes qui renvoient des images d'animaux trop mignons ou wtf.

- `$cat` `$kitty` `$kitten`: Une image de chat
![Une image de chat][cat]

- `$dog` `$puppy` `$doggy`: Une image de chien
![Une image de chien][dog]

- `$bunny`: Une image de lapin
![Une image de l4p1n][bunny]

- `$penguin`: Les pingouins
![Pingu][Pingu]

- `$pug`: Un bulldog
![Un bulldog][pug]

- `$tiger`: Rwwwwaaaaaaaarrr !
![Un tigre de l'espace][tiger]

### Musique
C'est le même principe que le système de musique d'Aethex. [#flemme :stuck_out_tongue_closed_eyes:]

[leaderboard]: images/leaderboard.png
[cat]: http://random.cat/i/dgzxtZj.jpg
[dog]: https://cdn.discordapp.com/attachments/212992219261435904/221722598701006859/doggie.jpg
[bunny]: https://media.bunnies.io/poster/132.png
[Pingu]: http://penguin.wtf/images/4.png
[pug]: http://28.media.tumblr.com/tumblr_lj66zmgKEN1qcd23mo1_500.png
[tiger]: https://api.typicalbot.com/tiger/images/tiger8.png
