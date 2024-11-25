# HitmanGO_like
## Classes
**BP_Player** :
Represents the player pawn.

**BP_PlayerController** :
Handles the player's movement logic and partially serves as the GameManager alongside BP_LevelGameMode.

**BP_LevelGameMode** :
Works in conjunction with BP_PlayerController to manage overall game logic.

**BP_Node** :
Represents a node or point on the grid.

**BP_Nazgul** :
An AI that chases the player as soon as invisibility is activated.

**BP_Orc** :
An AI that pursues the player when they enter its field of vision.

**BP_Ring** :
A collectible that activates invisibility, making the player undetectable by Orcs.

**BP_Wall** :
A wall that blocks the Orcs' vision and restricts player movement.

## Testing the Prototype
- Test Map : Located at Content\HitmanGO_like\Maps\Dev\Level1.

- Controls : To move the character, click on a node with the mouse.
