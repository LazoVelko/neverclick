<div align="center">

<div align="center">
  <a href="https://neverclick.com">
    <img width="100" alt="Neverclick logo" src="https://github.com/user-attachments/assets/bcfc6210-e8ae-4d14-880f-025a15c2abbd" />
  </a>
</div>

# Neverclick

[Download](https://www.neverclick.com/) • [Discord](https://discord.gg/mJQ3KpsqP9) • [Twitter/X](https://x.com/LazoVelko) • [Reddit](https://www.reddit.com/r/neverclick/)

Neverclick is a desktop application for performing mouse actions with your keyboard.

</div>

https://github.com/user-attachments/assets/2ba988e9-3faf-4423-a2dd-1f1e60e53cb2

### Use it in any application.

Neverclick uses computer vision to detect UI elements on your screen.

https://github.com/user-attachments/assets/5ae876be-0f65-40cd-8355-5e26ee2f0faa

### Window mode vs Full Screen mode

Hit `Tab` to toggle between Window mode and Full Screen mode.

https://github.com/user-attachments/assets/3e36e752-6b12-40b6-bc3a-bfdb928aecdc

### Easily switch between windows.

Use `Shift` + `W`/`A`/`S`/`D` to switch between windows in Window mode.

https://github.com/user-attachments/assets/0d8f1f6d-286b-4d5e-95c0-f869d306cff4

### Other ways to switch between windows:

- Use `Shift` + `Q` and `Shift` + `W` to cycle through overlapping windows.
- Use `Shift` + `Z` to switch into the window behind the currently active one.

### Jump to the beginning or end of a word.

Use the arrow keys (or `Shift` + `J` `I` `L` `K`) to snap the target to the edge of the bounding box.

https://github.com/user-attachments/assets/5c8559fe-598c-4c3f-89a5-22b54eb4a132

### Click anywhere in between.

Press a number row key (`1`, `2`, `3`, `4`, `5`, `6`, `7`, `8`, `9`) to position the target.

https://github.com/user-attachments/assets/e0d03e62-65cf-4a60-9720-07225389f57f

### Click anywhere you want.

The target is in the center by default but you can move it anywhere you like.

https://github.com/user-attachments/assets/e33928f0-ca8a-486e-a02f-10b82e8c3a08

### Select multiple hints at once.

Press `'` to enter Dual Select mode to select 2 hints.

Press `Shift` + `'` to enter Multi Select mode to select multiple hints. Press `Enter` to finish.

https://github.com/user-attachments/assets/4c1843ac-636d-4a00-a9be-3ead30fca65f

### Select hints along a path.

Press `Ctrl` + `'` to enter Path mode. Select 2 or more hints. All the hints between them will be selected automatically. Press `Enter` to finish.

https://github.com/user-attachments/assets/d325c2aa-931a-4977-bdd5-2686000cd399

### Highlight text without a mouse (coming soon).

Activate the Text Highlighting Tool, then pick two hints to highlight the text between them.

https://github.com/user-attachments/assets/c022bad1-5e6d-4b81-a52c-ef85bd764dba

### Easily drag items without a mouse (coming soon).

Useful for dragging files between folders or rearranging the order of tabs in your web browser.

https://github.com/user-attachments/assets/f7999510-e911-43dd-9c4c-60a468d9bfb3

### Anatomy of a hint

- The **bounding box** is the rectangular outline of the detected UI element.
- The **hint** is the label.
- The **target** is where the mouse action is executed.

The target is placed in the center of the bounding box by default but you can move it.

![Diagram labeling the three parts of a Neverclick hint: the bounding box, the hint label, and the target](https://github.com/user-attachments/assets/0ef4ef29-d6af-4877-a6e1-5ead6a22cf0d)

### Neverclick prioritizes letters in the center of the keyboard.

However, you can customize this if you have a different keyboard layout.

![Keyboard map showing Neverclick's hint-letter priority, weighted toward the center keys](https://github.com/user-attachments/assets/171e931e-2d9f-407b-94ab-9ba88a40fa32)

### No config files.

Set up your hotkeys in a GUI.

![Neverclick's configuration window for setting up hotkeys in a graphical interface](https://github.com/user-attachments/assets/1643b4db-1ff0-417a-b111-e2217609a28d)

Configure your keybinds visually on an interactive virtual keyboard.

![Neverclick's interactive virtual keyboard for assigning keybinds visually](https://github.com/user-attachments/assets/32ebf1d6-462d-4abb-9024-f662912e4f18)

# Vision Modes

**Neverclick Vision** is a computer vision system which finds UI elements based on raw pixel data.

- It's extremely fast (instantaneous even on older hardware)
- It's able to detect text quite well so it's excellent for editing text and coding
- It supports a full screen mode
- Detection settings can be tuned

Neverclick Vision is the default vision mode.

![Neverclick Vision detecting UI elements from raw pixels, with hints overlaid on the screen](https://github.com/user-attachments/assets/0a714951-813a-4a63-b5ca-33a81a1feee3)

**Clairvoyance** uses operating system accessibility APIs to find UI elements.

- It's significantly slower than Neverclick Vision
- It can be unpredictable
- It only works on the foreground window (no full screen mode is supported)
- It doesn't detect text in text editors
- Detection settings cannot be tuned
- However, it may produce cleaner bounding boxes for buttons in certain apps

Clairvoyance makes for a good backup to Neverclick Vision.

Press `[` when the hints are up to switch into Clairvoyance mode.

![Clairvoyance mode detecting UI elements via operating system accessibility APIs](https://github.com/user-attachments/assets/4e951f3d-8bf8-4a4e-9b23-83a5e6be7e85)

**Grid** mode spaces hints evenly across the screen. It's useful for clicking blank areas, like right-clicking the desktop.

Press `;` when the hints are up to switch into grid mode.

![Grid mode spacing hints evenly across the screen for clicking blank areas](https://github.com/user-attachments/assets/e4e3349e-60d5-4aeb-857e-f7727b690f32)

# How to install

#### 1. Download it from [neverclick.com](https://www.neverclick.com/).

#### 2. Run the installer and follow the instructions.

![The Neverclick tray icon, which opens the configuration window when clicked](https://github.com/user-attachments/assets/9a4b6992-48b6-44b5-a7a1-70c880409afa)

#### 3. Verify that it works by pressing `Ctrl` + `Enter` to activate the Left Click Tool.

#### 4. Open the configuration window from the tray icon.

![The Neverclick installer running on Windows](https://github.com/user-attachments/assets/7f5c0935-20e8-4066-8417-6ed2794396c6)

# Coming soon...

- Scrolling
- Window switching via hints
- Moving windows between virtual desktops
- Much more...

https://github.com/user-attachments/assets/698ead2e-8dca-4443-a61b-1352a9e0c492

<div align="center">
  <a href="https://discord.gg/mJQ3KpsqP9">
    <img src="https://img.shields.io/badge/Join%20%20The%20%20Discord%20%20Server-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Join the Neverclick Discord Server" width="390"/>
  </a>
</div>

# FAQ

### Is Neverclick free?

Yes. It's free to download and use. There are no accounts, subscriptions, or trials.

### Is it Windows only?

For now, yes. Linux and macOS aren't supported yet.

### Does Neverclick have multimonitor support?

Yes.

### Will it work on my 4K monitor? How about 8K?

Yes, and yes.

### Does Neverclick work with non-English languages?

Yes. By default the hint labels use your keyboard's language but you can change it in the settings. The settings UI itself is English-only for now.

### Is there a portable version?

No. Neverclick installs to Program Files because Windows requires that for it to register as an accessibility tool. This is what lets it perform mouse actions on apps running as administrator.

### How fast is the computer vision system?

It's instantaneous. There should be no perceptible delay upon activating it, even on 10 year old hardware.

### How accurate is the computer vision system?

It's really good, but it does hallucinate occasionally. I'll continue to improve it.

### Do I need a powerful GPU to run Neverclick?

No.

### How much disk space does Neverclick need?

About 40mb.

### How much memory does Neverclick use?

It depends on your setup: how many monitors you have, their resolution, and your display scaling. On a typical 1080p monitor it's around 200mb. More monitors or higher resolutions will use more.

### Does Neverclick use CPU cycles when it's not being used?

No. Neverclick doesn't run in a continuous loop. It just sits there and only runs when you activate it. Its CPU usage should be at 0% at all times, except for when you actually use it.

### Is Neverclick powered by ChatGPT or any other AI service?

No. Neverclick's computer vision system runs entirely on your own machine. It's not built on ChatGPT, Claude, or any online AI service.

### Is my data being sent anywhere?

No. Everything runs locally on your machine. Nothing you do ever leaves your computer.

### Does Neverclick require an internet connection to work?

No. It requires an internet connection to install, but once installed, it runs without one. It's 100% offline.

### Where is the code?

The source isn't hosted here right now. This repo is for issues and releases.

### Is this still being maintained?

Yes. It's my daily driver, so I have every incentive to keep improving it and fixing bugs as I hit them.

### How much of this was made with AI?

It's about 95% human made (created by me) and 5% AI. I've worked on Neverclick for many years, predating the AI era. I only started using AI in March 2026. The percentage written by AI will increase over time, but I'm careful not to let it spaghettify the codebase. Additionally, the artwork was predominantly made in Blender (by me) and I created the logo in a vector graphics editor.

### Is there a backstory to Neverclick?

Yes. I made Neverclick when I was suffering from RSI.

### Do you still suffer from RSI?

No. I recovered years ago and I owe it to this software.

### What is the logo supposed to be?

It's meant to be an abstract mouse cursor but also the letter "N" when you connect the dot.

<img src="https://github.com/user-attachments/assets/bcfc6210-e8ae-4d14-880f-025a15c2abbd" alt="Neverclick logo" width="100"/>

<div align="center">
<a href="https://www.neverclick.com/">
  <img src="https://img.shields.io/badge/Download%20for%20Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="Download for Windows" width="332" />
</a>
</div>

<div align="center">
<a href="https://buy.stripe.com/dRmdR98CBamu3z46xweME00">
  <img src="https://img.shields.io/badge/Support%20This%20Project-8957E5?style=for-the-badge&logoColor=white" alt="Support This Project" width="300"/>
</a>
</div>

<div align="center">

https://github.com/user-attachments/assets/0025bed8-e6e4-4689-bf07-aa8a412e294f

</div>
