(abandoned until further notice)

**Preview/Cheatsheet:** the png file

(Partly implemented in the Linux version of [my keyboard layout.](https://github.com/theNizo/DvorakByNizo-German))

# Nizo's ultimate Keyboard
Inspired by [Vim](https://en.wikipedia.org/wiki/Vim_(text_editor)), 40% Keyboards like the [MiniVan](https://i.ytimg.com/vi/g6bKhcrlnn8/maxresdefault.jpg) (buy it [here](https://thevankeyboards.com/)) and the [Neo Layout](https://www.neo-layout.org/).

This is an AutoHotkey Script I use.

**Requirements:** [AutoHotkey](https://www.autohotkey.com/)


* **For Dvorak by Nizo:** this is the original script, written for use on [my custom layout](https://github.com/theNizo/DvorakByNizo-German), which is a german [dvorak](https://en.wikipedia.org/wiki/Dvorak_Simplified_Keyboard) version. / Das ist das originale Skript, welches für [mein Eigenes Layout](https://github.com/theNizo/DvorakByNizo-German) geschrieben wurde.
* **For US Dvorak:** This is made to be used with the standard US Dvorak keyboard
* **For QWERTY:** Written for QWERTY.
* **For QWERTZ:** Made for QWERTZ (German version) / Für QWERTZ

The scripts might have some bugs (they rarely happen). Reloading normally fixes everything. / Die Skripte könnten den ein oder anderen Fehler beinhalten (treten kaum auf). Neu laden hilft meistens.

**Only the first one is tested. I ported it by changing the keys, so the oher files should work. If they don't, please contact me and I'll fix it. / Nur das erste ist wirklich getestet. Die anderen wurden nur gestartet, um zu schauen, ob sie überhaupt funktionieren. Wenn Fehler auftreten, bitte mich kontaktieren.**

# English

### But why?
For less finger movement and higher speed. For example, It's much quicker to use the backspace hotkey than moving my hand to the backspace button.

## Install
Deutscher Teil im Anschluss

1. Download the file for the preferred layout
2. place it somewhere
3. Edit if you don't like something (most of the relevant stuff is described. If not, please let me know.)
4. Put it into Autostart (In Windows: Win+R, type "shell:startup", enter and create a new shortcut to the file) Make sure the keyboard which the script is written for is normally selected. Otherwise, some hotkeys will not work until you switch to it and reload the script.
5. Enjoy

## Issues

**How can it activate CapsLock?** Caps+RShift

**The spaces are inserted after I release the space bar** This is necessary for some shortcuts. If it's really bothering, edit the file. Go down to the section with the Space Bar Hotkeys and delete it/turn it into a comment (put /* before and */ after it)

**I cant deactivate NumLock** Numlock is something that bothered me all the time, because it is usually turned off. With the script, it's forced to always be on. If you don't want that, remove the second line (SetNumLockState) or put a ; in front.

# German

### Aber warum?
Damit sich die Finger weniger herumbewegen und weil es schnelller ist. Ich brauch viel kürzer, den Backspace hotkey zu verwenden, als meine Hand zur tatsächlichen Taste zu bewegen.

## Installation

1. Datei für gewünschtes Layout herunterladen
2. Irgendwo hin speichern
3. Bearbeiten, wenn etwas nicht passt (der großteil der wichtigen Sachen ist beschrieben. Wenn nicht, bitte mich darauf aufmerksam machen.)
4. Zu Autostart hinzufügen (In Windows: Win+R, "shell:startup" eingen, Enter, Shortcut erstellen). Bitte sicherstellen, dass das Layout, für das das Skript gedacht ist, standardmäßig ausgewählt ist, sonst funktionieren ein paar Hotkeys nicht, bis man zu dem Layout wechselt und das Skript neu ladet.
5. Es toll finden (oder auch nicht, wer weiß)

## Probleme

**Wie kann ich CapsLock aktivieren?** Caps+RShift

**Abstände werden erste eingefügt, wenn ich die Leertaste loslasse.** Das liegt an den Hotkeys, die mit der Leertaste funktionieren. Wenn es zu lästig ist, bitte das Skript bearbeiten, zu dam Teil mit den Space Hotkeys Scrollen und entweder rauslöschen, oder auskommentieren (/* davor und */ danach hinschreiben).

**Ich kann NumLock nicht deaktivieren** NumLock hat mich meistens genervt, weil ich das Nummernfeld nur zum Zahlen eingeben verwende, aber das standardmäßig ausgeschaltet ist. Im Skript wird es zwangsweise eingeschaltet. Wenn man das nicht will, 2. Zeile (SetNumLockState) entfernen oder auskommentieren (; davorsetzten).
