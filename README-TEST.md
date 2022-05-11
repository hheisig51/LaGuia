# LaGuía

By Henry Heisig

_Contact me at [henry+laguia@eheisig.com](mailto:henry+laguia@eheisig.com) (or talk to me in-person) with any questions, comments, or concerns!_

A guide to markdown, VSCode, Github, and more

## Table of Contents

- [Table of Contents](#TableofContents)
- [Github](#Github)
- [VSCode](#VSCode)
- [Markdown](#Markdown)
- [About](#About)

## Github

WIP.

Best advice for now is to go poking around repos. A lot of little settings to fiddle with.

## VSCode

"Black Magic!" - Karl Helmstetter, 2021

VSCode is a highly customizable IDE, more capable than Mu or Repl.it, but harder to optimize to. If you want to forge your path; through trial and error; through fire and brimstone; then go right ahead! Close this, and figure it out. However, if you want helpful resources for your adventure, then continue reading.

### Setup

Open VSCode. It should be already installed on your computer.

On the lower left, at the bottom, there should be a settings icon:

![Settings](/Images/settings-gear.png)

Click it. Next click `Online Services Settings`

On the upper right, click `Settings Sync`

Click `Sign-in and Turn On`, then `Sign-in with GitHub`

It will walk you through the process of logging in.

Now, hit `Ctrl` + `Shift` + `P`, type `Git: Clone` and the command should appear. If you succesfully logged in with GitHub, you can click `Clone from GitHub`. If the repo wasn't made by you, or you had trouble logging in, you can still provide the repository URL to clone.

VSCode should guide you through where to put the folder.

### Adding Microcontroller Drive as Folder

On the far left sidebar, near the top, there's a files icon:

![Files](/Images/files.png)

Click it, and it will open the file explorer for your workspace.

### Creating a New File

TODO: PLACEHOLDER FOR CREATING A NEW FILE

The rest of this guide is a reference for various components of VSCode

- [Git/Source Control](#gitsource-control)
- [Extensions](#extensions)
- [Keyboard Shorcuts](#keyboard-shorcuts)

### Git/Source Control

On the far left sidebar, there should be a branch-like icon:

![Source Control](/Images/source-control.png)

Click it. This is where VSCode manages all the source control...

WIP

### Extensions

Also on the far-left sidebar, you'll see an icon that looks like this:

![Extensions](/Images/extensions.png)

Click it. It shows the extensions already installed, and the recommended extentions to be installed. Below are some links to extensions for various purposes.

_Install as you see fit!_

#### Code Extensions

- [Arduino](https://marketplace.visualstudio.com/items?itemName=vsciot-vscode.vscode-arduino)
- [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python), refer to [below](#python-installation) if the extension asks you to install Python.
- [CircuitPython](https://marketplace.visualstudio.com/items?itemName=joedevivo.vscode-circuitpython)
- [Serial Port Helper](https://marketplace.visualstudio.com/items?itemName=hancel.serialport-helper), to access Serial Monitor

#### Collaboration Extensions

- [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)

#### Markdown Extensions

- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint), looks at your markdown (`.md`) files with strict rules.
- [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode), has a shortcut to automatically format your markdown (`.md`) document.

#### Themes

- [Dracula](https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula)
- [Abyss] (Need to add link)
- [Ariake Dark](https://marketplace.visualstudio.com/items?itemName=wart.ariake-dark)
- [SynthWave '84](https://marketplace.visualstudio.com/items?itemName=RobbOwen.synthwave-vscode) (Glow doesn't work without Admin access ☹)

#### Miscellaneous Extensions

- [git-autoconfig](https://marketplace.visualstudio.com/items?itemName=shyykoserhiy.git-autoconfig), for working with multiple accounts on the same device.
- [Five Server](https://marketplace.visualstudio.com/items?itemName=yandeu.five-server), for live web hosting previews.
- [Markdown Converter](https://marketplace.visualstudio.com/items?itemName=manuth.markdown-converter), aptly named.

### Python Installation

So, you've installed the VSCode _extensions_, but it's asking you to install the Python _language_.

Go to [this website](https://www.python.org/downloads/) and download the latest version. Open the executable.

Uncheck the box that says "install for all users", located near the bottom of the installer window. Now, click the first arrow from the top (of the window) and install Python for your account.

On your Python (`.py`) file, there should now be a green triangle in the upper right corner. Clicking it runs your code.

If you do that, and...

It runs perfectly -> Good! Have fun.

It gives you an error message in white text -> Likely means something is wrong with your code. Double check that.

[Maybe unneeded]

It gives you an error in red text -> VSCode may not be able to find your python installation. Keep reading below

#### The Case of the Missing Python Installation

With your python (`.py`) file open, look at the bottom of the VSCode window.

TODO:

`C:/Users/hheisig51/AppData/Local/Programs/Python/Python310/python.exe`

[/maybe uneeded]

### Keyboard Shorcuts

TODO: PLACEHOLDER FOR KEYBOARD SHORTCUTS

### Comprehension

Just checking if you're reading this ;)

Tell me the words "Pineapple Tango" if you've made it this far.

## Markdown

Follow the [advice of John Gruber](https://daringfireball.net/projects/markdown/basics), the person who made Markdown back in 2004.

## Reminder

"Type it in, Google’s your friend bruh" - Jay-Z, "Drug Dealers Anonymous." 2016

## About

This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit [http://creativecommons.org/licenses/by-sa/4.0/](http://creativecommons.org/licenses/by-sa/4.0/) or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
