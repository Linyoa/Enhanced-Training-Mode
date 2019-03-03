When Super Smash Brother’s Ultimate was announced, we all had rather high hopes for the game. In a lot of ways, those hopes were met (Everyone is here!), but one way they certainly weren’t met is its training mode. That’s not to say it’s not an improvement over past games, in a lot of ways it is, just that it still leaves something to be desired. A lot to be desired. That’s where the Enhanced Training Adapter comes in.
The adapter was born as a way to allow users to lab combos with multiple DI, SDI, and escape options. From there, more and more features were added, and I’m got plans for plenty of new stuff in the future too.

# Requirements

While the adapter is plug and play, it does have a few requirements: Namely, a GameCube controller, as well as either an official Switch/WiiU adapter or a Mayflash adapter. Note that while the adapter supports the Gamecube or Wii, and will mostly work fine for older smash games, it is designed with Ultimate in mind. Please also note that if a Mayflash adapter is used, it must be updated to the latest firmware and both USB ports must be plugged in. Additionally, the control scheme used for the training adapter should be default controls with tap jump OFF and rumble turned ON. 

# Getting Started

Setting up your Enhanced Training Adapter could not be simpler. Simply plug a second Gamecube Controller into the female port on the training adapter, and plug the training adapter into the console the same way you would a normal GameCube controller. After that, plug the controller that you’re going to play on into the console, and you’re good to go!

Please note that the training adapter is meant to be used on a second controller, controlling a second player, NOT the controller you yourself are going to be using. It can be used in training mode or in regular battles, but if used in training mode, please set the CPU to “control”.

# Modes

The adapter features three different operation modes: basic, advanced, and Nintendospy. In basic mode, all options are triggered immedietly upon selecting them. This means, for example, if you pick Left/Right DI while in basic mode, the CPU will immedietly start dash dancing in place. Additionally, less features are avialable in basic mode. Advanced mode, on the other hand, does not activate the DI or Escape options you select until the CPU gets hit (or something else triggers rumble). The reason for this split is that when you set the Training CPU in training mode to "control", the game will never trigger rumble on that controller. Therefore, you should only use advanced mode to either control the player character in training mode (rather than the cpu) or practice in a regular match. Two switch between modes, hold start when plugging the controller in. Also note that the adapter will remember what mode you picked last, and default to that mode.

Different training mod options are cycled via the D-pad. By default, all training modes are off. Press the D-pad option of your choice to cycle to the next option on the list. Press start to turn all modes off again.

# Basic Mode

- DI Modes (D-Pad Left)
	- Random Left / Right DI - Switches between full left and full right DI every frame.
	- True Random DI - DI in an entirely new and random direction every frame.
	- Set DI - DI in the direction the stick was held in when this mode was enabled.
	- Random SDI - The CPU will pick one of the 4 cardinal directions and max speed SDI in that direction. Press start to reset SDI, and the CPU will pick a new direction the next time it is hit.
	- Set SDI - The CPU will max speed SDI in the direction the stick was held when this mode was enabled.

- Escape Modes (D-Pad Right)
	- Airdodge - Airdodges every other frame.
	- Jump - Jumps every other frame.
	- Down-B - The CPU will use down special every other frame. Useful when combined with down special like rest or pokemon change.
	- Up-B OOS - The CPU will hold shield. After a hit connects on shield

- Input Recording - Press D-Pad down to start recording inputs (for up to 400 frames. Press D-pad down again to stop recording inputs.
- Input Playback - Press D-Pad Up to start playing recorded inputs. Input loops on completion.

# Advanced Mode

In advanced mode, DI and Escape options are only triggered on hit, rather than immedietly. Additionally, the following options are enabled:

- OOS Options (D-Pad Right + L)
	- Up-B OOS - The CPU will hold shield. After a hit connects on shield, it will immedietly up-B OOS
	- Up-Smash OOS - The CPU will hold shield. After a hit connects on shield, it will immedietly up-smash OOS
	- Grab OOS - The CPU will hold shield. After a hit connects on shield, it will immedietly grab OOS
	- Nair OOS - The CPU will hold shield. After a hit connects on shield, it will immedietly nair OOS
	
# NintendoSpy

You can enter NintendoSpy mode by holding D-Pad down on plug in. When in Nintendo Spy mode, training features are disabled, but the input display is enabled. Simply download NintendoSpy here: https://github.com/jaburns/NintendoSpy/releases/tag/v1.10.1 and plug your adapter into your PC via a mini-usb casble.

# Updating
You can always find the most recent version of the Enhanced Training Mod hex on my twitter (@Linyoa) or on my GitHub (https://github.com/Linyoa/Enhanced-Training-Mode). Once you’ve downloaded the hex file, you can load it onto your adapter with a tool like Xloader (http://xloader.russemotto.com/). First, pop the lid off your adapter, and plug it into your pc with a mini-usb cable. Then, simply open Xloader, select the hex file you downloaded,  and then select Duemilanove/Nano(ATmega328) as the device, and make sure you're using the correct COM port (it should be the one that shows up when you plug your board's USB cable in). Leave all other options default, then press upload.

# Building your own
To build you own, check it this guide by SimpleControllers: https://docs.google.com/document/d/1gWrSWay3a0utMu--3GWUzfrxPZzdtf34wqbHLplC7hE/edit?usp=sharing
If you have any problems with the guide, try joining the Painthouse Discord (https://discord.gg/KKq8gR9 ) or feel free to DM me. Please note I am not responsible for any damages or problems you may have while making your own, though I'll do my best to help you.

# Contact
If you have any questions, comments, or concerns, feel free to drop me a DM on twitter (@Linyoa). I always love hearing your feedback and ideas!
