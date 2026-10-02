# MBF21 OPTIONS Lump

The OPTIONS lump (originally from mbf) allows wad authors to set a series of variables that affect engine behaviour. This file contains descriptions of the options as well as examples you can use to approximate old environments.

See the templates [here](./templates/). For [Ultimate Doom](./templates/OPTIONS.doomu.txt), [Doom II](./templates/OPTIONS.doomu.txt), [Boom](./templates/OPTIONS.doomu.txt), [MBF](./templates/OPTIONS.doomu.txt) and [MBF21](./templates/OPTIONS.doomu.txt)

| Key                   | Description                                                    | Ultimate Doom | Doom 2 | Boom | MBF | MBF21 |
|-----------------------|----------------------------------------------------------------|---------------|--------|------|-----|-------|
| weapon_recoil         | Firing a weapon pushes the player back                         |             0 |      0 |    0 |   0 |     0 |
| monsters_remember     | Friendly monsters return to old target when losing current one |             0 |      0 |    1 |   1 |     1 |
| monster_infighting    | Monsters infight                                               |             1 |      1 |    1 |   1 |     1 |
| monster_backing       | Ranged monsters will back away from close melee targets        |             0 |      0 |    0 |   0 |     0 |
| monster_avoid_hazards | Monsters avoid hazards such as crushing ceilings               |             0 |      0 |    0 |   1 |     1 |
| monkeys               | Monsters can climb steep stairs                                |             0 |      0 |    0 |   0 |     0 |
| monster_friction      | Monsters are affected by friction modifiers                    |             0 |      0 |    0 |   1 |     1 |
| help_friends          | Friendly monsters prefer targets of friends                    |             0 |      0 |    0 |   0 |     0 |
| player_helpers        | Number of dogs to spawn                                        |             0 |      0 |    0 |   0 |     0 |
| friend_distance       | Friendly monsters try to keep at least this distance apart     |             0 |      0 |    0 | 128 |   128 |
| dog_jumping           | Dogs can jump down from high ledges                            |             0 |      0 |    0 |   1 |     1 |
| comp_telefrag         | Spawners only telefrag on Map 30                               |             1 |      1 |    1 |   0 |     0 |
| comp_dropoff          | Discourage / prevent enemies from walking off ledges (?)       |             1 |      1 |    1 |   1 |     0 |
| comp_vile             | Archviles can create ghosts                                    |             1 |      1 |    0 |   0 |     0 |
| comp_pain             | Pain elementals don't spawn lost souls if there are over 20    |             1 |      1 |    0 |   0 |     0 |
| comp_skull            | Lost souls can spawn past impassable lines                     |             1 |      1 |    0 |   0 |     0 |
| comp_blazing          | Blazing doors have double sounds                               |             1 |      1 |    0 |   0 |     0 |
| comp_doorlight        | Door lighting changes are abrupt                               |             1 |      1 |    0 |   0 |     0 |
| comp_model            | Assorted physics quirks and bugs                               |             1 |      1 |    0 |   0 |     0 |
| comp_god              | God mode is removed in sector 11 & ignored at 1000+ damage     |             1 |      1 |    0 |   0 |     0 |
| comp_falloff          | Don't pull monsters off ledges they are hanging off of         |             1 |      1 |    1 |   0 |     0 |
| comp_floors           | Assorted floor bugs                                            |             1 |      1 |    0 |   0 |     0 |
| comp_skymap           | Don't apply invulnerability palette to skies                   |             1 |      1 |    1 |   0 |     0 |
| comp_pursuit          | Monsters can infight immediately when alerted                  |             1 |      1 |    1 |   0 |     1 |
| comp_doorstuck        | Monsters get stuck in door tracks                              |             1 |      1 |    0 |   0 |     0 |
| comp_staylift         | Monsters don't prefer staying on lifts their target is on      |             1 |      1 |    1 |   0 |     0 |
| comp_zombie           | Dead players can activate things                               |             1 |      1 |    1 |   1 |     1 |
| comp_stairs           | Assorted stair bugs                                            |             1 |      1 |    0 |   0 |     0 |
| comp_infcheat         | ?                                                              |             1 |      1 |    1 |   0 |     0 |
| comp_zerotags         | Allow tag zero actions                                         |             1 |      1 |    0 |   0 |     0 |
| comp_respawn          | Monsters not spawned at level start respawn at the origin      |             1 |      1 |    1 |   1 |     0 |
| comp_soul             | Buggy lost soul bouncing                                       |             1 |      1 |    1 |   1 |     0 |
| comp_ledgeblock       | Monsters are blocked by ledges (except when scrolling)         |             1 |      1 |    0 |   0 |     1 |
| comp_friendlyspawn    | Spawned things inherit the friend attribute from the source    |             1 |      1 |    1 |   1 |     1 |
| comp_voodooscroller   | Voodoo dolls on slow scrollers move too slowly                 |             0 |      0 |    0 |   1 |     0 |
| comp_reservedlineflag | The line flag 0x0800 disables extended flags                   |             1 |      1 |    1 |   1 |     1 |
