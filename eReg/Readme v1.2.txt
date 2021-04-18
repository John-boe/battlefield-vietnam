==================================================================
Battlefield Vietnam(tm) v1.2
Read Me File
August 9, 2004
==================================================================

KNOWN ISSUES AND WORKAROUNDS

-- 1.2 Patch and WW2 Mod - If you have not installed the WW2 mod, It is important
   to install the 1.2 patch after installing the WW2 mod.  If the WW2mod is installed
   after the 1.2 patch, the WW2 mod will not function properly. To resolve this issue 
   install patch 1.2 again after you installed ww2 mod.

-- Using Geforce FX5200 type cards with high or highest graphics setting in Saigon 1968 may cause problems
   on some systems with unpredictable behaviors on player input due to low frame rates. To resolve this issue 
   change the graphics setting to low or medium.

NEW CONTENT AND FEATURES

-- 3 new maps in Patch 1.2:
-- Operation Cedar Falls is a new map that introduces tunnels to BFV.
   Minimap changes when inside tunnels, and teammate icons only appear
   if they are on the minimap the player is currently viewing (ie above 
   ground or tunnels).  Tunnel flags appear in the minimap as vertical flags,
   differentiating them from the regular horizontal flag.

-- Saigon 1968.  Based during the Tet Offensive, the NVA have tunneled into the Saigon
   Sewer system in an effort to overtake the Presidential Palace.

-- Fall of Saigon.  It's spring 1975, and the NVA are moving quickly to attack Saigon as the USA 
   is finishing the final evacuations from Vietnam.

-8 vehicles are new in Patch 1.2:
-- The A1 Skyraider in 2 versions; one for anti-infantry (MGs and napalm), 
   and the other for anti-vehicle attacks (bombs and missiles).  
-- The Ontos is a new USA tank that can fire 1 round from it's 6 cannon sequentially, 
   or it can empty all 6 at once.
-- The BRDM Malyutka Complex is an NVA amphibious vehicle that fires
   wire-guided missiles.  Once fired, the player camera is attached to the missile. The control
   is similar to an airplane. Right-clicking will detonate the missile. 
-- Quad 0.50 MG is a static machine gun emplacement with 4 powerful cannons.  A 360 degree rotation  
   and a thick bullet shield make it a great option for clearing the skies of enemy targets.  
-- T-72 is a heavy NVA tank. The driver fires tank shells with primary fire, and shoots a machine gun
   as secondary fire. The gunner fires the canopy machine gun with primary fire, and shoots out 
   smoke grenades with secondary fire.
-- AC-47 Gunship. Heavy transport/gunship with coaxial chain guns out the left side.  The pilot can
   drop bombs with primary fire.
-- M35A1 Nancy.  A flatbed truck with a Quad 0.50 MG mounted in the back, an M60 facing to the
   front, and a couple armed passengers for good measure.
-- BM21 Troop Transport.  A BM21 truck with armed passenger positions filling the back.

-Mobile spawn points have been added to the 3d map.

-Unique colors for individual buddies.  Once a buddy has been added to the buddylist.con (located 
 in the settings\profiles\profile_name folder), that file can be edited manually to adjust the  
 RGB value of the individual buddies.  The unique color will appear in the mini-map, 3d map, and 
 for text, and death messages.  
 For instance, game.addPlayerToBuddyListByName "Player" 255.0 155.0 0.0
 = Red(R) 255.0, Green(G) 155.0, Blue(B) 0.0 --> an Orange buddy icon.
 
-Spectator Mode.  
-- Server must be setup to allow spectators to join.  If Spectator Mode is allowed, players can become spectators
   by clicking the spectate button on the in game side bar.  The player can return to teamplay by selecting
   the team button on the side bar and then selecting a team to join.  **WARNING** by becoming a spectator
   a player forfeits his points and will be forced to wait before being allowed to return to teamplay.  The wait
   time is set in the server interface.
-- Spectators see the health of all players or the health of the vehicle that the player is in
   They receive all CP change warnings,   regardless of team and even if that option has been disabled 
   for players.  Spectators see CP timers when they are within the capture radius, 
   or when they are using the associated CP camera.
-- Players do not see spectators on the 3d or mini-map, but they do appear on the Scoreboard.  Here they
   are treated as regular players, with full buddy capabilities.
