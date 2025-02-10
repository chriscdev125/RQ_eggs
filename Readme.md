# RQ_eggs
Custom eggs ARM64 for Pterodactyl.  



An Little Upgrade for thesee old eggs, Some of them work on ARM and also ARM form Oracle Free Tier  

If you want to support my work:

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/J3J2HGECS)



------------
**Right click and click save!**

✅ - Working (Normal ARM was tested on Raspberry Pi)  
❔- Not tested yet but should work  
❌ - Don't work 



## Aplication
| Service | file* | AMD64 | ARM64 | ARM Oracle | Updated | More info |
|--|--|--|--|--|--|--|
| Gogs | [egg-gogs.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/applications/egg-gogs.json) | ✅ | ✅ | ✅ | 2022-06-30 | Not ssl ready and on ARM use native ARM version

## Databases
| Service | file* | AMD64 | ARM64 | ARM Oracle | Updated | More info |
|--|--|--|--|--|--|--|
| Redis server generic | [egg-generic-redis.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/databases/egg-generic-redis.json) | ✅ | ✅ | ✅ | 2022-07-23 | supports: v5.0,6.0,6.2,7.0 |

# Game eggs

####  **General Games**
| Service | file* | AMD64 | ARM64 | ARM Oracle | Updated | More info |
|--|--|--|--|--|--|--|
| Among Us - Impostor Server | [egg-among-us--impostor-server.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/among_us/egg-among-us--impostor-server.json) | ✅ | ✅ | ✅ | 2023-01-18 | You MUST use Port 22023 for the Master Server. To host multiple servers, please read [Impostor Multiple Servers Documentation](https://github.com/Impostor/Impostor/blob/master/docs/Running-the-server.md#multiple-servers).
| BeamMP | [egg-beamMP-servers-ARM64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/beamMP/egg-beamMP-servers-ARM64.json) | ✅ | ✅ | ✅ | 2022-11-22 | native arm64  |
| Factorio | [egg-factorio-a-r-m64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/factorio/egg-factorio-a-r-m64.json) | ❌ | ✅ | ✅ | 2023-11-18 | 1 port |
| Path of Titans | [egg-path-of-titans-a-r-m64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/path_of_titans/egg-path-of-titans-a-r-m64.json) | ❔ | ❔ | ✅ | 2024-08-28 | 5 ports + native arm64  | 
| Quake 2 - Q2PRO | [egg-q2-p-r-o.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/quake_2/Q2PRO/egg-q2-p-r-o.json) | ✅ | ❌ | ❌ | 2024-03-24 | Shiped .pak files may be out of date. + install can take 15 minutes. |

#### **GTA**
| Service | file* | AMD64 | ARM64 | ARM Oracle | Updated | More info |
|--|--|--|--|--|--|--|
| FiveM | [egg-five-m-a-r-m64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/gta/egg-five-m-a-r-m64.json) | ❌ | ✅ | ✅ | 2024-07-15 | !!FEX!! |
| Multi Theft Auto | [egg-multi-theft-auto.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/gta/egg-multi-theft-auto.json) | ❌ | ✅ | ✅ | 2023-10-08 | Needs 2 ports |
| Rage MP | [egg-rage--m-p.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/gta/egg-rage--m-p.json) | ✅ | ✅ | ✅ | 2023-02-22 | Set the ARCH variable for your arch and select the right docker image |
| SA-MP | [egg-s-a--m-p.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/gta/egg-s-a--m-p.json) | ✅ | ✅ | ✅ | 2024-05-25 | Uses box86 emulation

#### **Minecraft**
| Service | file* | AMD64 | ARM64 | ARM Oracle | Updated | More info |
|--|--|--|--|--|--|--|
| paper + hibernation | [egg-paper--hibernation.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/minecraft/egg-paper--hibernation.json) | ✅ | ❌ | ❌ | 2023-01-22 | to controle the hibarnate in the console it is: `msh` and to controle minecraft is it: `mine` |
| Bedrock Vanilla - Box64 | [egg-vanilla-bedrock-box64.json](https://raw.githubusercontent.com/chriscdev125/RQ_eggs/refs/heads/main/game_eggs/minecraft/egg-vanilla-bedrock-box64.json) | ❌ | ✅ | ✅ | 2025-02-05 | Works but slow startup |
| Bedrock Vanilla - FEX | [egg-vanilla-bedrock-FEX.json](https://raw.githubusercontent.com/chriscdev125/RQ_eggs/refs/heads/main/game_eggs/minecraft/egg-vanilla-bedrock-FEX.json) | ❌ | ✅ | ✅ | 2025-02-05 | Works with a fast startup |


#### **SteamCMD**
| Service | file* | AMD64 | ARM64 | ARM Oracle | Updated | More info |
|--|--|--|--|--|--|--|
| 7 days to die | [egg-7-days-to-die-a-r-m64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-7-days-to-die-a-r-m64.json) | ❌ | ✅ | ✅ | 2023-01-26 | !!STEAMCMD!! + needs 6 ports + console is realy slow and shutdown can take up to 50 seconds |
| Ark survival Evolved | [egg-ark--survival-evolved.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-ark--survival-evolved.json) | ❌ | ❌ | ✅ | 2022-11-21 | !!STEAMCMD!! |
| Assetto Server | [egg-assetto-server.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-assetto-server.json) | ✅ | ✅ | ✅ | 2023-12-24 | Needs 2 ports |
| Counter Strike 2 | [egg-counter--strike--global-offensive.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-counter--strike--global-offensive.json) | ❌ | ❌ | ❌ | 2022-11-18 | !!STEAMCMD!! |
| Counter Strike: Source | [egg-css-arm64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-css-arm64.json) | ❌ | ✅ | ✅ | 2023-08-14 | !!STEAMCMD!! |
| Enshrouded| [egg-enshrouded-a-r-m64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-enshrouded-a-r-m64.json) | ❌ | ✅ | ✅ | 2024-02-25 | !!STEAMCMD!! !!FEX!! 2 port 18GB disk space |
| Garry's Mod | [egg-garrys-mod-a-r-m64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-garrys-mod-a-r-m64.json) | ❌ | ✅ | ✅ | 2023-11-22 | !!STEAMCMD!! |
| Palworld | [egg-palworld-a-r-m64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-palworld-a-r-m64.json) | ❌ | ✅ | ✅ | 2024-05-08 | !!STEAMCMD!! + !!FEX!! (It can take up to 3 minutes before you can use the console to this egg)|
| Project Zomboid | [egg-project-zomboid-a-r-m64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-project-zomboid-a-r-m64.json) | ❌ | ❌ | ✅ | 2024-02-23 | !!STEAMCMD!! + !!FEX!! (Does not seem to work on a Pi)|
| HLDS Engine Game / CounterStrike | [egg-h-l-d-s-engine-game-a-r-m64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-h-l-d-s-engine-game-a-r-m64.json) | ❌ | ✅ | ✅ | 2024-02-10 | !!STEAMCMD!!, crashes on first start, on cstrike error reinstall, login is needed |
| SCP: Secret Laboratory Exiled| [egg-s-c-p--s-l--exiled--a-r-m64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-s-c-p--s-l--exiled--a-r-m64.json) | ❌| ✅ | ✅ | 2025-01-26 | !!STEAMCMD!! + slow! + !!FEX!! |
| Satisfactory | [egg-satisfactory-a-r-m64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-satisfactory-a-r-m64.json) | ❌ | ❌ | ✅ | 2025-01-26 | 12GiB Ram, 3 ports  !!FEX!!|
| The Front | [egg-the-front-a-r-m64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-the-front-a-r-m64.json) | ❌ | ✅ | ✅ | 2024-02-13 | Needs 4 ports, 10GiB disk space, 5GiB ram |
| Unturned | [egg-unturned.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-unturned.json) | ❌ | ✅ | ✅ | 2023-06-29 | Needs 3 ports (game, game+1, game+2) && !!STEAMCMD!! **The first launch will segfault just wait for the server to start again** |
| Valheim | [egg-valheim.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/steamcmd/egg-valheim.json) | ❌ | ❌ | ✅ | 2022-11-20 | !!STEAMCMD!! |

#### **Terraria**
| Service | file* | AMD64 | ARM64 | ARM Oracle | Updated | More info |
|--|--|--|--|--|--|--|
| Terraria Vanilla | [egg-terraria-vanilla-ARM64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/terraria/egg-terraria-vanilla-ARM64.json) | ❌ | ✅ | ✅ | 2022-12-20 |
| Terraria tShock | [egg-tshock-ARM64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/game_eggs/terraria/egg-tshock-ARM64.json) | ✅ | ✅ | ✅ | 2023-01-04 | running with mono |

## Other
| Service | file* | AMD64 | ARM64 | ARM Oracle | Updated | More info |
|--|--|--|--|--|--|--|
| OpenWorld | [egg-open-world.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/other/egg-open-world.json) | ✅ | ✅ | ✅ | 2022-10-31 | Difrend docker image for ARM64 then for AMD64 and **needs a reinstall after changing the primary port! (remove old config first then reinstall)** | 

## Voice
| Service | file* | AMD64 | ARM64 | ARM Oracle | Updated | More info |
|--|--|--|--|--|--|--|
| TeamSpeak3| [egg-teamspeak3-server-ARM64.json](https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/voice/egg-teamspeak3-server-ARM64.json) | ❌ | ✅ | ✅ | 2022-07-06 |



## SteamCMD
if **!!STEAMCMD!!** is mentioned in the egg more info then you have to run this the first time you install a steam game **on the host OS!**
```sh
curl -sSL https://raw.githubusercontent.com/QuintenQVD0/Q_eggs/main/steamgames.sh | bash
```

## FEX
**!!FEX!!**

FEX is a special emulator. It is something like QEMU-user but with its own file system. So it needs by itself at least 8GB of disk space,
it also will create a folder called rootfs and a file in /home/container called `Config.json` Do not touch those files!
Keep in mind that the console will be slow / can reports Freezing because of its 2nd filesystem. You safly ignore those!

~~**When using FEX,  there is no auto update. You will have to hit reinstall!**~~
**FEX now has a very basic and still experimental auto update**

## FEX Mount

There is now a still but working experimental option to put the RootFS in a mount

How to do it:

1. Make a directory on the host system to where the mount will be stored. Example `/var/lib/pterodactyl/mounts/fex`
2. Chown that directory as the pterodactyl user. `chown pterodactyl:pterodactyl /var/lib/pterodactyl/mounts/fex`
3. Go on the admin side and make a new mount. Where source is the PATH from step 1 and the destionation a PATH but this can not be in /home/container! Recommended `/fex`
4. Set Read only to false, User mountable to true. Link it to your arm64 node and add eggs that will use this mount
5. Stop the wings `systemctl stop wings` (This will stop the console from working, servers will keep running).
6. Coppy the example config from the admin side under Nodes -> Your node -> Configuration to your clipboard. (**Do not use auto deploy!**)
7. Navigate on the host system to /etc/pterodactyl `cd /etc/pterodactyl`
8. Remove the exitings config.yml `rm config.yml`
9. Make that file again and opend it with an editor. `nano config.yml`
10. Paste the contence of your clipboard in it, then save and exit.
11. Start the wings again. `systemctl restart wings`
12. Now when making a server in the `FEX_ROOTFS_PATH` variable enter the value of target you set in step 3 **This must end in a / so if you did in step 3 `/fex` then here you need to enter `/fex/` else it will not work**.
13. Now create the server but uncheck the box  `Start Server when Installed`!!
14. When the server is fully installed, go to the admin side of that server, the Mounts tab.
15. Press on the green "plus" icon to add that mount to that server.
16. If this is the first server using that mount it will download the RootFS, else it will say it already exits and run / start the game server.

![afbeelding](https://github.com/QuintenQVD0/Q_eggs/assets/67589015/ca2d028c-cbbd-4a55-b161-a5555b82a938)
![afbeelding](https://github.com/QuintenQVD0/Q_eggs/assets/67589015/be782bfb-81a3-484a-8b67-10d015f818b8)
![afbeelding](https://github.com/QuintenQVD0/Q_eggs/assets/67589015/bbe1cb31-9505-4bd1-8a1d-5e5b248da3d2)
![afbeelding](https://github.com/QuintenQVD0/Q_eggs/assets/67589015/be1bb45e-5064-4945-a93b-4c74ffe91e26)
