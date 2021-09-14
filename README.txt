color a
taskkill /im "nvcontainer.exe" /im gamebar.exe /im ui32.exe /im wallpaper32.exe /im ldcfg.exe /im hid.exe /im BakkesMod.exe /im discord.exe /im eadesktop.exe /im EpicGamesLauncher.exe /im galaxyclient.exe /im musixmatch.exe /im "nvidia rtx voice.exe" /im opera.exe /im PowerToys.exe /im "Redragon Audio 7.1.exe" /im rvrvpngui.exe /im spotify.exe /im steam.exe /im taskbarx.exe /im vgtray.exe /im xboxappservices.exe /im XboxPcApp.exe /im miner.exe /im t-rex.exe /t /f
timeout /t 1 /nobreak
taskkill /im explorer.exe /f
timeout /t 1 /nobreak
explorer.exe
timeout /t 1 /nobreak
DisplaySwitch.exe /internal
timeout /t 2 /nobreak
@echo off
:start
C:
cd C:\Users\Gabriel\Desktop\NVIDIA
t-rex -a mtp -o us-solo-firo.2miners.com:9090 -u aEP2jijg1LtywDk41E4Keo8qL4myqEdw7A.RIG_Firo_ZCoin_XZC -p x
goto start
pause
