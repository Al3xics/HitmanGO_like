# HitmanGO_like

## Classes

**BP_Player** :
Contient le pion joueur.

**BP_PlayerController** :
Contient la logique de déplacement du joueur, mais aussi sert de GameManager.

**BP_Node** : Une node.

**BP_Nazgul** : Une IA qui va chase le joueur dès que celui-ci aura activé l'anneau.

**BP_Orc** : Une IA qui poursuivra le joueur dès que celui-ci entrera dans son champs de vision et si l'anneau n'est pas activé.

**BP_Ring** : Un collectible qui permettra d'activer l'anneau.

**BP_Wall** : Un mur qui bloquera la vision des Orcs et les mouvements des joueurs.

## Tester le prototype

- La carte de test se trouve dans :
Content\HitmanGO_like\Maps\Dev\Level1.

- Contrôles :
Pour déplacer le personnage, cliquez sur une node avec la souris.
