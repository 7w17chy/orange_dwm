#                                          _                    
#   ___  _ __ __ _ _ __   __ _  ___     __| |_      ___ __ ___  
#  / _ \| '__/ _` | '_ \ / _` |/ _ \   / _` \ \ /\ / / '_ ` _ \ 
# | (_) | | | (_| | | | | (_| |  __/  | (_| |\ V  V /| | | | | |
#  \___/|_|  \__,_|_| |_|\__, |\___|___\__,_| \_/\_/ |_| |_| |_|
#                        |___/    |_____|                       

Well, not everything is themed orange, but the borders of the focused window and the bar at the top are :D

Since people asked for my config files after posting this:

![](The original Reddit post)[screenshot.png]

on /r/unixporn, I decided to tidy them up (they aren't really, sorry) and post them here.
Huge thanks to all of those countless <a href="https://suckless.org">suckless</a> people who made dwm possible.

# Installation:
It should work right out of the box:
```
git clone https://github.com/RealAngelaMerkel/orange_dwm.git
cd orange_dwm
sudo make install clean
```
Take a look into config.mk if you're not on Linux, on FreeBSD for example, the
include directories are not correct. Just as a quick reminder :D

If you're interested in the font used in the screenshot; it's called 'Input Mono Narrow':
<a href="https://input.fontbureau.com/">Input: Fonts for Code</a>
Just follow the steps in INSTALL.txt and you should be just fine :D

# Also included
* tmux.conf -> in case you don't know: tmux can be really... it can be quite a
challenge.
* Do you want to see the vimrc too?

# Last words
If you encounter problems or have any recommendations, feel free to open an issue
or pull request :D