-- Spectators have full voting privileges if the server allows for spectator voting.     

-- Spectator Mode Controls:
 Use Space Bar to cycle through the 4 camera types, or use the associated Function key.
 Free Camera (F9), Team 1 Chase Camera (F10), Team 2 Chase Camera (F11), and Control Point Camera (F12).
 Use 'C' to cycle forward through the cameras of a particular type, and 'X' to cycle backwards.
 Spectators can not view the spawn interface, but they can view the mini-map and scoreboard using the 
 regular controls.  Free Camera is not allowed in the tunnels; only chase cameras and the CP camera 
 may be used.
-- Remapping Spectator Controls:  If you wish to remap spectator controls, you must remap the function
   already using that key.  For example, you must remap Jump (Space Bar) to remap the 'Cycle Camera Type'
   control.  


BUG FIXES
-Tank splash damage against light and heavy vehicles now works.
-Minimap sorting order altered so players are visible above the CP flags.
-Performance problems resolved at the temple in Ho Chi Minh Trail and Cambodian Incursion.
-Repeating napalm sound bug has been resolved.
-The bug with grenades that goes through bridges has been resolved.

BALANCE/GAMEPLAY TWEAKS
-Helicopter pads at main bases will not reload or repair helicopters occupied by enemy players, 
 even after the control point is taken by the enemy.  Note that this is determined by the team 
 the player is on, not by the vehicle they are in.
    
-Mi8 hitpoints reduced from 125 to 100.  Rocket reload time increased from 3 to 4.5 seconds.

-Flaming Dart balance changes:
-- SVA tickets stop bleeding after a single flag is neutralized.  
-- One team must hold all 3 flags for enemy tickets to bleed.  
-- Jeeps added to starting SVA spawn areas, and are not tied to Control Towers.
-- Tango now spawns independent of the Control Tower.

-The static Quad 0.50 MG has been added to primary USA/SVA bases in:
-- Siege of Khe Sahn
-- Fall of Lang Vei
-- Operation Flaming Dart
-- Operation Game Warden
-- Operation Hastings

==================================================================
Patch 1.1
==================================================================
NEW CONTENT AND FEATURES
**Maps and Vehicles**
-Defense of Con Thien is a head to head battle across the DMZ separating 
 North and South Vietnam.  
 	Defense of Con Thien features 3 new vehicles:
	-OH-6 Loach is a scout helicopter used by the USMarines.  It's fast and agile, 
	armed with chain guns and can be used to spot for artillery strikes.
	-Ka-25 'Hormone' is an attack helicopter used by the NVA. It carries chain 
	guns and heat seeking missiles, and also benefits from the addition of 
	radar in the nose.  
	-Stationary M60 emplacements with infinite ammo.

**Menu and Game Features**
-MapVote/KickVote/Buddy GUI from BF1942 1.6 has been integrated into BFV 1.1.
-Longer player names (Up to 23 characters) will show up on the TAB screen.
-Current tickets for each team displayed on the TAB screen.
-Server IP, name, and current map appear on TAB Screen.  
-Server Favorites option added to server browser.
-Server Browser Legend added.
-Copy and Paste IP address into Add Server dialog box
-Servers rented through the EA 'Rent Server' program have a special icon in the server browser.
-The choice to using English Only dialog for all VO's added to Options Menu.
-3d map now shows friendly mines, traps, explosives, ammo boxes, and 
 medical cabinets.  These icons fade in as the player approaches.
-Pixel added to the middle of the crosshair.
-Flight Ceiling added to helicopters.

**Dedicated Server**
-Dedicated server supports the creation of a multiple mod/game mode maplist. Note that
 Evolution mode is NOT supported in a mixed mod map list.
-Added an option to force team switch at the end of a round.
-Added an option to carry tickets over between rounds.  This will work with 
 team switch, so the tickets will follow the team if they switch sides.
-Can force players with a defined string in their name to a particular team.
-Crosshair pixel centerpoint option added to dedicated server.
-Crosshair hit feedback option added to dedicated server.
-Dedicated server can choose between death camera options of orbit/reveal killer/free cam.
-TK punish mode options added to dedicated server.
-Password-reserved slots added to dedicated server.
-Option to disable the Flag Warning mini-map icon added.

