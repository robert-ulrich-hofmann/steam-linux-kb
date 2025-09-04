# Steam Games

## HITMAN World of Assassination
``gamemoderun %command%``
- ge 8-23 works
- ge 8-26 works
- ge 8-32 does not work anymore!
- exclusive fullscreen 50 instead 30 fps
- but all settings rainbow lighting
- doesnt start with 7 9 e h or ge
- `-USEALLAVAILABLECORES` leads to rainbow lighting
- disable ecores (number of cores? weak cores?)

## Mass Effect Legendary Edition
``gamemoderun %command%``
- 7.0.6 to install ea
- experimental
- ge9-23
- runs exceptionally well stable no jitters no artifacts, 120 fps WOW

## Helldivers 2
``%command% --use-d3d11 -USEALLAVAILABLECORES``
- ge 8-26
- cap 30, uncapped will result in laggy mouse and your character walking slow motion
- gamemoderun leads to game guard errors, won't even start with it
- for some reason dx12 (standard) doesn't work anymore (black screen with running game and hud (you can hear and move normally) as soon as entering any mission), it used to. (uncapped fps, 40-50) and the performance was way better.

## Mechabellum
``gamemoderun %command%``
- disable efficiency cores for stable fps (otherwise dips below 30)
- 10.0-1 works flawlessly
- lock fps @30, it will break down to single digit fps in later rounds anyway

## Sniper Elite: Resistance
``PULSE_LATENCY_MSEC=90 gamemoderun %command% -USEALLAVAILABLECORES``
- Proton 10.0.1
- disable efficiency cores or the performance will drop to from 40 to 15 fps within minutes of loading a game
- crackling audio only in cutscenes and kill cams, not in normal game
- fix with pulse buffer, the less the better (less lag) (I needed 90)
- `-USEALLAVAILABLECORES` gives 5 FPS boost (on 6 real cores without HT)

## Half Sword Demo / Playtest
``gamemoderun %command%``
- 7.0.6

## LEGO Star Wars
``PROTON_USE_WINED3D=1 PROTON_NO_ESYNC=1 PROTON_NO_FSYNC=1 gamemoderun %command%``
- Proton 7.0.6

## RoboCop: Rogue City
``PULSE_LATENCY_MSEC=30 gamemoderun %command% -USEALLAVAILABLECORES``
- ge10-8
- badly optimized, needs to run with xess on performance (allthough it's still really enjoyable!)

## GTA V Enhanced
``-nobattleeye`` 
- ge10-10
- singleplayer only, hassle-free out of the box. `gamemoderun` does not work.

## GTA V Legacy
``gamemoderun %command% -nobattleeye`` 
- ge10-11
- singleplayer only, hassle-free out of the box. Way better performance (and no drops / stuttering than Enhanced version)
 
## next
``gamemoderun %command%``
- version
- review
