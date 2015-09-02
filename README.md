Easy Cygwin installation guide!
===============================

<img src="https://dl.dropboxusercontent.com/u/1042234/blog/images/posts/2012-07-06/tweaked-ui.png" style="width: 300px; height:200px;"/>
<img src="http://s009.radikal.ru/i309/1011/7c/f2ead4cc6eb3.png" style="width: 300px; height:200px;"/>
<img src="https://pbs.twimg.com/media/A5mIaIBCEAEOniT.png" style="width: 300px; height:200px;"/>

Why Cygwin
----------
Cygwin is a Unix console container for windows.
If you are used to work with Git-Bash (MinGW), it is way more powerful!
The combination on Cygwin and ConEmu will provide you with a fast, easy tool to work,
plus it support, screen splitting, tabs, keyboard shortcuts, and it can be personalized to fit your needs.


How to install Cygwin?
-----------------------

first, head over to <http://cygwin.com/install.html> and download the latest version of cygwin.

run it, and when you see this screen:

**make sure to install `svn`** ! you will need it later to install `apt-cyg`

beside that, add packages you need, like `git`, `python`, `wget`, `kdiff` etc.

<img src="http://xahlee.info/mswin/i/Cygwin_Setup_dialogue.png" style="width: 400px;"/>


- - -

Install apt-cyg
-------------------

apt-cyg is a command line tool to install new software. much like `apt-get`, `brew`, `mac-ports` or `yum`.
got to <https://github.com/transcode-open/apt-cyg/> and follow the instructions.

to use it, open cygwin and type `apt-cyg install [your package name]`

- - -

Install con-emu
---------------
ConEmu is a console container for the Cygwin, it enables you to have tabs, shortcuts and what not!
download and install it from here <https://conemu.github.io/>


#### Connecting ConEmu to Cygwin
to connect ConEmu to you Cygwin, go to settings (win+alt+p) > tasks > and hit the `+` sign.
name the task `Cygwin` and the in the commands box type `C:\cygwin\Cygwin.bat`.

now, choose `startup` in the left menu, choose `specified named task` and choose `cygwin`.

done!

#### Assigning a keyboard shortcut
I suggest assigning a keyboard shortcut to the console, it can be done in `Keys & Macro` and my suggestion is to assign `Ctrl+Shift+~` to `Minimize/Restore`.


Personalize your console
------------------------

Here are some usefull links:

* <http://whiletruecode.com/post/get-a-transparent-quake-style-windows-console-with-conemu>
* <http://www.howtogeek.com/130056/the-command-prompt-is-outdated-2-command-prompt-replacements-for-windows/>
