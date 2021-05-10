# noob-hacker
Location tracker
hi guys 
im a noob hacker
welcome to by blog
today i will show you how to track location

Requirements

Termux
Download Link
Hacker's Keyboard
Download Link

IPGeoLocation GitHub
https://github.com/maldevel/IPGeoLocation.git
Difficulty
Intermediate


procedure
1: First we need to setup Android Termux
Type command 
pkg update && pkg uograde && pkg install python && pkg install python2 
and press Enter.
2.png

2: Now visit the GitHub Link
Link is given in Requirement copy the clone link as shown in this screenshot
1.png
Type the command pkg install git and press Enter.
git.png
3: Now we need to clone the IPGeoLocation in Termux.
Type command git clone (GitHub Link). Here the (GitHub Link) is the Git link that you copy in step-2 it may be like this git clone https://github.com/maldevel/IPGeoLocation.git and press Enter. Wait until it Finished.
gitr clone.png

Now type command ls you will see a file requirements.txt. These requirements are essential for this script. You can fulfilled all requirements by executing the command pip install -r requirements.txt and press Enter.
pip.png

-Now change the permission Type command chmod +x ipgeolocation.py and press Enter.
chmod.png

4: How to use this script to trace the IPLocation
Type command python ipgeolocation.py -m. This will give your IP Location
own.png
my loc.png
For other IP Locations type command python ipgeolocation.py -t (Target IP) and press Enter. Here (Target IP) is IP address you want to Locate.
5: Example
I give an Example to use my own IP Address
-python ipgeolocation.py -t 121.16.2.19 and press Enter. I didn't show my exact IP in command. You must put the exact IP you want to locate.
-t.png
Screenshot_20180126-155131.png
6: Where the Google Map Link?
You can find the Google map link at the end of data as shown in this screenshot. You can simple Google it and get the Location
g map.png
