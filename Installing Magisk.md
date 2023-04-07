Hello, here's tutorial how to install Magisk ( https://github.com/topjohnwu/Magisk )

Step 1. Unlocking BootLoader
//Warning, i am not responsing by any damage you made, the things im talking about is tested on my phone (Xiaomi Redmi 8) and working fine//
If you'r phone is by Xiaomi, i can tell how to do it, if it's not...
  Step 1.1. Downloading software
  You need to download Mi Unlock to your PC, sadly i don't have link to, and i forgot the version.
  And of course download ADB//Fastboot here: https://developer.android.com/tools/releases/platform-tools
  Step 1.2. Preparing phone
  Go to -> settings, Developer Options, Usb Debugging -> ON, Allow unlocking bootloader -> ON
  Step 1.3. connecting Mi Account and phone
  Go to -> Settings, Developer options, Status of Mi Unlock, [Press Agree], [Scroll Down], [Press Last button]_(you need to disable Wifi and be connected via SIM-Card or it's will give errors)_
  Step 1.4. Checking time
  open Mi Unlock on your PC, log in your Mi Account -> connect your phone to PC, open folder with ADB, type thoose commands: "adb devices", if you see "[Random Line]  Device" you did it right, if not, unlock your phone (if it was locked) and try again, and allow debbuging for that PC (press "Allow this PC to debbug this Device")
  Type: "adb reboot fastboot", if you did it right, the phone will show the FastBoot sign, and on some devices will show rabbit what is editing Android robot
  Go to Mi Unlock -> agree with that you lose every data (do you though this will be that good? heh, do Backup -> Long press [POWER] button // type in ADB "fastboot reboot", do last step again) and that the phone can be more effectivy attacked by viruses
  wait...
  after time you see above percentage you should repeat this step again, cya
  //
  //
  //
  Congrats! your phone are now with unlocked bootloader!
  Install TWRP (Reccomended) ( https://twrp.me/ ) or OrangeFox Recovery Project (Custom Recovery with themes and patches) ( https://orangefox.download/ )
  place the [Recovery.img] to ADB folder, type in CMD "adb reboot fastboot", "fastboot flash recovery recovery.img", "fastboot reboot recovery".
Step 2. Install Magisk
  now after all, use the Magisk documentation: https://topjohnwu.github.io/Magisk/install.html 
  //I'll recommend to check, even you have no RamDisk to install Magisk in Boot image, not recovery, if it is still don't work, sadly...//
  Good Luck using Magisk!
  
