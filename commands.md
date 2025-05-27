# Debug Commands
## Disclaimer: Most of these have been proven to work some have yet to be tested listing is updated as it goes please create an issue or a pull request if you have anything to add or remove.

### System Commands
-------------------
#### [Client to Server Commands](#Client-to-Server-Console-Commands)
``d_c2scmd``
#### Changer render of mipmap/pixel. 0-10 high-low quality
``d_mipmapbias`` 
#### Sight of your camera.
``d_viewradius`` 
#### Seems to be useless or not working.
``d_playerradius`` 
#### Change the render of the trees. 0-4
``d_treelod`` 
#### Show/Hide Water 0-2
``d_render_water`` 
#### Show/Hide Grasses 
``d_render_grass`` 
#### Show/Hide Trees
``d_render_forest`` 
#### Show/Hide Shadow
``d_render_shadow`` 
#### Show/Hide Outline
``d_render_outline`` 
#### Do not prevent the window from updating when it loses focus.
``d_rendernofocus``
#### Changes UI theme 0=old 1=new
``d_theme``
#### Change ingame time (client side only). Format: 10,00 (mean 10AM).
``d_settimeofday`` 
#### Same thing as (F9) but without the Screenshot window.
``d_cameramode``
#### Move to X, Y cords. Use ``d_showpos`` to help you.
``d_goto x, y`` 
#### Move to the specified game coordinates
``d_go x, y``
#### Display all purchased EB?
``d_money``
#### Open a url in the browser
``d_ie <url>`` 
#### Changes window title?
``d_title`` 
#### Fly but only works when you have a high movement speed. For flying without speed adjustments use [d_c2scmd fly](#Fly-but-not-broken)
``d_fly``
#### Changes player runspeed values exceeding 5 cause rubberbanding due to server anti-cheat
``d_runspeed``
#### Seems to be useless or not working. Perhaps to use a skill?
``d_skill``
#### Seems to be useless or not working. Quests are known as Tasks may be related to completing a quest
``d_task``
#### Return to character selection screen.
``d_relogin`` 

### Information
---------------
#### Some wire boxes on in-game objects.
``d_boundbox``
#### Show Dynamic NPC's ID in the order they were spawned.
``d_npcid``
#### Show/Hide the cords for every NPC, MOB, PLAYER (and you).
``d_showpos``  
#### Show the distance between your character and the cursor.
``d_testdist`` 
#### Show/Hide item/npc/character's ID instead of their name. You can also get a character's ID by ``CTRL + Right Click`` their name in chat.
``d_showid`` 
#### Show the server date and time.
``d_getservertime`` 
#### Show last login time
``d_lastlogintime``
#### Show character creation time
``d_createtime``

### Show Debug info
-------------------
#### Shows debug info
``d_rtdebug``
#### Show/Hide 3D game information.
``d_a3dstat``
#### Show/Hide computer and game resources.
``d_gamestat``
#### Display information related to debugging UI
``d_uidebug``
#### Show/Hide FPS in the right upper corner of the screen.
``d_fps`` 
#### Shows a gfc from gfc.pck (requires dir location)
``d_gfx``
#### Seems to be useless or not working.
``d_skipframe`` 
#### Seems to be useless or not working.
``d_modelupdate`` 
#### Write dump, close the game and show the Report Bug window.
``d_minidump`` 

### ID Search
-------------
#### Search for a partial name of an item / mob / npc and get its ID in return
``d_query`` 
#### Type an npc id and get back its coordinates (if its already in the autopath database)
``d_querynpc`` 
#### Search for a partial name of an NPC Service and get its ID in return
``d_queryservice`` 
#### Type in a partial model path and it spits out the items that use it
``d_querymodel``

### ???
-------
#### Seems to be useless or not working.
``d_turnaround``

#### Seems to be useless or not working.
``d_trnlayer`` 
#### Seems to be useless or not working.
``d_trncull`` 
#### Maybe for make some changes on GS(gamed)? GS controls the servers rates(exp/drop/gold/spirit/etc) and who knows what else.
``d_gscmd`` 
#### Delete command?
``d_delcmd``
#### Seems to be useless or not working.
``d_namepos`` 

### Client to Server Console Commands
-------------------------------------
#### Drop gold on ground
``d_c2scmd 20 <amount>``
#### Invite player to party
``d_c2scmd 27 <id>``
#### Meditate
``d_c2scmd 46``
#### Open Self Shop
``d_c2scmd 84``
#### Initiate duel with a player
``d_c2scmd 92 <id>``
#### Take your hands? (Embrace)
``d_c2scmd 95 <id>``
#### View characters information
``d_c2scmd 99 <id>``
#### Change class
``d_c2scmd 1102 0 <id>``
#### Gain gold relevant to the equation (level*100)
``d_c2scmd 1988``
#### Change pet mood maybe?
``d_c2scmd 1989 <id>``
#### Gives exp + spirit(note this is affected by the servers exp rate and can result in receiving negative experience)
``d_c2scmd 1999``
#### Add level 1 character
``d_c2scmd 2000``
#### Create item with 1 minute timer(no idea how to change timer amount needs to be looked into)
``d_c2scmd 2001 <id>``
#### Grants double experience for target player for a duration range of 0 to 14400 seconds.
``d_c2scmd 2009 <id>``
#### Gain 100 EB
``d_c2scmd 2014``
#### Expand inventory slots by amount
``d_c2scmd 2016 <amount>``
#### Makes target player spouse
``d_c2scmd 2020 <id or 0 for divorce>``
#### Gain spirit by amount
``d_c2scmd 4441 <amount>``
#### Clears inventory
``d_c2scmd 4444``
#### Spawns item by quantity on the ground
``d_c2scmd 10800 <id> <quantity>``
#### Gain experience by amount(note this is affected by the servers exp rate and can result in receiving negative experience)
``d_c2scmd 10889 <value>``
#### Spawns a mob/npc for the specified duration (NPCs that are spawned are not interactable)
``d_c2scmd 10802 <id> <quantity> <spawnduration> 0``
#### Fly but not broken 
``d_c2scmd 10803 66``

# GM Commands

``gm_kickout_role`` 
``gm_kickout_user`` 
``gm_list_user``
``gm_online_num``
``gm_restart_sev``
``gm_shutup_role``
``gm_shutup_user``
``gm_moveto_player``
``gm_callin_player``
``gm_broadcast``
``gm_showid``
``gm_forbid_role``
``gm_trigger_chat``
``gm_generate``
