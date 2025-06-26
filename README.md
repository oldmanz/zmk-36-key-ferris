## 36 Ferris Sweep

Current Layout is based on [miryoku](https://github.com/manna-harbour/miryoku)

To use, [Fork this repo](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo).

- Edit your keymap in the [config/base.keymap](config/base.keymap) file.
- When you make changes, Github actions will build the new firmware files.  Grab those in the Actions Tab.
- Unzip the firmware file.
- Connect your board with usbc to the pc, and double tap the reset button.
- Drag the firmware file to the now mounted device. (it will automatically disconnect and may pop up with an error.  It most likely worked fine)
- Repeat for the other half of the board.
- Here is more info: [https://zmk.dev/docs/user-setup#installing-the-firmware](https://zmk.dev/docs/user-setup#installing-the-firmware)
