# Feature tracker, FAQ & instructions

## When is it going to be done?
it's hard to say. this project/port is being contributed to on my free time. feel free to fork and create pull requests, i'll highly appreciate it. :)

## Can I use this on other devices using the Exynos 7420 SoC?
er, not really. you may use the kernel from this organization, but you will have to edit the configuration to make it work with your device, aswell use a different device tree!

## How can I get a cool splash screen?
oh, like [this](https://user-images.githubusercontent.com/51330681/133930469-e5fefb5d-dfcb-4980-aca8-40f4df7b5936.jpg)?

1. download the [custom splash screen flashable archive](https://github.com/ubuntu-touch-on-zeroltexx/readme/raw/halium-7.1/utsplash.zip).
2. connect your phone and boot into TWRP.
3. push the .zip file to your device using `adb push /path/to/utsplash.zip /sdcard/`
4. press the "Install" button on your phone, select the utsplash.zip archive and install the package by sliding the slider at the bottom.
5. you're done!

### How do I get the old splash back?
the custom splash screen archive generates a back up of your splash screen when flashed. to restore your splash back to original, do the following:

1. download this [splash screen restore archive](https://github.com/ubuntu-touch-on-zeroltexx/readme/raw/halium-7.1/restore_backup.zip).
2. and just install it using the instructions above.

