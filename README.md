# Group 106
## member: Victor Cheung(3035685902); Wang Qi(3035638818)

**Game description:

This game is a explorational maze game.

**Functions:

The game will generate a map using the seed values given by the player, the map will be represented using a 2-D or 3-D array or vector (suspended), random demons and token chests should be generated *inside* the map, players will go in from the entry and start exploring.

**Features:

*Chest:* They move spratically each time the player takes a move, there are other chests that may or may not contain weapons/magic potion that can make the moster go slower, but when the a chest appear within the 15 blocks around the player, it will become static automatically.

*Demons:* There are two types of them, one of which is faster than your movement and the other is slower, they both will begin to persue the player when agitated.

Both demons and chests will require a possibility game(RPS game), to conquer by weapon, but when administered with potion, demons can be conquered without one, user commands should be specified here.

**Movements: 

Movements are controlled using w, a, s, d, and then enter, the heading direction will be automatically adjusted when a or d is pressed.

By default, the player can only go one block each turn, slow demon will go one block per two turns, fast demons will go two blocks per turn, fast demons will be reduced to slow demons when administered with potion.

After pressing enter, the periphery (3X3 grid) where the player is located will be displayed below in text-based format.

Caveats of demons and chests within the 4x4 grid will also be shown.

**Data structures:

The player will be stored using a struct or class.

**Dynamic memory management:

**File input/output (e.g., for loading/saving game status):

When a game is halfway terminated, the map will be stored with a map datatype.

**Program codes in multiple files:

Will include many headers for functions.
