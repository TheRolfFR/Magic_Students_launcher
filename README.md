<div align="center">
    <img src="https://raw.githubusercontent.com/TheRolfFR/Magic_Students/master/img/icons/icon_64x64.png" width="200" style="image-rendering: crisp-edges; image-rendering: pixelated;">
    <h1><font color="#2979ff">Magic Student Launcher</font></h1>
    <p><font>Dungeon rogue-like made with Java and Slick2D library - Academic project</p>
    <a href="https://github.com/TheRolfFR/Magic_Students"><img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/TheRolfFR/Magic_Students.svg"></a>
    <a href="https://github.com/TheRolfFR/Magic_Students/graphs/contributors"><img alt="contributors" src="https://img.shields.io/github/contributors/TheRolfFR/Magic_Students.svg"></a>
    <a href="https://github.com/TheRolfFR/Magic_Students/blob/master/LICENSE.md"><img alt="license" src="https://img.shields.io/badge/license-NPOSL--3.0-3DA639.svg"></a>
</div>


# The code

The whole project code is available here :<br>
[https://github.com/TheRolfFR/Magic_Students](https://github.com/TheRolfFR/Magic_Students)

# Downloads

- Windows/Linux/MacOS executable JAR : [Magic_Students_win.jar](final/Magic_Students.jar)
- Windows executable : [Magic_Students.exe](windows/Magic_Students.exe)
- Mac App bundle : [Magic_Students.zip](mac/Magic_Students.zip)
- Linux shell : [Magic_Students.sh](linux/Magic_Students.sh)

# Screenshots
![Screenshot](https://raw.githubusercontent.com/TheRolfFR/Magic_Students/master/img/screenshot.png)

# Keys
![Keys](https://raw.githubusercontent.com/TheRolfFR/Magic_Students/master/img/keys.png)

# Build instructions

**!!! DOWNLOAD, INSTALL jarsplice here : http://ninjacave.com/jarsplice#Download !!!**

Double-click to launch the jarsplice executable jar.

## First step : add the jar

1. Click the **1) ADD JARS** button
1. Click the Add Jar(s) button
1. Select the built jar with Intellij IDEA and hit the **Add** Button

## Second step : add the natives

Natives are complementary libs needed to run on certains platform

1. Click the **2) ADD NATIVES** button
1. Click the Add Natives(s) button
1. Select the natives for the wanted platform *(can be found in lib/lwjgl-2.9.3/native folder of the [Magic Students](https://github.com/TheRolfFR/Magic_Students) root location)* and hit the **Add** Button

## Third step : Enter main class

1. Click the **3) MAIN CLASS** button
1. Enter the Magic Students main class location in the field : **Main.MainClass**

## Fourth step : generate the jar

1. Click the **4) MAIN CLASS** button
1. Click the **Create Fat Jar** button
1. Choose your location in the file dialog with your desired name *(it doesn't matter)* and hit the **Save** Button
1. Wait and you should see A success dialog appearing

## Fifth step : generate the exe *(or else depending the desired platform)*

1. Click the **EXTRA (WINDOWS.EXE )** button
1. Click the **Create Windows EXE file** button
1. Choose your location in the file dialog with your desired name *(this one matters)* and hit the **Save** Button

# Add an icon instructions

**!!! Download and install Resource Haker here : http://angusj.com/resourcehacker/#download !!!**

Open ResourceHacker.exe

## Add an Image Resource
1. Click the Open item in the File menu or press **CTRL + O**
1. Select the desired exe in the file dialog and hit the submit button
3. Click the "flower image icon" button in the toolbar, a dialog window will open
4. Click the **Select File ...** button
5. Select the desired Icon file
6. Resource Hacker will detect automatically that it is the icon and fill the other fields for you
7. Just click the **Add Resource** button to add the resource
8. Eventually click the "floppy disk" button to save your file
9. Select your location and hit the submit button
