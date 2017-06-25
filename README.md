# Zesty-Zapus Customization

## Conky

#### Installing
```
sudo apt-get install conky-all lm-sensors
sudo sensors-detect
cd && wget -O flair-c.sh http://drive.noobslab.com/data/conky/flair/flair-conky.sh
cd && chmod +x flair-c.sh && ./flair-c.sh
```
After installation logout and login back.

#### Uninstalling
```
cd && wget -O uninstall-flair-c.sh http://drive.noobslab.com/data/conky/flair/uninstall-flair-conky.sh
chmod +x uninstall-flair-c.sh && ./uninstall-flair-c.sh
```

## Plank

#### Installing
```
sudo add-apt-repository ppa:ricotz/docky
sudo apt-get update
sudo apt-get install plank
```

#### Configuring
```
vim ~/.config/plank/dock1/settings
```

## Gnome Tweak Tool

#### Installing
```
sudo apt-get install gnome-tweak-tool
```
install the following extentions :
- Applications Menu
- Coverflow alternative tab

   If having problem intalling the above extentions install thefollowing
   ```
   sudo apt-get install gir1.2-gmenu-3.0 libgnome-menu-3-0
   ```

## ADAPTA theme
#### Installing

```
sudo add-apt-repository ppa:tista/adapta
sudo apt-get update
sudo apt install adapta-gtk-them
```
