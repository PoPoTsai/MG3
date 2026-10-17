# MG3
## Devlog
1) Within the inspector, the default value for float appears to be 0f, the default for int is just 0, the default bool appears to be false as the checkmark is not there, and the default 
string appears to just be an empty string like "".

2) Unity will call the Update method for you, so that the user or programmer does not need to call the method, and will instead have whatever functions or pieces of code within the
method automatically run for every frame while Unity is running.

3) For KickWeapon, the class uses the Timer method BeginTimer, as part of _lifeTimer and assigns for the timer float in the Timer class to now be set to whatever argument value was chosen, which in this case was _lifetimeSeconds which was established in the inspector to be 0.2. Then, KickWeapon also utilizes the .isFinished() method for _lifeTimer to return a bool each frame
on whether the timer was less than or equal to 0 and returns true and stops the kick hitbox. Otherwise, the hitbox will remain for the period of time set by _lifetimeSeconds. 

## Open-Source assets
- [Cat fighter spritesheet](https://opengameart.org/content/cat-fighter-sprite-sheet)
- [Food sprites](https://rcpstd.itch.io/pixel-food-pack)