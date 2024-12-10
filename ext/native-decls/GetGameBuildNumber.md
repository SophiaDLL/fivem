---
ns: CFX
apiset: shared
---
## GET_GAME_BUILD_NUMBER

```c
int GET_GAME_BUILD_NUMBER();
```

Returns the internal build number of the current game being executed.

Possible values:

* FiveM
  * 1604 ( Arena War DLC ) 
  * 2060 ( Los Santos Summer Special DLC ) 
  * 2189 ( Cayo Perico Heist DLC ) 
  * 2372 ( Los Santos Tuners DLC ) 
  * 2545 ( The Contract DLC ) 
  * 2612 ( The Contract DLC ) 
  * 2699 ( The Criminal Enterprises DLC ) 
  * 2802 ( Los Santos Drug Wars DLC ) 
  * 2944 ( San Andreas Mercenaries DLC ) 
  * 3095 ( The Chop Shop DLC ) 
  * 3258 ( Bottom Dollar Bounties DLC ) 
  * 3323 ( Bottom Dollar Bounties DLC )
  * 3407 ( Agents Of Sabotage DLC ) 
* RedM
  * 1311
  * 1355
  * 1436
  * 1491
* LibertyM
  * 43
* FXServer
  * 0

## Return value
The build number, or **0** if no build number is known.
