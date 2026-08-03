# 3. Playing on Xbox Without An Original Controller (Adapter Boards)

If you are playing on emulator, you can skip this section. But if you want to play on Xbox or are curious about tinkering, read on.

You can either map a Keyboard+Mouse, an existing controller like a HOTAS joystick, build one from scratch.
Before talking about the controller itself, let us discuss the mapping hardware

# Skills you need
- Knowledge of programming: Coding is not strictly necessary unless you want to do more complex control options
- Basic soldering: you will need to solder 4 points
- Patience: this can be difficult

# Hardware
## Hardware you will need regardless
Omitting obvious things like a computer
|Hardware|Usage|Where to Buy|Price|
|---|---|---|---|
|USB-Female to Xbox Cable|Allows interfacing with the Original Xbox, also used for softmodding| [Ebay](https://www.ebay.com/itm/127869049454) among other places, you can also build one if you have a spare Xbox breakaway cable and a female USB port| Around 11 USD|

**Notes:** 
- If your board uses USB-C you can use an Xbox to USB-C Cable
- If your board uses Micro USB you can use an Xbox to Micro USB Cable


## Hardware you will need to decide on

|Hardware|Relevant Software|Where to Buy|Price|Notes|
|---|---|---|---|---|
|Teensy 4.1|[ogx360_t4](https://github.com/Ryzee119/ogx360_t4/)|Ebay, Sparkfun | 27-30 USD| Uses Micro USB, has Ethernet and non-Ethernet variants has SD Card Slot 
|RP2040 Board|[OGX-Mini-2026](https://github.com/MegaCadeDev/OGX-Mini-2026)|Ebay, Sparkfun, Adafruit| 4-30 USD|Some boards use USB-C some use Micro USB, many options including Pi Pico, Pi Pico 2, Pi Pico W, Pi Pico 2 W, RP2354, Pico/ESP32
|USB Host Cable (Female USB A)|Either|Ebay or other electronics stores| 3-8 USD|Some of the RP2040 boards (such as the Adafruit Feather) come with a USB Host built in and therefore do not require this cable

Depending on the board you will need a Micro USB or USB-C cable.


## How this works



<img width="975" height="965" alt="image" src="https://github.com/user-attachments/assets/7d95fc88-7829-45cb-86cd-088762b4ac45" />

