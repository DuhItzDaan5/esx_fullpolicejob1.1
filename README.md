esx_policejob
I made 2 configs one in English and an another one in Dutch -There are two sql. files an English one with UK ranks and another one with Dutch ranks
This is the original version of the policejob: https://github.com/ESX-Org/esx_policejob/archive/master.zip

EUP
-I put my uniforms on EUP however these are Dutch uniforms so it may look weird if you have other uniforms this can be customized in the config.lua

Requirements
esx_billing
esx_society
esx_datastore
esx_identity
esx_license
qalle-jail
esx_CommunityService
Download & Installation
You need to download everything from requirements otherwise it will not work
Manually
Download https://github.com/ESX-Org/esx_policejob/archive/master.zip
Put it in the [esx] directory
Installation
Import esx_policejob(nl).sql or esx_policejob(en) in your database
Add this in your server.cfg :
start esx_policejob
If you want player management you have to set Config.EnablePlayerManagement to true in config.lua
If you want armory management you have to set Config.EnableArmoryManagement to true in config.lua
If you want license management you have to set Config.EnableLicenses to true in config.lua
Credits
Moddinq#1883
DuhItzDaan#4407
