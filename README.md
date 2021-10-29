# Super Star Trek

## What is Super Star Trek?
Super Star Trek is an old text-only game, an early example of a turn-based space strategy sim, written in BASIC. In this game, you are the captain of the starship Enterprise, and your mission is to scout the federation space and eliminate all the invading Klingon ships. You will have to manage the ship energy carefully, use phasers and torpedoes to destroy the Klingons, and find starbases to repair damages and replenish your energy. All of this, rendered with a few characters on screen and a lot of imagination.

Super Star Trek is probably the most famous early text-only game ever created - or at least as famous as The Oregon Trail or Zork - and it inspired many other videogames. Since the code was public domain, during the years, it was changed and improved many times. There are literally thousands of versions out there. All of them are nice, but my preference goes to the classic 1978 version called Super Star Trek.  

## The story of the game
According to Games of Fame, Mike Mayfield wrote the initial Star Trek game in 1971 for the Sigma 7 mainframe. The program didn't even require a screen. You could play it with a teleprinter machine: you enter the command after the prompt, and the game was printing some lines in return. How cool is that?

In 1972, Mayfield rewrote the game in HP BASIC, and one year later, the code became "public domain" when it was put to several HP data center machines. This version is what people consider the "standard" Star Trek game. Since the code was public, everyone was free to change it, or adapt it, so several versions emerged during the years.

David H. Ahl, the founder of Creative Computing magazine, published a BASIC-PLUS version of this program, calling it Space War, in his 1973 book BASIC COMPUTER GAMES. In 1974, a Westinghouse employee, Bob Leedom, ported the game to a Data General Nova 800. This computer had 32K of RAM, so he decided to expand and improve the code. He called it Super Star Trek.

Leedom enhanced the mechanics, improved the map, changed the original numeric commands into something more comprehensible such as NAV, PHA, COM, and added some occasional feedback from Spock, Uhura, Sulu, Scotty, and more. Fantastic!

It's important to note that all of this happened before the first home computers were even invented. Nobody had a computer at home before the Commodore PET, the Apple II, and the TRS-80 were released in 1977.

