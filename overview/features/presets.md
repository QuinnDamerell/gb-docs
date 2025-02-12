---
description: >-
  Mainsail supports so-called presets. They are often used for preheat &
  cooldown, but also execute normal G-Code.
---

# Presets

## Setup <a href="#setup" id="setup"></a>

In Mainsails interface settings you will find a section called “Preheat Presets”. There you can set your presets via “ADD PRESET” and the following dialog.

### &#x20;Preheat <a href="#preheat" id="preheat"></a>

Enter a name for your preset, such as filament, color or other text and the temperature you wish to set the preset at. You can disable individual heaters and even specify a custom G-Code for the preheat phase. The G-Code will be executed after the selected temperatures are set.

<figure><img src="../../.gitbook/assets/image (8) (1).png" alt=""><figcaption></figcaption></figure>

### Further Examples <a href="#further-examples" id="further-examples"></a>

#### &#x20;**Z-Offset**

You can add custom G-Code to make it easier to switch between different Z-Offsets. This makes it easier to work with different surfaces and flexplates.

To configure the G-Code enter `SET_GCODE_OFFSET Z=0.2`, and change `0.2` to the offset you need.

<figure><img src="../../.gitbook/assets/image (2) (2).png" alt=""><figcaption></figcaption></figure>
