# 3D_Experimental
**NSFW WARNING!** The player model may not be safe for work environment

(Nothing explicit. The player looks like a naked mannequin)

Thank you for checking out my project! If you thought a 3D game engine in Processing is a 
bad idea, you're probably right! I was surprised to see this running at a favourable speed.

This is my latest experiment for a 3D game engine in Processing.

Aspects of this engine are influenced by early 3D engines, such as Source, Mario 64 and Doom engine

I hope I (and maybe even the community) can expand on this idea and make the code less ugly

Controls:

- WASD to move
- mouse controls camera
- press CONTROL to toggle crouch
- hold SHIFT to sprint
- press 'g' to toggle godmode (on/off)
- numbers 1 - 5 affect day/night cycle
- scroll wheel controls camera distance
- scrolling close to player will cause first person camera
- similarily, scrolling away from first person will cause third person camera

current bugs / features:

- no robot. Mouse is not fixed
- imported shapes may have weird outline (clearly visible on player model) (could be due to low-precision vertices)
- player does not always find shortest angle to turn (try turning around and around to see what I mean)
- when sprinting forward and jumping, holding 's' and 'd' will cause the player to go into warp drive
(I have no idea why this happens)
- nighttime is absent in the day/night cylce (once the sun sets, it immediately rises)
- lighting depending on the time of day isn't totally accurate, too saturated when close to sunset / sunrise
- the sky is one HDRI texture, the sun does not actually 'set' or 'rise'
- animations aren't particularily good
- no crouch walking animation (yet)
- no NPCS (although possible)
- currently no method of importing object files as solid objects
- object and animation files currently rely on txt. format and can be easily edited
- no reliable way to make animations or objects without custom processing sketch (which I can upload if inquired)
- no way to find positions of limbs of player for collision reference
- the game speeds up player movement when frames drop to make the game more playable. This however causes
issues when the frameRate is incredibly low (est. < 15 fps)