![26497](https://user-images.githubusercontent.com/14840708/139320391-ffd4e624-b4a3-481e-a74e-37c90a81ed3c.jpg)

David Ahl knew about the new version of Star Trek written by Leedom and asked permission to publish it in his new book, BASIC COMPUTER GAMES — Microcomputer edition, released in 1978. It would be the first computer book to sell 1 million copies. Some people say it's because the name Star Trek was in it. True or not, the game became hugely popular, mainly because, in the meantime, home computers had arrived. Suddenly there were thousands of machines capable of running BASIC and, consequently, BASIC computer games.

But now, let's play the game. 

## Let's play 1978 Super Star Trek
When the game starts, it generates the galaxy, and then it tells you the 3 main things you have to know: how many Klingons you have to destroy, how many days you have, how many starbases are present.

![26511](https://user-images.githubusercontent.com/14840708/139320567-5ce4120f-07fe-45b6-b132-1a5a838d3fdf.jpg)

In this case, we have been quite lucky: 3 starbases will be useful. One of them is here, but we don't need it now.

So, let's start! You control the Enterprise using the nine commands at your disposal. They are shown below:

![26512](https://user-images.githubusercontent.com/14840708/139320624-c3bced92-a21c-49fa-9951-5316e4834e32.jpg)

There are no Klingons in this quadrant, so let's use the long-range sensor scan to see if they are around. Long-range sensors show the number of ships, starbases, and stars in the 8 quadrants around you.

![26513](https://user-images.githubusercontent.com/14840708/139320675-c8cfe0af-79af-4f9f-8300-aaf9bc03d2ff.jpg)

The number "014" for the current quadrant means there are 1 starbase and 4 stars. The number "205" for the quadrant south-east from our position means there are 2 enemy ships (and 5 stars). Let's go there.

To move, you have to enter the command NAV and then specify the course and the warp speed. The screenshot below shows a description of the directions; this feature is not in the original game - this is the only small change that I consider acceptable on the 1978 code because it improves the playability a lot.

![26514](https://user-images.githubusercontent.com/14840708/139320712-95e7a8a7-df6c-4b99-95d1-26284c8eac56.jpg)

You specify the course with a number between 1 and 9. You can also use non-integer numbers if necessary, but we want to go south-east, so we enter "8". A warp speed of 1 will allow you to go to the next quadrant.

![26515](https://user-images.githubusercontent.com/14840708/139320766-00f32df8-eb84-4ec0-865e-09b8bccb934e.jpg)

On the new quadrant, we can see the 2 Klingon ships. As the text says, our shields are dangerously low. Better to raise them. Deflectors can be activated with the SHE command. We don't want to risk, so let's move 500 units of energy to the shields.

![26516](https://user-images.githubusercontent.com/14840708/139320825-96d5d7b7-a6f3-4694-9520-76913992e854.jpg)

Now we are ready to fight. We have plenty of energy, so we will use the phasers entering PHA. Like in the TV episodes, you have to decide how much energy will be used by the phasers. Since there are 2 ships, the Enterprise will fire twice, so the power will be split, better to use a reasonable amount.

![26517](https://user-images.githubusercontent.com/14840708/139320883-7a554fe6-0deb-40e1-ba6a-bc1c78d6118c.jpg)

Luckily, we destroyed them, so they won't fire back. That's good.

Continuing the exploration, we end up in another quadrant with 2 enemy ships. This time we'll try to use the torpedoes.

![26518](https://user-images.githubusercontent.com/14840708/139320914-ce0ffdc4-f3ef-47ad-b743-9a9f10702ea4.jpg)

Torpedoes don't hit automatically. We need to specify the direction. We will ask the computer to calculate the course. Enter COM to activate the ship computer. Then "2" and the computer will calculate the distance and directions of the enemies. The closest one is at distance 2.82 and direction 6.

![26519](https://user-images.githubusercontent.com/14840708/139320964-6643e4c6-fe11-4b67-922b-ddeaa5c74d47.jpg)

We will try to hit the ship with a torpedo. By entering TOR and then direction 6, we will try to hit the nearest Klingon ship.

![26520](https://user-images.githubusercontent.com/14840708/139321016-dad9b63c-fa7b-4fca-bf64-1120142866c4.jpg)

Success! The Klingon has been destroyed, but the other one hit the Enterprise. Not a big deal. With the phasers, we will beat the remaining one.

A few turns later...

Things were going well, but they can deteriorate quite quickly. A few turns later, we enter a quadrant with 2 enemy ships. Photon torpedos have been damaged in a previous fight, and energy is scarce. A first attempt with the phasers was not enough to destroy the 2 ships. Their counterattack damages the warp engines and the computer. Without warp speed, we cannot escape, so the only chance is to destroy them with the phasers.

![26521](https://user-images.githubusercontent.com/14840708/139321079-c4a28615-6fdd-41ed-aa82-0b29f3cfb525.jpg)

The next round of phasers destroys the enemies, but now energy is very low, and we need to reach the nearest starbase as soon as possible. Unfortunately, with the warp engines damaged, the maximum speed is 0.2. If the Enterprise consumes all energy, the game is over, so better to move back some power from shields to engines. We will need to avoid enemy encounters, or it's over. Once docked to the starbase, the energy goes back to the maximum level, and we can repair the damaged systems.

At this point, you should have an idea of the gameplay. As you realize, time is critical. Without a time limit, you would be able to go back to the starbases as much as you want and fight only when the Enterprise has full energy. But you can't. If you do this, time will expire. In fact, you must be very careful during exploration, trying to cover all the quadrants with the minimum amounts of movements, because time passes fast when you travel at warp speed. You cannot imagine how many times I lost a game with just 1 Klingon left, just because I needed one more turn to destroy it.

Of course, on the other side, if you risk too much, the Enterprise can be destroyed, as you can see below.

![26522](https://user-images.githubusercontent.com/14840708/139321136-02270db1-d5f6-4480-876e-5abf596e5388.jpg)

To make things complicated, there are random events. Sensors may be offline, so you are blind, and you encounter an enemy ship while you were trying to reach the starbase. If a hit damages your phasers, you only have torpedoes, but you can't see the enemy, so the only way is to ask the computer. But what if the computer goes down?

Despite its simplicity, there are really many different mechanics in this game, that combined with random factors, create surprisingly addictive gameplay.

![26539](https://user-images.githubusercontent.com/14840708/139321183-89ad36ec-cdcd-4dbd-b756-613e587ef391.jpg)

Of course, it's possible to win, as you can see above. Once you won, you get a score based on your performance and the difficulty of the scenario. Next time, you can try to improve your score.