BUG FIXES
-Disappearing/duplicate missiles bug fixed.  This was especially prevalent with the Mi8.
-Fixed bug where NVA mobile tunnel spawns wouldn't appear for some players.
-Punkbuster button is easier to see, and easier to select.
-Multiple VO messages at connection time fixed.
-Selecting the current weapon from the weapon menu will close the menu.
-Splash physics against soldiers fixed.  They now react with the appropriate
 force when a tank shell explodes nearby.
-lowered 44 Magnum rate of fire to better sync with the animation.
-Free camera prediction moved to client side to give smoother control.
-Removed splash physics from friendly explosions when Friendly Fire is off.
-Airlifting Tango no longer repairs/rearms helicopter.
-Vehicles on Tango won't float in the air when Tango moves.
-Can no longer deploy Pungi Sticks when in an armed passenger position (they would
 float around the vehicle).
-Can no longer deploy Claymores when in armed passenger position (they would 
 explode).
-Certain static object exploits fixed.
-Fixed potential exploit involved with altering video settings.
-AI shooting teammates has been lessened.
-AI visibility is now properly blocked by overgrowth/undergrowth.

BALANCE/GAMEPLAY TWEAKS
-Jeeps take less damage in water.
-Jeep top speed and torque increased.
-Helicopter bullet damage decreased against light vehicles and air vehicles.
-The ability to track air targets was lowered for vehicle mounted heatseekers.
-MUTT tow rocket changed to a heat seeker.  Reload time increased, ammo count decreased.
-Cobra heatseeker rate of fire decreased.
-Increased destabilization of Cobra when no driver, making it harder to switch to 
 the 2nd position to fire heatseekers.
-Slightly reduced Cobra hitpoints.
-M60 damage vs. helicopters increased.
-LAW and RPG damage vs. helicopters significantly increased.
-Vehicle resupply radius of ammoboxes increased from 3 to 8 meters.
-BM21SAM minimum firing pitch angle lowered.  
-BM21SAM Rate of fire doubled, but now contains 4x10 round magazines with a long reload.
-Increased ammo count of M46 from 30 to 50 rounds.
-Replaced static crosshair with animated one in all mounted MG's.
-Lowered minimum pitch of all tank turrets as much as possible.
-Kit speeds adjusted so Scouts are fastest, Heavy Assault slowest.
-Falling damage when going down stairs reduced.
-Flaming Dart air towers are less vulnerable to explosives and mortar attacks.


==================================================================
Patch 1.01
==================================================================
SERVER FIXES
-General optimizations to reduce server lag.
-CDkey hash added to game.listplayers output.
	-game.listPlayers uses the new format:
	#Id:<id> - <name> is remote ip: <ip>:<port> hash:<cdkeyhash>
-Gamespy port setting fixed.
	game.gameSpyPort 	- now working
 	game.gameSpyLANPort	- now working
	game.ASEPort		- removed (not supported by ASE)
-All Seeing Eye updated. 
	-Battlefield Vietnam games no longer appear in Battlefield 1942 
	ASE list.
	-Player details should appear correctly in ASE server list.

CLIENT FIXES
-Sort by Ping fixed in Server Browser.
-Scrollbar fixed in Server Browser.
-Player number now displays properly if more than 10000 players.
-Soldier prediction fixed to remove jerky movements when walking/jumping.
-M60 removed from the LAW kit and replaced with M14.
-M60 and RPD min/max bullet deviation increased when standing/moving.
-M60 and RPD max bullet deviation decreased slightly when prone.
-Rate of fire and velocity of M60/RPD adjusted.
-Player movement speeds on Heavy Assault kits reduced slightly.
-Network overhead of vehicle engines and airlifting significantly reduced.
-Added minimap warning icon when enemies are within capture radius of an 
 opposing team flag.


==================================================================
Useful Web Sites
==================================================================

http://windowsupdate.microsoft.com
Keep your Windows installation up to date.

http://www.eagames.com/official/battlefield/vietnam/us/home.jsp
The official Battlefield Vietnam website.

http://www.dice.se
Developer’s homepage.

==================================================================
Third Party Legal Information
==================================================================

Battlefield Vietnam uses Bink Video Technology. 
Copyright © 1997-2003 by RAD Game Tools, Inc.

==================================================================
DICE Copyright
==================================================================

Copyright © 2004 Digital Illusions CE AB. 

ALL RIGHTS RESERVED.
