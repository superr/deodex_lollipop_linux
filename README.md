# Deodex Lollipop v1.6
# by SuperR

This tool is intended to deodex /system/app, /system/priv-app, and /system/framework in Android Lollipop.

Usage:

1. Copy the 3 above mentioned directories from your odexed ROM into the /system directory at the root of this tool.
2. run "deodex_lollipop" from it's location in terminal 

Example:

In your terminal, type the following where "/home/user/location/" is the directory where the script lives:

cd /home/user/location/
./deodex_lollipop

Dependencies:

Java 7 (or higher)
p7zip-full (to run 7za commands)
