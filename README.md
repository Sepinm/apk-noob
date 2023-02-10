# APK-NOOB

## What
- A very simple shell script.
- Simplifies APK CLI-usage for new users.
- Please refer to official documentation and help <code>apk --help</code> should you wish to have deeper understanding of APK.

## Why
- Thought to brush up my shell scripting skills for the heck of it.
- Installed PostmarketOS with Gnome Shell and there was no GUI for package management so I decided to implement a slightly simpler version of APK usage for new users of Alpine.

## How to use
1. Copy the repo and add to ~/.local/bin
    - <code>mkdir ~/.local/bin</code>
    - <code>cd ~/.local/bin && git clone git@github.com:Sepinm/apk-noob.git</code>
	- <code>sudo chmod +x ~/.local/bin/apk-noob</code>
2. Should run out of the box with command <code>apk-noob</code>

## Umm, actually, it fails to work
1. Try moving all the things like <code>mv ~/.local/bin/apk-noob/* ~/.local/bin/</code> 
2. Check the code (I'm not perfect at these things by any means)
3. Read some forums about shell scripts and see if you can fix it