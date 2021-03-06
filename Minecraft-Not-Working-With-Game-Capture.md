Minecraft does not default to the high performance GPU. In order to get it working with game capture you will need to do the following:

**This is mainly for laptops and all-in-one systems.**

* Close OBS and Minecraft

* Open the Windows 10 Settings App (Start button → Cogwheel icon)

![StartMenuCogwheelIcon](https://i.imgur.com/6dUeodW.png)
* Navigate to System → Display and select "Graphics settings" near the bottom

![](https://raw.githubusercontent.com/wiki/obsproject/obs-studio/images/laptop-troubleshooting/win10/01-graphics-settings.png)
* Choose "classic app" / "Desktop app" and hit "Browse". Navigate to javaw.exe, usually located here:
> C:\Program Files (x86)\Minecraft Launcher\runtime\jre-x64\bin\javaw.exe

![](https://raw.githubusercontent.com/wiki/obsproject/obs-studio/images/laptop-troubleshooting/win10/02-add-application.png)

![](https://i.imgur.com/kphrwU3.png)

* Once Minecraft/javaw.exe is added, click "Options" and choose "High Performance"

![](https://raw.githubusercontent.com/wiki/obsproject/obs-studio/images/laptop-troubleshooting/win10/05-high-perf.png)