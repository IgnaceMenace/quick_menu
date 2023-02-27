# QuickMenu
Rust based program you can execute whenever you want and will pipe data into a rofi-like app launcher

The project is not ready yet

I will decide between rust or python depending on the available libraries, I already have
a few modules in my config written in python that i would just have to translate. 

# Functionalities
- Desktop, app launcher agnostic
  - Should work on whatever linux desktop
  - Should be able to communicate with wthever app launcher you want (fuzzel, rofi, etc)
  - Thanks to this it won't care if you are on wayland or xorg
- Main menu
  - Power menu
    - Log Out
    - Suspend
    - Hibernate
    - Power Off
    - Restart
  - Power management menu
    - Performance mode
    - Normal mode
    - Power Saving mode
  - Tiling menu
    - Alternating
    
  - Input/Output Menu
  - Light mode menu
    - Dark mode
    - Light mode
    - Red light intensity
  - Wifi menu
  - Bluetooth menu
    - Enable/Disable
    - Pair device
    - Connect Device
