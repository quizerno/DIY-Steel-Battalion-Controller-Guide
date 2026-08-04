# 3. Playing on Xbox Without An Original Controller (Adapter Boards)

If you plan on playing on emulator, you can skip this section.
But if you want to play on Xbox or are curious about tinkering, read on.



**Skills you need**
- Knowledge of programming: Coding is not strictly necessary unless you want to do more complex control options.
- Mild understanding of linux commands
- Basic soldering: you will need to solder 4 points
- Patience: this can be difficult

# Xbox Modding

As said in the intro, I am not going to be detailing Xbox Mods as there are many tutorials.
There is softmodding, hardmodding, and TSOP modding. All will give a custom dashboard capable of running Steel Battalion.

# Hardware

## Adapter Board
Before building the controller proper we need hardware that emulates the original controller's signals.
For the sake of ease, we will call this an Adapter Board.

To connect the adapter board to the Xbox, you will need a cable that allows you to connect USB devices to the Xbox.  If you have done softmodding or hard modding before, you will likely have some experience with this.
|Hardware|Usage|Where to Buy|Price|
|---|---|---|---|
|USB-Female to Xbox Cable|Allows interfacing with the Original Xbox, also used for softmodding| [Ebay](https://www.ebay.com/itm/127869049454) among other places, you can also build one if you have a spare Xbox breakaway cable and a female USB port| Around 11 USD|

**Notes:**
- In the next section you will choose a platform for the adapter board
  - If the platform uses USB-C you can use an Xbox to USB-C Cable.
  - If the platform uses Micro USB you can use an Xbox to Micro USB Cable.


## Hardware you will need to decide on

|Hardware|Relevant Software|Where to Buy|Price|Notes|
|---|---|---|---|---|
|Teensy 4.1|[ogx360_t4](https://github.com/Ryzee119/ogx360_t4/)|Ebay, Sparkfun | 27-30 USD| Uses Micro USB, extremely powerful development platform. 
|RP2040|[OGX-Mini-2026](https://github.com/MegaCadeDev/OGX-Mini-2026)|Ebay, Sparkfun, Adafruit| 4-30 USD|Many Options including Pi Pico, Pi Pico 2, Pi Pico W, Pi Pico 2 W, RP2354, Pico/ESP32
|USB Host Cable (Female USB A)||Ebay, Sparkfun or other online electronics stores| 3-8 USD| Needed to take in the Custom Controller inputs. Some of the RP2040 boards (such as the Adafruit Feather) come with a USB Host built in and therefore do not require this cable
|Micro USB or USB-C Cable||Everywhere|1-15 USD|Needed to connect the platform to the computer, as stated above the Teeny 4.1 uses Micro USB, RP2040s have Micro USB and USB-C options


## How this works

<img width="1152" height="360" alt="image" src="https://github.com/user-attachments/assets/44a67dc0-539d-45d2-8aa5-a849d6a9ef41" />

The inputs are read from your controller into your adapter board which outputs Steel Battalion inputs to the Xbox Controller 
Through this rube-goldberg finaggling of connections, you can play Steel Battalion with a control set-up of your choosing.

## Which Board Should I Choose?


## Firmware for the board
For instructions on ogx360_t4 go here
For instructions on OGX-Mini-2026 go here


## Controller Pieces
