# LightDM Obscura

Inspired by `lightdm-evo`.

## Requirements
- [lightdm-webkit2-greeter (aur/lightdm-webkit2-greeter)](https://github.com/Antergos/lightdm-webkit2-greeter)

## Installation
```
git clone https://github.com/ashutoshchettri/lightdm-webkit2-obscura obscura
sudo cp -r obscura /usr/share/lightdm-webkit/themes/obscura
```

## Changing theme
```
sudo nano /etc/lightdm/lightdm.conf
```
And find greeter-session and add lightdm-webkit2-greeter, Eg :-

```
greeter-session=lightdm-webkit2-greeter
```
Then save it and close and go to /etc/lightdm/lightdm-webkit2-greeter.conf

```
sudo nano /etc/lightdm/lightdm-webkit2-greeter.conf
```

And in webkit_theme, change it to obscura
```
webkit_theme = obscura
```
## Credit
- [AlphaNecron](https://github.com/AlphaNecron)


