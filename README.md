# Sol_1
## GUIDE
### PRE-INSTALLATIONS:
* Install i3:
	```
	$ sudo dnf install i3	
	```

* Download i3-keyboard-layout:

	```
	$ git clone https://github.com/porras/i3-keyboard-layout
	```
* Install picom:
	```
	$ sudo dnf install picom
	```
* Install polybar:
	```
	$ sudo dnf install polybar
	```
* Install rofi:
	```
	$ sudo dnf install rofi
	```
* Download rofi-themes/adi1090x:
	```
	$ git clone --depth=1 https://github.com/adi1090x/rofi.git
	$ cd rofi
	$ chmod +x setup.sh
	$ ./setup.sh	
	```

* Install pactl:
	```
	$ sudo dnf install pactl
	```
 
* Fonts:
	- Install FontAwesome & copy fontlar to the fonts directory:
		```
		$ sudo dnf install fontawesome-fonts.noarch
		$ sudo cp fontlar/* /usr/share/fonts/
		```
	​	
					
### INSTALLATION:

* Copy .config/i3 to .config
```
$ cp .config/i3 .config
```
	
* Copy .config/polybar to .config
```
$ cp .config/polybar to .config


```
