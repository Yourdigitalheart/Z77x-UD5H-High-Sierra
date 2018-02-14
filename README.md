# Z77x-UD5H-High-Sierra
'sudo /Applications/Install\ OS\ X\ Yosemite.app/Contents/Resources/createinstallmedia --volume /Volumes/USB --applicationpath /Applications/Install\ OS\ X\ Yosemite.app --no interaction'

Have a USB keyboard/mouse handy for installation
Disconnect all drives except Mac boot drive
Boot from Unibeast 8.1.0 or clover
In options remove disable_nv=0 and add -v to see boot process
Follow on screen instructions, installer reboots after just a few minutes
On next boot, set same options as above
Select macOS install from "partition title", will show black screen with Installing, about 11 minutes remaining.
Download and install Multibeast -> quick start -> UEFI mode defaults
Audio > Realtek ALCxxx > ALC898
Network > Atheros
Network > Intel > AppleIntelE1000e
Only other thing is when booting I need to select "drop MATS" every time, but otherwise everything seems to work fantastic!