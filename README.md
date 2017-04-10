# KLH-Threat-Meter-17.35
KTM 17.35, version from [DuduSandsten](https://nirklars.wordpress.com/wow/addons-rarecustom-addons-by-other-authors/).
KLHThreatMeter monitors and records your threat, and will list your threat in a table with other members of your party or raid group who are using the mod. Most class talents, abilities, and items that cause or modify threat are taken into account. There is a table for your personal threat contribution, broken into specific categories such as white damage, healing, mana gain, etc, and specific abilities such as Sunder Armor and Taunt. The mod records your own threat and sends updates into a shared channel. Other players in your raid who are also using the mod will pick up the messages and see you in their raid threat window. 

## Screenshot
![ktm_17 35](https://cloud.githubusercontent.com/assets/24671466/24852270/2cfe9bba-1dd7-11e7-82fb-a1c60dea5501.png)

## Installation
1. Close any instance of WoW
2. Download **[KTM 17.35 Zip file](https://github.com/Linae-Kronos/KLH-Threat-Meter-17.35/archive/master.zip)**
3. Extract the zip file wherever you want
4. Copy the folders "KLHPerformanceMonitor" & "KLHThreatMeter" to Wow_Folder\Interface\AddOns
5. This is what you should have on character selection screen :

![ktm_charselect](https://cloud.githubusercontent.com/assets/24671466/24852759/f557c694-1dd8-11e7-9539-910080ec72e8.png)

## Recommended additional addon

[KTMAutoHider](https://github.com/Linae-Kronos/KTMAutoHider) : will automatically hide KTM when not in raid or party

## Documentation & Tips
The following files in folder "KLHThreatMeter\Readme" have some random tips and documentation :
- Advanced Raid Commands.txt : raid officers / leaders should read this
- Localisation Notes.txt :	explanation of the localisation implementation
- Development - My To Do List.txt : stuff i'm working on, or about to work on
- How You Can Help!.txt: adding new items / abilities / bosses to the mod.
- Implementation Notes.txt : description of how the code works for addon authors

## Commands
```
/ktm                  List of useful commands
/ktm version query    Check versions
/ktm version notify   Notify people with older version
/ktm mastertarget     Sets the master target
```

## Credits
[Kenco](https://mods.curse.com/legacy/interviews/world-of-warcraft/13873-interview-with-kenco-klhthreatmeter) for the original addon
[Sandsten](https://nirklars.wordpress.com) for the KTM version
[Shagu](https://github.com/shagu/pfUI) for the Readme format