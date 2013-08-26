Phosphene_win
=============
I'm on vacation for 2 weeks, so there won't be any updates... I'm not abandoning this project though!

A windows port of hdni's amazing Gnome theme: https://github.com/hdni/Phosphene

Still WIP, at the moment I there is not much besides a TrueTransparency theme and an almost finished foobar theme.

TrueTransparency
----------------
![screenshot](http://a.pomf.se/1Xc3.gif)

Download and install TT from here: http://dl.dropbox.com/u/7100381/TrueTransparency.zip, drag and drop the "truetransparency"
folder into `C:\Program Files\`.

Copy all the files from `Kamiru-/Phosphene/TrueTransparency/` to `C:\Program Files\TrueTransparency\TrueTransparency x86` AND `C:\Program Files\TrueTransparency\TrueTransparency x64`.

Start both the 32 bit and 64 bit version of TrueTransparency.exe and right click on the icons in the tray, select the skin Phosphene_TT.

WINDOWS 7: Download http://www.angusj.com/resourcehacker/ and open `C:\Windows\Resources\Themes\aero\Shell\NormalColor\shellstyle.dll` with it, go to `UIFILE > 1 > 1033` and search (ctrl+f) for `<style resid="FolderBandStyle">`. Add the following line under it: `<Element padding="rect(0rp,0rp,0rp,-44rp)"/>`. Press the "Compile Script" button, and save the file, you may need to take ownership of shellstyle.dll.

WINDOWS 8: Use http://winaero.com/comment.php?comment.news.20 to disable ribbon. You can also disable the organize bar
by following the previous Wndows 7 step.

Foobar2000
----------------
![screenshot](http://a.pomf.se/7Bl2.png)

Install the required components and load the theme with columns UI.

Rainmeter
----------------

Load both skins, make BAR click through and make BUTTONS on top and not draggable.
