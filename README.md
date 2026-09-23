# icewm-dump
my icewm themes dump so i can clone it later

## maybe important
yes, there are my personal wallpapers, if youre going to use these themes/templates, you should replace your own wallpaper with the same name.
example, if inside "Vostro" folder there is a "wallpaper.jpg" you must delete it, replace it with the same name and file extension, and then run the command

```bash
icewmbg
```

to reset the wallpaper and use yours instead of the one stored in RAM.

## reminder for myself
if youre cloning this to put icewm themes to your computer too and you run into issues you can simply type

```bash
mkdir -p ~/.icewm/
```

and then

```bash
mkdir -p ~/.icewm/themes
```

and you should be able to drag all the themes to the directory

# switching persistent wallpapers in icewm
to switch and add persistent wallpapers everytime you log in icewm, you must type in the terminal

```bash
vim ~/.icewm/preferences
```

then add the following line

```text
DesktopBackgroundScaled=1
DesktopBackgroundImage = "~/path/to/wallpaper.jpg"
```

to reset and add your new wallpaper, you can simply use the same command,

```bash
icewmbg
```
