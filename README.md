# Xbird.me Fichier de config Serveur Match CSGO


Ceci est un ensemble de fichiers de configuration utilisé sur mes serveurs

il est edité à partir du fichier :


les modifications apportées sont des modifications adaptée au style de match effectué sur mes serveurs

## Informations

Le fichier "esl5on5.cfg" est le fichier 
>"Electronic Sports League CS:GO 3on3/5on5 Ladder Config 14.01.2016"
https://play.eslgaming.com/download/26251762/

avec les valeurs de temps de round :
>round time : 1:55 // bomb timer 0:40

conformement au changement annoncé sur le site ESL :
https://play.eslgaming.com/counterstrike/csgo/news/262509/

## Installation

Pour utiliser ce fichier dans les meilleures conditions, vous devez avoir un serveur avec le mode de jeu compétitif officiel :

> +game_type 0 +game_mode 1

Vous devez ensuite créer le fichier :

> csgo/cfg/gamemode_competitive_server.cfg

et y mettre le contenu suivant :

> exec xbirdme-csgo-cfgservermatch.cfg

(Vous pouvez également utiliser celui fourni ici si vous ne voulez pas le créer à la main)


Une fois le serveur relancé, vous devriez voir apparaitre les messages suivant dans la console :

> \>  ESL CS:GO 3on3/5on5 Ladder Config loaded - 14.01.2016<

> \> Xbird.me loaded. HAVE FUN ! <