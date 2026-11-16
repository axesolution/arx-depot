# ARX : dépôt pacman `[arx]`

Paquets du système personnel **ARX** (basé sur Arch Linux), publiés sous forme de
*releases* GitHub, un canal par release :

| Canal | Release | Pour |
|---|---|---|
| `test` | [`test`](../../releases/tag/test) | machines virtuelles : les nouveautés arrivent ici d'abord |
| `stable` | [`stable`](../../releases/tag/stable) | PC : les mêmes fichiers, promus une fois validés sur `test` |

Les paquets et la base sont **signés** (OpenPGP). pacman exige les signatures :

```ini
[arx]
SigLevel = Required DatabaseRequired
Server = https://github.com/axesolution/arx-depot/releases/download/stable
```

Empreinte de la clé de signature en service :
`627D 6307 ACE0 2E79 B3DF  1C86 A0EF 704B BBBC F2FA`
(clé de développement, remplacée avant la version finale ; le paquet
`arx-keyring` porte la clé en service).

Ce dépôt ne contient que les paquets publiés : le code source d'ARX n'y est pas
développé. Usage personnel.
