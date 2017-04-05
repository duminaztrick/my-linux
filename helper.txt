WIKI

TODO
system-wide changelog

Useful Command
setxkbmap fr # changing keyboard layout for a session
smbclient //10.0.1.10/homeshare -U francist
youtube-dl -x --audio-quality 0 --audio-format mp3 'URL'
find /home/francist -name search -type f -print0
mogrify -format png picturename.jpg
sudo dd if=inputfile.img of=/dev/sd? bs=4M && sync
sudo mkfs -t filesystem_type /dev/usbname
cut lsof ps sort lspci fsck md5sum set xprop env alias source

Command Debian Base Distro
dpkg
dpkg --search thefile
dpkg --install name.deb
dpkg --list
dpkg --status firefox
apt-cache search PACKAGE_NAME
sudo apt-get install --fix-broken
sudo apt-get remove package
apt-cache show firefox

Fix
fix dmenu --> pacman -S dmenu
ckb not opening # start ckb-deamon via systemctl
Infinality Font for better Font Rendering
crc32 --> https://bbs.archlinux.org/viewtopic.php?id=210673https://askubuntu.com/questions/372607/how-to-create-a-bootable-ubuntu-usb-flash-drive-from-terminal#579615

DEBIAN SPECIFIC CODEC:
At this point of time, Debian is using the “libav-tools” package instead of ffmpeg in Jessie/Testing so we are going to stick with the default packages and install only some extra packages.
sudo apt-get install libavcodec-extra
sudo apt-get install gstreamer0.10-plugins-ugly gstreamer0.10-plugins-bad gstreamer0.10-fluendo-mp3 gstreamer0.10-pulseaudio
sudo apt-get install libgstreamer-perl libgstreamer-interfaces-perl
sudo apt-get install xscreensaver-gl

Pakage
detail most use app
firefox browser
	[add-on]
	stylish
	adblock
	httpseverywhere
	privacy badger
	firebug
	toggle reddit sidebar
	one tab
	color picker
	add bookmark here
	bookmark dedublicator
	[theme]
	black by madona

	[text editor]
	atom

	[terminal emulator]
	termite
	tmux
	zsh
	oh-my-zsh

	[util]
	volwheel
	[disk]
	gnome-disk disk partitioner
	pcmanfm file manager

	[app i want to learn]
	vim text editor
	qute browser
	ranger fm
	latex markdown text editor
	mutt email

	[stuff i use]
	gnome-character
	baobab
	xfce4-screenshooter/gnome-screenshot
	steam
	vlc
	virtualbox
	lxappearence gtk theme manager
	pamac
	GNOME Software
	anki flash card program
	File-roller
	dmenu finder
	deluge
	nitrogen
	arandr
	Evince pdf and more
	xprop app-info
	midnight_comander file manager
	htop
	keepassX2 password manager

	[neat stuff]
	grsync
	double-commander
	thunar
	evolution email
	game_conqueror cheat engine for linux
	gcalculator
	extcalc
	discord
	ardour 4 DAW
	audacity  audio
	lmms DAW
	mixxx dj software
	rofi finder
	compton pretty transition
	conky
	bleachbit ccleanner
	gdmap
	kodi
	obs
	libreoffice
	play on linux
	Pragha Mucic Player
	Pavucontrol
	ristretto
	feh
	retroarch emulation
	spaceFM
	sunflower
	team speaker
	youtube-dl
	yaourt
	psylock
	weechat
	wicd
	ufw
	arno-fw
	transmission-cli
	thefuck
	glances
	cmatrix
	e3 assenbly text editor
	fish --> shell
	oh my fish --> shell customization
	kvm
	qemu
	virt-manager
	parcellite : Clipboard manager
	gimp : Image editor
	gparted : Partition Manager
	network-manager-gnome
	xscreensaver
	WPS word processor
	ckb
	cmus

	[neat no name]
	bluck rename
	MIME type manager
	power manager
	printing
	image viewer
	session manager
	setting editor
	setting manager
	task manager gui htop
	cli-torrenting
	network manager
	burning cd/dvd
	calendar
	codec


Terminal App
htop --> cli monitoring
glances --> cli monitoring
tmux --> term multiplaxer
termite --> terminal emulator
zsh --> shell
oh my zsh --> shell customization
Mutt --> terminal email
fish --> shell
oh my fish --> shell customization
ranger
qutebrowser
yaourt
git
cmus
scanmem
weechat

GUI App
conky --> monitoring widget
lxapparence --> gtk theme manager
arandr --> managing screen
file-roller : Archive manager
evince : PDF reader
parcellite : Clipboard manager (I don’t use “Clipman” that is bundled with xfce4 goodies because its buggy)
qalculate : Calculator
clementie : Audio player
vlc : Video player
bleachbit : System cleaner
gimp : Image editor
shotwell : To import pictures from digital camera
gparted : Partition Manager
gnome-disk-utility : Disk Utility
gamesconqueror

Special App
arnod-firewal
ufw
virtualization:
kvm
qemu
virt-manager
pavucontrol
network-manager-gnome
Multimedia codecs
xboxdrv
firmware-linux
intel-microcode

sublime text
ckb corsair kb
steam
lm_sensors
acpi

SELF-HOSTING:
Sonerezh
bookie

Dev App
PYTHON DEV ENV:
git
build-essential
curl
wget
virtualenv

Ricing App
Font
share_tech_mono google font
roboto mono
nova mono
font-awesome

Icon
arc icons pack

GTK
adwaita-dark gtk theme
