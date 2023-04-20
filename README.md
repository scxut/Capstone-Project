# Capstone-Project
2D platformer
	
  
  Week1:
	Lost the finished backup from when my group presented in software engineering ;/
	Had to rebuild patrol enemy AI system from scratch
		-Created a patrol enemy script that can allow me to manually set patrol distances (old build you have to manually change the values within the script)
		-modified enemy attack scripts so that damage values, speed, and health values can be changed from with the editor (old build didnt allow for this either)
		-rebuilt the next level transition script (simple array index increment)		
		
    Week2:
	-Added Respawn System with triggers
	-Fixed a bug that would deactivate the player entirely before respawning
	

	Week3:
	-Added Controllable Jumping 
	-Fixed bug where player attack animation would trigger on key press but wouldn't damage enemies
	-Working on wall jumping but its broken 

	Week4:
	-Created a manager UI script that allows me to create menus easily 
	-Added a game over menu if a player dies and respawn checkpoints are not available
	-three working buttons added to game over screen
		-Restart
		-Main Menu
		-Exit
	-added a fireball arrow that moves to indicate what button the user is hovering on
	-W and UP arrow key to move up, S and Down arrow key to move down, E key to enter

	Week5:
	-Fixed a bug that wouldnt display game over or respawn character when dying in mid air
	-Fixed a bug that didnt properly return character to idle animation when respawning.
	-Added the game over screen as a prefab so that all levels can possibly display it
	-Fixed a bug when player dies player model doesn't deactivate (again)

	Week6:
	-Fixed a bug where the game would pause if you hit start game for a second time (had to set delta time back to 1)
	-Created a Main Menu with three working buttons
		-Start Game
		-Credits - Referencing my software engineering partners/me
		-Exit
	-Fixed a bug where levels would fail to start (Renamed method from Start to StartGame)

	Week7:
	-Added a boss
	-Created Boss enemy AI that seeks player
	-Modified Health Script to function properly with Boss AI script
	-Finished the credits screen with a working button that takes you back to the main menu
	-Created a game over screen that the player will see after defeating the boss
	-broke the entire game :)
	-fixed the game three hours later (restored backup, I would go into more depth but I don't understand how I did)

	Week8:
	-Created a third level (i dont like game design :/ )
	-Created a boss level 
	-Created different types of enemies
	-Fixed a bug that prevented enemies from dying whenever player spam attacked




ASSETS USED
https://oisougabo.itch.io/gap-i
https://brullov.itch.io/2d-platformer-asset-pack-castle-of-despair
https://blackdragon1727.itch.io/pixel-zombie-monster
https://comixtrash.itch.io/lifebar-pixelart-sprites-16x16
https://ansimuz.itch.io/magic-cliffs-environment?download
https://assetstore.unity.com/packages/2d/environments/2d-platfrom-tile-set-cave-61672
https://assetstore.unity.com/packages/2d/fonts/free-pixel-font-thaleah-140059
https://assetstore.unity.com/packages/2d/environments/platformer-set-150023
https://assetstore.unity.com/packages/2d/environments/platform-tile-pack-204101
