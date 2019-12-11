# qtcreator-themes
A few themes for QtCreator

## Dark
-------
![Dark (cpp)](./screenshots/dark-cpp.png?raw=true "Dark (cpp)")


![Dark (qml)](./screenshots/dark-qml.png?raw=true "Dark (qml)")

## Light
-------
![Light (cpp)](./screenshots/light-cpp.png?raw=true "Light (cpp)")


![Light (qml)](./screenshots/light-qml.png?raw=true "Light (qml)")
-------
## Installation
-------
Commands for finding your system qtcreator installed themes,
```
    find /usr/share -type f -name *.xml|grep qtcreator
    find /usr/share -type f -name *.creatortheme|grep qtcreator
```

### Editor themes installation

```
    cp styles/*.xml ~/.config/QtProject/qtcreator/styles/
    cp styles/*.xml /path-to-qt-bin/Tools/QtCreator/share/qtcreator/styles/
    cp styles/*.xml "/path-to-qt-bin/Tools/Preview/Qt Creator <version>/share/qtcreator/styles/"
    sudo cp styles/*.xml /usr/share/qtcreator/styles/
```
----
### QtCreator dark themes
If you want qtcreator dark theme, pick one of them depends on the sort your installation.
```
    cp themes/*.creatortheme ~/.config/QtProject/qtcreator/themes/
    cp themes/*.creatortheme /path-to-qt-bin/Tools/QtCreator/share/qtcreator/themes/
    cp themes/*.creatortheme "/path-to-qt-bin/Tools/Preview/Qt Creator <version>/share/qtcreator/themes/"
    sudo cp themes/*.creatortheme /usr/share/qtcreator/themes/
```
Also, for dark themes you could change TODO panel color scheme by replacing `[TodoPlugin]` section in 
```
    vim ~/.config/QtProject/QtCreator.ini
```
----
file with content of the `todo-dark-colors` file.

## Compatibility
-------------

For Qt Creator 3.0 and below, remove line which starts with `<style name="PrimitiveType"` in `.xml`.
