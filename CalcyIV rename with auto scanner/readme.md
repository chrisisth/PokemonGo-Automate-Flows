This flow is designed to work with the free version of the Automate app by LlamaLab and in conjunction with the "auto scanner" feature of the [CalcyIV](https://play.google.com/store/apps/details?id=tesmath.calcy&hl=en-US) app in order to automate the process of scanning Pokemon and renaming them.

In order to make this flow work you need:
- To have CalcyIV started in auto-scan mode
- To screen share the Pokemon Go App, not the full screen
- To be on a Pokemon page (not the appraisal, just the regular screen)
- Allow CalcyIV to use the clipboard of your device
- Have the "Automate" input set up

1. **Start**: Press the volume down button to activate the flow. A notification will appear to confirm the start of the process.
2. **Operation**: The flow will automatically scan Pokemon and rename them based on the nickname profile set in CalcyIV within the game.
3. **End**: You can stop the flow at any time by pressing the volume up button. To kill the flow, you need to manually stop it in the Automate app.

## CalcyIV auto scanner

You need to select the Automate soft keyboard at start! You may need to enable it first in keyboard settings.

## CalcyIV auto scanner slow

This version is similar to the [CalcyIV auto scanner](#calcyiv-auto-scanner) one but does not scroll down on a Pokemon in order to hint the spells to Calcy, it will only rely on the appraisal feature. It has been designed to be reliable and let ran for many Pokemons.

1. Click the burger menu (3 lines) at bottom right of your screen
2. Click appraisal to allow CalcyIV determine the IV of your Pokemon
3. CalcyIV will then use your clipboard to copy the name you've configured
4. Click on your Pokemon name to toggle the "rename" pop-up
5. Erase the current name
6. Paste the clipboard value
7. Press OK to rename
8. Swipe next Pokemon
9. Repeat from step one
