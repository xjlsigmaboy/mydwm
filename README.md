### Installing dependencies
```
sudo pacman -S libxinerama libxft
```
### Compiling and configuring
If you will edit config.def.h delete config.h before compiling!!!!
```
sudo make clean install
```
### Fonts
Copy the content of fonts folder to /usr/share/fonts/TTF before compiling!!!
```
cd fonts
cp * /usr/share/fonts/TTF
