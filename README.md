TOTEM Wireless Manual
=====================
manual copied from https://suns-shave-80u.craft.me/NDKH6lhuW8BzBi

Power & Mode
------------

The keyboard can be powered either by USB-C cable or built-in battery.

To turn on battery power, slide the power switch to the right (when facing the switch).

The two halves pair automatically when both are powered.
- To use in wired mode:

Connect the left half to your device via USB-C.
- To use in wireless (Bluetooth) mode:

Power on the left half (battery switch ON). No cable is needed.
- To charge the battery:

Connect a USB-C cable and turn the power switch ON.

The power switch controls battery power only. When connected by cable, the keyboard is powered and works even if the switch is off.

Bluetooth
---------
- In wireless mode, search for “TOTEM” in your device’s Bluetooth settings to connect.
- Use the following keys to manage Bluetooth profiles:

- BT 0–4: Switch between Bluetooth profiles
- BT CLR: Reset the current profile

(See keymap below for key locations.)

Keymap
------

#### Default Keymap

The default layout is shown below:

If your TOTEM didn't come with this firmware, or you’d like to restore this configuration, you can download the firmware [here](https://github.com/Keycoon/zmk-config-totem/actions/runs/16163509301) (Github sign-in required). Then follow the [step 7 below](https://suns-shave-80u.craft.me/NDKH6lhuW8BzBi#54279AE2-8DE9-4A5D-A4E0-68AA5BBDAB04/Flash-the-firmware) to flash it.

#### Customization

You can customize the keymap in two ways:

##### 1\. ZMK Studio – Easy Live Keymap Edits

ZMK Studio allows you to visually update your keymap without rebuilding firmware.
- Visit: [https://zmk.studio](https://zmk.studio)

ZMK Studio is still in development and doesn’t support all ZMK features. For advanced customization, use the method below.

##### 2\. Full Customization – Build and Flash New Firmware

Use this method if you want access to full ZMK behaviors or advanced features.

Step-by-step:

1.

Create a GitHub account (if you don’t already have one):

→ [https://github.com](https://github.com)
- a platform helps you store configuration files and build firmware

2.

Fork the firmware configuration repo:

→ [https://github.com/Keycoon/zmk-config-totem](https://github.com/Keycoon/zmk-config-totem)
- Click the “Fork” button in the top-right corner
- This creates your own copy of the config repo

3.

Open the Keymap Editor:

→ [https://nickcoutsos.github.io/keymap-editor/](https://nickcoutsos.github.io/keymap-editor/)
- Link your GitHub account and forked repo

4.

Edit your keymap
- Modify layers, bindings, and advanced behaviors
- Reference official ZMK behavior docs:

→ [https://zmk.dev/docs/keymaps/behaviors](https://zmk.dev/docs/keymaps/behaviors)

5.

Save your changes
- When you’re done, click the “Save” button at the top of the editor
- This will trigger a firmware build automatically in your GitHub repository using GitHub Actions

6.

Download the compiled firmware
- Go to the Actions tab of your GitHub repo, Select the latest build run (or click the button to the right of the "Save" button in the editor)
- Download the firmware files

7.

Flash the firmware
- Connect the keyboard via USB-C
- Double-press the reset button on the top side
- A USB drive will appear on your computer
- Drag the corresponding .uf2 firmware file into it
- The keyboard will flash and reboot automatically

Flashing the left half is usually enough. Flash both halves if some changes don’t take effect.

What's your name?Share your name to let the document owner know who's joining in.Are you a Craft user? Log inReactCommentCopy
