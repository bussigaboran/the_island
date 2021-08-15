# the_island
ASCII-based adventure game.

## Gameplay
Run the game:
```
[the_island py](./the_island.py)
```

Screenshot of our hero(es) waking amidst the dense woods, slowly approaching
the mountains in the north. What dwells there?
```
--------------------------------------------------------------------------------
|                                                                              |
|                                .....           ......                        |
|                               ......      ...............                    |
|                              ......      .................           .....   |
|                    .........................###########......................|
|             ..................###..........##############...........####.....|
|         .............########################################################|
|    .............#############################################################|
|   ..........#################################################################|
|   ........#####################^^^^^^^#######################################|
|   .......##################^^^^^^^^^^^^^#####################################|
|    .....###############^^^^^^^^^^^^##^^^^####################################|
|     ...#############^^^^^^^^^^^########^^^^^^^^^#############################|
|      .############^^^^^^^^^##########@###^^^^^^^^^^^^^#######################|
|      ..########^^^^^^#####################^^^^^^^^^^^^^^^####################|
|     ..########^^^^^##########################################################|
|    ...#######################################################################|
|    ..########################################################################|
|   ..#########################################################################|
|    ...#######################################################################|
|    ......####################################################################|
|~ ~......#####################################################################|
--------------------------------------------------------------------------------
```

## Game description
The game is heavily inspired by rogue and the CBM64 version of Phantasie II.
The player reqruits a band of adventures and goes of adventuring on an island.

### Details
- Turn-based game style
- hjkl for navigation
- Fixed ASCII map for the Island, random generated dungeons/ruins/dimensions
- Stationary as well as moving monsters
- Conecpt of ambush
- No colors, field of view or concept of food or ageing


### What is Implemented
- [X] Basic game objects (tiles, monsters etc)
- [X] Create and display simple map
- [X] Make party move around
- [ ] Character generation
- [ ] Hook up and equip party of adventures
- [ ] Monster generation and random placement
- [ ] Fight system
- [ ] ...with spells

### Personal goals
This is an attempt to learn programming beyond simple shell scripts
Areas I aim to dig into:
- [X] Python logging
- [X] Static code analysis
- [ ] Unit tests
-  Refactoring
-  Avoiding broken windows
- [ ] DRY
- [ ] Decouple code
