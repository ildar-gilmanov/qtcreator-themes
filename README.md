# qtcreator-themes
Some themes for QtCreator

Dark
----
![Dark (cpp)](./screenshots/dark-cpp.png?raw=true "Dark (cpp)")


![Dark (qml)](./screenshots/dark-qml.png?raw=true "Dark (qml)")

Light
-------
![Light (cpp)](./screenshots/light-cpp.png?raw=true "Light (cpp)")


![Light (qml)](./screenshots/light-qml.png?raw=true "Light (qml)")

Install
--------

Place `styles/*.xml` files into `~/.config/QtProject/qtcreator/styles/` folder, and if you want dark theme, place `themes/ildar-dark.creatortheme` and `themes/ildar-dark-x.creatortheme` file into `~/.config/QtProject/qtcreator/themes/` folder.  
Also, for dark themes you could change TODO panel color scheme by replacing `[TodoPlugin]` section in `~/.config/QtProject/QtCreator.ini` file with content of the `todo-dark-colors` file.

Compatibility
-------------

For Qt Creator 3.0 and below, remove line which starts with `<style name="PrimitiveType"` in `.xml`.

