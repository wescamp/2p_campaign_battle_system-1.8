2p Campaign Battle System
v1.0
-------------------------

1. What is it?
2. Notes on Playing
3. Credits & Thanks
4. Known Problems
5. Change log

=========================

1. What is it?
--------------

The 2p Campaign Battle System is a simple addon for Wesnoth version 1.8.4 that allows two players to play cooperatively against the AI across a number of scenarios and maintain a persistent army. After each scenario the players can choose their next scenario, allowing them to control the difficulty level, the enemies they will face and the terrain they will fight on.

This addon was designed to be a simple, straightforward and reliable way for coop players to enjoy the process of building up veteran units. Almost all scenarios are "Kill all enemy leaders" and rely on core features of Wesnoth's gameplay: terrain, income and unit leveling. Other aspects, such as unique scenario objectives and storyline, do not feature. In return for this simplicity of concept, we hope to be able to regularly and rapidly add new battlegrounds so that players can continue to play on new terrain or start fresh with a new faction whenever they want.

The first release includes 22 maps on 7 different difficulty levels. Only one of these maps is not a "Kill all enemy leaders" scenario and it is a simple "Reach the signpost" scenario instead. Future releases may include more imaginative scenarios, but these will be categorized or described in such a way so that the player knows clearly what they are getting into before they choose the scenario.


=========================

2. Notes on Playing
-------------------

When selecting your next scenario, you will see that they are divided into different difficulty levels and each scenario has a brief description that should indicate the enemies you will face and the type of terrain you will be using. Players are expected to use their own judgement to get the difficulty level they want. For instance, a level 2 map on a desert map will of course be easier for players with Saurian units.

You are NOT MEANT TO PLAY ALL SCENARIOS of a single level before moving to the next. You should only play as many as it takes to feel that the level is no longer difficult. I suspect this will be 2-3 scenarios per level, but it will probably decrease at higher levels where the player can gain more experience in a single scenario.

If you're losing, don't restart! If your leader dies you will lose all your gold, but you will be able to choose another scenario and start again with any units you built up in the lost scenario.


=========================

3. Credits & Thanks
-------------------

Thanks goes first and foremost to the many developers of Battle for Wesnoth, for creating such a malleable game platform. Other than a tricky out of sync error, which Gambit graciously helped me locate and work out, this was incredibly easy to put together.

Otherwise, this is just a two-man effort by two coop players who sucked too much to complete any of the available multiplayer campaigns:

H-Hour		WML/Maps
		--------
		0101_3p_outlaw_fortress
		0102_4p_on_hostile_ground
		0201_4p_northern_thaw
		0203_4p_salvaged_woods
		0301_5p_river_wye
		0302_6p_raeners_gap
		0303_3p_coastal_ruin
		0304_4p_mountain_passes
		0601_6p_weary_age
		0701_4p_edge_earth
		
azrael1322	Maps
		----
		0103_4p_invading_sands
		0104_4p_road_north
		0202_4p_desert_fortress
		0204_4p_mosaic
		0305_5p_among_whitetops
		0401_6p_cursed_castle
		0402_5p_valley_heath
		0403_4p_siders_web
		0404_3p_forest_fallen
		0501_3p_citadel
		0502_7p_besieged
		0602_4p_wasteland


=========================

4. Known Problems
-----------------

- Out of Sync errors: It's possible to receive an out of sync error in one case. If one player moves to the next scenario and then moves a unit before the second player has clicked through to the next scenario, you may get an out of sync error. To resolve this, simply click the "No" option in the out of sync message window and bring the second player up to the next scenario. Once that's done, everything seems to sync just fine.

- Leader death error: If your leader dies, you'll still have a chance to move on, but if both leaders die you will need to load up a few turns back.


=========================

5. Change log
-------------

v1.0
Released: 2010-10-07
- First release with 22 scenarios
