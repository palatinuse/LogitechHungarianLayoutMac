# Hungarian Layout of Logitech External Keyboards for Mac

## Motivation:

* Have you ever wanted to use a third-party keyboard with your Mac? 
* Do you need a non-English layout?
* Your keyboard of choice is not Mac-compatible?

Than most probably you will end up having level 3 characters (e.g. @, \, ...) misbehaving: your Mac most probably won't recognize your keyboard's level 3 characters, but rather will interpret them as a Mac Keyboard's level 3 characters. Ouch... 

## Story:

This is exactly what happened to me when I bought a Logitech K330 in Hungarian layout, and plugged (the keyboard's wireless adapter) into my MacBook Pro. The accented characters were correctly recognized, but all level 3 characters were misinterpreted. The characters appearing on the screen were different than on the keyboard.

Fortunatelly, there is a neat software, [Karabiner](https://pqrs.org/osx/karabiner), which allows you among others to remap any key(combination) of your external keyboard. The difficulty of the task is figuring out the correspondance of the external keyboard's keys and those on the Mac's English Keyboard. This can be done using the "Show keyboard viewer" function of the Keyboard Layout menu.

After some fiddling around with my external keyboard, the keyboard viewer application, and sneaking on my Mac's English keyboard I was able to create the mappings for the most important special characters, i.e. those used in programming. The result is the Hungarian keymapping config file for Logitech external keyboards used with a Mac to be used in [Karabiner](https://pqrs.org/osx/karabiner).

## Usage:

Install [Karabiner](https://pqrs.org/osx/karabiner), and follow instructions on [How to add your own settings] (https://pqrs.org/osx/karabiner/document.html.en#privatexml). Overwrite the private.xml file with the one in this [repository](private.xml). Enjoy!
