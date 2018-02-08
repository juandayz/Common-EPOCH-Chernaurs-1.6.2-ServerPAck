******************************CONFIGS.***

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
