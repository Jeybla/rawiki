---
title: Clif authok
permalink: /Clif_authok/
---

Syntax
------

`int `**`clif_authok`**`(struct map_session_data *sd);`

==Parameters==

-   **sd** Pointer to player's information struct.

See [map_session_data](map_session_data) for more information.
==Description== Tells client that a player (sd) is fully loaded and that it can proceed to the map screen.
Provides client with player position and facing direction as well.
==Example== See bool [pc_authok](pc_authok)(...) in pc.c
[Category:Source_Functions](Source_Functions)