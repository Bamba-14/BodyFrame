# Welcome to BodyFrame 01.01.2021 - 01.03.2021 Update
![Homescreen](https://github.com/Bamba-14/BodyFrame-images/blob/main/Homescreen.PNG?raw=true)
The last update showed the integration of range weapons, starting with a bow. The bow provides a way to deal damage from a safe distance, but you always have to keep an eye on the amunition count, as the arrows are hard to find, so use it wisely. In terms of mechanics, how the bow works, it's what you'd expect, it has a limited range, you can see the projectile and once you fire it, the amunition count goes down by one and the damage to the enemy is applied (expect this to vary in other ranged weapons to be introduced in the future). The only way to get more amunition at the time was to find it somewhere in the world.
The second major thing was the introduction of a simple UI, with a pause menu option, if you would for example have to prepare a cup of coffe or tea to complement your gameplay experience. The UI is one of the segments that has been worked on the most these last couple of months, so lets dive right in.

## The expansion of the UI
As you've seen in the image above, the Homescreen currently has two options, to start a new game or to quit to desktop. When we start a new game, we're put in the world, somewhere near a village called BuckySide. To access other UI elements, you press the Escape button and it brings up an improved pause menu as shown in the picture bellow (all buttons are indeed working):
![Pausescreen](https://github.com/Bamba-14/BodyFrame-images/blob/main/Pausescreen.PNG?raw=true)

I know, the most interesting part is definetly the Inventory button. If you've been folowing the development of the game, you know it already had an inventory system, but there was no way no see it. Well prepare to be blown away, as the inventory system is now visible and expanded, to allow you, the player, full control over the items you've been able to gather.
![Inventory](https://github.com/Bamba-14/BodyFrame-images/blob/main/Inventory.PNG?raw=true)

I know, it's pretty slick. You can see all of your items, their descriptions and the amount you currently hold. In the image, the arrow icon is selected, and as you can see, there is also a use button and once you press it, it increases your amunition count by 10 and it uses the item, since there is only one remaining it will disappear from the inventory. The "Use" button is not visible if you select a sword, since you can always use it. Ofcourse, there is also a "Back to Pause" button, that brings you to the pause menu. How the menu looks is going to change in the future, but the functionality will stay the same. Oh, if you're like me and you like to pick up everything you find in the game world and save it for when you really need it, don't worry, the inventory screen is scrollable, so you can fit in as many items as you'd like. 

If we go to the pause menu, you can always save the game, so the next time you return to it, you can continue from where you started. For now, the location of the player is not stored, working on it currently, but your health, amunition, items, opened treasure boxes are going to save and wait for you to come back. The future plan is to save enemies killed, your location and other things that will be added in the future. 
You can also reset the save, so you can experience the game from the begining. For now you have to press reset save, save the game, quit to main menu and press new game from there. In the future, the main menu will have the option to start a new game or load the saved game. 

Well for now that's all from the UI front, it was a lot of work and things like saving the game is not so fun to read about. So don't worry, I have just the thing to finish this update.

## Neutral characters in the world - simple AI
You've read correctly, the first non-combat character has been added. The sprite is simple and will be replaced, it's currently in the works and you never know, if you read to the end you might just get a sneak peak of him.
![Character](https://github.com/Bamba-14/BodyFrame-images/blob/main/Character.PNG?raw=true)

We can call this character a Farmer. The Farmer is confined to the rectangle marked with a black line (not as sloppy as in the image) and inside of it, he can walk in all four directions, and it's very random, the direction and the lenght he walks is randomly selected, so you will never see him do the same thing twice, he has a mind of his own. Best of all? If you want to interact with him, he will stop and allow you to interact with him (using the "E" interact button).
![Character1](https://github.com/Bamba-14/BodyFrame-images/blob/main/Character1.PNG?raw=true)

Beside the Farmer another character was introduced to the game. It is exhausting to be fighting trees all the time, so how about fight a strong green monster with a mace? Yes, they hit harder and are harder to kill, but once you see how he terrifies everyone in BuckySide you know it's the right thing to do.
![Enemy](https://github.com/Bamba-14/BodyFrame-images/blob/main/Enemy.PNG?raw=true)

I'm almost sure that's all the news I have for right now. Do come back to this post as I will post a youtube link to a video, showcasing all of the current features in the game, including every features from this update. 
And as promised, since you've stuck to the end, here is a sneak peak of the farmer character model:
![NPCwalking](https://github.com/Bamba-14/BodyFrame-images/blob/main/NPCwalking.png?raw=true)
![NPCidle](https://github.com/Bamba-14/BodyFrame-images/blob/main/NPCidle.png?raw=true)
