# EKS_Seatbelt

An immersive seatbelt system built with full customization, sound effects, indicator visuals, and optional ejection logic.

## ?? Features:
- ? Completely standalone, no dependencies (ox_lib recommended for notifications)
- ?? Buckle, Unbuckle & Chime sounds (Can be disabled)
- ?? OX-style notifications when buckling/unbuckling
- ?? Adjustable velocity for at what speed you get ejected when not wearing a seatbelt (Can be disabled via config)
- ?? When seatbelt is buckled, you can't exit the car (Can be disabled)
- ?? Visual indicator when seatbelt isn't buckled (Can be disabled)
- ?? Buckle sounds for everyone else in the vehicle (Can be disabled)
- ?? Export for your current seatbelt status: `exports.seatbelt:status()`
- ??? Double-clicking 'F' will remove the seatbelt instantly. Press 'F' again to exit the vehicle.

## ?? How to Install:
1. Place `EKS_Seatbelt` into your FiveM server's `resources` directory.
2. Add the following to your server’s `server.cfg`
   ensure EKS_Seatbelt
3. Adjust the `config.lua` settings to your liking.

## ? Frequently Asked Questions:
**Why does the seatbelt buckle and unbuckle at the same time when I toggle it?**  
If you used another seatbelt script before that used the same keybind, it may still be saved in your client settings.

**How to fix:**  
Go to `ESC` ? `Settings` ? `Keybinds` ? `FiveM`, and look for any duplicate bindings that use the same key (default is `B`).  
If you see another “Seatbelt” entry that doesn’t say `(EKS_Seatbelt)`, unbind it.

## ?? Support:
For any issues or help, contact R. Robertson directly on discord @operatorecho_kilo or email me on the email found in the LICENCE!

**IMPORTANT - DO NOT CHANGE THE NAME OF THE FOLDER ELSE THE SCRIPT WILL NOT WORK!**

**Support can be found here - https://discord.gg/busQ9w6dqa**
