# Common-EPOCH-Chernaurs-1.6.2-ServerPAck

MODS: 
[custom crates events],[Rubbletown event],[WAI],[DZAI],[DebugMonitor],[DeployAnything],[LogisticTow&Lift],[Remote LockUnlock Pressing T key],[Safezones],[Takeclothes],[Day Night Cycles],[Coins],[Restrict Buildings near traders cities],[Vehicles with GodMode on plotpoles],[ESSV3],[LoadingScreen],[MapMarkers],[custom ConfigVariables.sqf].

**INSTALL FOR HOSTS LIKE GTX** 

1.Open ...\@DayZ_Epoch_Server\addons\ and drop dayz_server.pbo in your \@DayZ_Epoch_Server\addons\  (remove your own first).

2.Open ...\MPMissions\ and drop DayZ_Epoch_11.Chernarus.pbo into your MPMissions folder. (remove your own first).

Done.

**INSTALL FOR Virtual machines or locals ones.** 

1.Create a fresh database...Use "epoch2018" as database name, user and pass. (you can change it later)

2.Create in C:\ a folder called epoch. (do not change the paths other way you gonna need edit all paths.)

3.Drop all content of your arma2 into C:\epoch

4.Drop all content of your arma2oa into C:\epoch  but without those folder who start with @. Example do not put @DayZ

5.Download epoch 1.6.2 client files and drop into C:\epoch\   Link: https://epochmod.com/a2dayzepoch.php

6.Drop all .Dlls provided here into C:\epoch\

7.Drop Keys folder into C:\epoch\

8.Drop MPMissions folder provided here into C:\epoch\

9.Drop @DayZ_Epoch_Server folder provided here into C:\epoch\

10.Drop DZE_Server_Config into C:\   (yes C:\ NOT! into C:\epoch\)

Done. Click on START_WITH_RESTART.bat to start your server with autorestart.


CONFIGS.

1.Change your BEC password. (C:\DZE_Server_Config\BattlEye\BEServer.cfg)
```ruby
RConPassword epoch2018
```
C:\DZE_Server_Config\BattlEye\Bec\Config\Config.cfg
```ruby
#User = epoch2018
#Password = epoch2018
```


2.Debug Monitor. (C:\epoch\MPMissions\instance_11.chernarus\scripts\debug\)

Find those lines in player_debug.sqf to entry your server name and web page.
```ruby
	_textuals = _textuals + "<t size='1.1' font='Zeppelin33' align='left' color='#FFCC00'>ServerName</t><br/><br/>";
	_textuals = _textuals + "<t size='1.1' font='Zeppelin33' align='center' color='#FFCC00'>Discord</t><br/>";
```
3.Server Configs. C:\epoch\MPMissions\DayZ_Epoch_11.Chernarus\server_options\)

Manage your server configs from :
```ruby
ConfigVariables.sqf and server_options.sqf
```
You can manage your map markers from server_markers.sqf


4.Now if u wanna change your database user and pass values. (first create a new db with the names that you want.)

A.C:\DZE_Server_Config\HiveExt.ini
```ruby
#User = epoch2018
#Password = epoch2018
```

B.C:\DZE_Server_Config\START_WITH_RESTART.bat
```ruby
set DB_USERNAME="epoch2018"
set DB_PASSWORD="epoch2018"
set DB_NAME="epoch2018"
```
