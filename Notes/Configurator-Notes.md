# Sim Configuration Tool + Hotkey Fixes and Other Menu Options — requirements

## Sim Configuration Tool (SCT)

- **Pauses the VM at launch** for marked games. For Steel Battalion the pause
  is **right before the controller connects to the game**, so configuration is
  done before the game's controller check.
- A **window** opens where the player browses **profiles**, mostly per the
  controller the launched game expects.
- **Views mirror the real hardware**: left block, middle block, right block,
  **pedals**, and an **all three at once** view.
- **Calibration** is part of the tool.
- **Connects to the emulated Steel Battalion controller** for the SB games.
- **Connects a real SB controller to games that never supported it** — e.g. a
  different Xbox mech game — with a **default profile already built** for that
  game.
- Works with **USB passthrough automatically** — the user must NOT have to
  drop to a console and run passthrough commands as they do today.
- **Default profile shipped per game**; user profiles saved alongside.
- Also covers **racing wheels** and **cockpit/flight games** (Ace Combat-class)
  with joysticks/HOTAS.
- The specification must be **broad enough for everything Steel Battalion
  needs**, **flexible for other games**, and **adaptable to the other
  emulators**.

## Quality of life (new SCT dropdown)

A **fourth section in the SCT view dropdown**, beside left/middle/right block.
Contents so far:

### Alt-to-look (Arma 3 style)
- A function for mouse users that do not have a left joystick
- On the original controller, the left joystic's hat-stick (called Sight Change in game) **controls the direction of the VT's camera** 
- Clicking down on the stick **re-centers the camera**
- Previously in emulator the stick's directions had been bound the arrow keys or the WASD keys, with the click-down being tied to another key (Q or X)
- Keyboard-and-mouse players should be able to **hold a toggle** to do this similar to how Arma 3 does free-look.
- This switches from the default mouse function which is **weapon aim**
- **It does not need to snap back to where it was before when released.** But the weapon aim location needs to be maintained.
- Either the cursor must be moved back to the original position, or something needs to be done to keep the relative center understood
- A suggested configuration might be **hold alt to have the mouse control the camera** while **middle mouse click re-centers the camera**
- **Possible Issues:** Check interactions with lock-on

### Optional Controller Consolidation
- Allows an option to bind the **five toggle switches** to **one toggle**
- Allows an option to bind the **Hatch, Ignition, and Start** to **one button**
- Note that this **Optional Controller Consolidation** which should not be confused with possible **Necessary Controller Solidation** for the Gear Shifter and Tuner Dial 



## Input Settings Menu: 

### Kiosk mode (hotkey)

- A **hotkey binding** in the normal hotkey binds.
- **Default: unbound, or Ctrl+Delete.**
- Toggling it **disables all other emulator hotkeys**.
- Rationale: Steel Battalion uses so many keys that it is genuinely better to
  disable the emulator's own hotkeys wholesale.
- The kiosk hotkey itself must stay live so it can be toggled back off.

###Toggle Fullscreen Switch
- Turns off Xemu's double-click that switches the emulator window between fullscreen mode and windowed mode
-**Default: Disables This**
- Rationale: not just for Steel Battalionm for FPS games that use the mouse this is a must-have..


## Display Settings Menu: 

### Toggle Menu Bar 
- Removes the Menu Bar.
-**Default: Menu Bar On**
- Rationale: Done so that mouse users don't accidentally click it during play and gives a bit more viewing room

### Toggle the Cursor Visibility 
-  Done so that it is not in the way of mouse users
- **Default: Cursor On**
- Rationale: Done for FPS games and Steel Battalion.
