# WolfLoader

WolfLoader is a custom BakkesMod plugin designed to be used in Rocket League this will allow you to load custom car and replace the current car mesh (visually) with the custom car that has been selected 

WolfLoader is only allowed in Freeplay and Workshop maps in order to comply with Psyonix/BakkesMod TOS like how AlphaConsole is doing their custom cars 

The Plugin will come preinstalled with cars from the following platforms (Switch, Box, Station)

(Switch)
Muffin Gunship (Orange)
Muffin Gunship (Blue)
Calzone (Red)
Calzone (Green)

(Box)
Hogstick Truck 
Gears Car

(Station)
Tooth Truck

![Cars](https://github.com/TechoGit/WolfLoader/blob/main/cars.png?raw=true)

# How to Download WolfLoader and Install

If you would like to download WolfLoader for your BakkesMod install head to the releases tab on Github (Right hand side of your screen) once there you should see a rar file, download it inside you'll
find the following content: the plugin itself (.dll) file and the car files inside customcars folder

Open up the .exe file this will automatically attempt to install the plugin to the bakkesmod folder and copy the customcars to rocket league folder in order to work (Make sure your rocket league is closed
beforehand)

Once the exe says it has completed install you may close the command prompt window and launch Rocket League then press F2 for BakkesMod and head to the plugins tab you should see WolfLoader at the bottom
of the plugin list, head into Freeplay then go to WolfLoader select one of the cars in the list and you should see your current car mesh replaced with the custom car one Enjoy :)

Make sure you have goal reset off in BakkesMod / Freeplay if you score a goal the custom car will refresh and you'll need to reapply it also i advise against applying multiple meshes in one session it will most likely result in crashing as i've mentioned in the Known Issues section










# 1. I can't launch the installer exe cause windows defender think its a virus / 2. you don't have permissions to launch exe files from the internet / 3. i don't trust you 

1. You need to turn off your anti virus and allow it as program follow the steps below if you can't do that

2. You need to follow the steps below for a manual install

3. I'll publish the code for the installer when i've cleaned it up a bit in this repo, if you want can take a look at the virustotal report
https://www.virustotal.com/gui/file/0e983ff4a3279b060007779ebf3984b6073e66241e0f727f52b57ab373460df0?nocache=1
5/72 right now its at and they're just false postives its cause its accessing the reg to find the steam/epic location probably you can see what stuff its calling 

if that doesn't put your mind at ease then sorry you won't be able to install WolfLoader

If for some reason you can't launch the exe file due to your windows permissions or it gets detected as a virus cause it access the registery to find the location of the steam dir

You'll need to do a manual install

You need to locate your bakkesmod folder which you can do easily by doing

![Cars4](https://github.com/TechoGit/WolfLoader/blob/main/bakkesfolder.png?raw=true) 

Then you should see a folder called "Plugins" open that then drag or copy and paste the WolfLoader.dll file inside there 

Then you need to locate your Rocket League folder Its different on epic and steam but the default location for both is

C:\Program Files (x86)\Steam\steamapps\common\rocketleague  for Steam
C:\Program Files\Epic Games\rocketleague for Epic

Once you've located your Rocket League folder go inside it and head to TAGame then CookedPCConsole
you should see a mod folder if you've used some bakkesmod plugins previously inside that but if you don't
create a mods folder inside the CookedPCConsole folder like how i've shown below

![Cars5](https://github.com/TechoGit/WolfLoader/blob/main/insidemodsfolder.png?raw=true)

Once you've found the mods folder or created it you want to open it up then copy and paste or drag CustomCar folder from The WolfLoader folder inside your Downloads Folder
then put it inside and that should be you done inside the CustomCar folder it should look like this

![Cars6](https://github.com/TechoGit/WolfLoader/blob/main/insidecarsfolder.png?raw=true)

Also don't upload these cars to Alphaconsole's own website Alphaconsole's custom car feature is locked behind patreon wall by default. so it would look like Alphaconsole is charging to use Psyonix Assests when they're free 

So i don't want anything bad to happen to Alphaconsole so please don't do that 

# Known Issues
There is a small chance (1%) your game may crash if you alt tab via freeplay when the BakkesMod window is open 

Hogstick Truck spikes don't stick to the Truck and float i believe this is cause there is something wrong with the material / spikes aren't stuck to the truck properly 
I've had to recreate the spikes as i couldn't get the original ones to attach to the truck no matter what i did

![Cars2](https://github.com/TechoGit/WolfLoader/blob/main/hogstickspikes.png?raw=true)

If you load the Tooth Truck first then switch to multiple different other custom cars then you go back to the Tooth Truck, the game will crash

Calzone has a missing texture on the bottom this will be fixed in a later release isn't priority right now

![Cars3](https://github.com/TechoGit/WolfLoader/blob/main/calzonemissing.png?raw=true) 

Some Cars will crash your game if you use a F-150 for example your game will crash when trying to replace the mesh with a custom one i believe this is cause they're different materials rather than a single one

I don't have a list of said cars that will crash the game with the meshes as they're too many cars to go through without some method of automating testing

If people fill out the github issues with a car that crashes, i'll make a google document with the list of cars that crash and work out which ones do but that will take some time

# Credits and Name

Alot of people have helped me make this plugin a reality so i would like to give them credit where credit is due

spiritvod over on the gildor forums 

ArcadeGamer1929 for helping out on accessing the box cars from that console 

Soul, Emii pointed me in the right direction roughly when it came to coding

WolfLoader name comes from the character called Silver Wolf in Honkai Star Rail thats where i got the idea of the name for, i was considering like CustomCarLoader or ConsoleCars but i thought WolfLoader sounded cooler 

