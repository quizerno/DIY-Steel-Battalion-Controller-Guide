# 3. Playing on Xbox Without An Original Controller

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
|USB Host Cable (Female USB A)|Allows your custome controller to connect to whichever controller board you decide on (see next below)| Ebay or other electronics stores| Around 3-8 USD|

**Note:** If your board comes with a built in host (such as the Adafruit Feather) you will not need a USB Host cable.

## Hardware you will need to decide on

|Hardware|Usage|Where to Buy|Price|
|---|---|---|---|
|Teensy 4.0|Adapts your inputs to Steel Battalion Inputs |Ebay, electronics websits | 27-30 USD
|RP 2040 Board|Adapts your inputs to Steel Battalion Inputs|Ebay, various vendors Ranges from 4 USD to 30 USD
|Interface cable|Whichever cavl
Your Custom Controller With USB Cable 
A Teensy 4.0 with USB Host Cable (Female USB A)
Micro USB Cable
USB-Female to Xbox Cable
A computer
This software: ogx360_t4





Alternatives to ogx360_t4
OGX-Mini is a project by WiredOpposite that uses RP2040 boards to allow different gamepads to interact with Xbox, PS3, and Nintendo Switch. It has a built-in configuration (from og360) that will map Steel Battalion inputs to a Xbox 360 with a Chatpad attachment (see picture). Unfortunately, OGX-Mini’s configuration options are quite limited , so customization and rebinding appear to be out of the question. Hence I do not recommend it for Steel Battalion.


<img width="975" height="965" alt="image" src="https://github.com/user-attachments/assets/7d95fc88-7829-45cb-86cd-088762b4ac45" />

