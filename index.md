# FaceTracker
<img src="https://github.com/Juulpy/FaceTracker/blob/gh-pages/path992.png" width="266" height="219">

### Setup instructions
1. Install and open the FaceTracker app on your phone
2. Install and open the latest version of [OpenTrack](https://github.com/opentrack/opentrack/releases)
3. Open Command prompt on your computer (Windows key+R -> type `cmd`)
4. Type `ipconfig` and hit enter. Enter your IPv4 address into the respective input field in the app
5. In OpenTrack under Input, select **UDP over network** and click on the hammer symbol
6. Enter the port into the respective input field in the app. Typically this will be 4242
7. In the app, tap **Update Parameters**
8. In OpenTrack, go to Options>Hotkeys and bind an easily accessible key combination to **Center**
9. In OpenTrack, click OK on the dialog box and click **Start**
10. Everything should work!

### Modes
FaceTracker has 3 modes: Dogfight mode, Normal mode and Cruise mode. These modes change the sensitivity of the rotational and translational axes. Because the sensitivity changes, the face position might also change. This will eventually be corrected for but isn't in the pipeline yet. Also, the sensitivity of each mode will be adjustable.

### Tuning Opentrack
Everyone has different preferences when it comes to sensitivity, and luckily this is very intuitive to edit in OpenTrack. If you want to edit the default values, go to the Mapping menu in OpenTrack. Here, you can adjust the mapping to your liking. You can also import a prefab config file. Download this file and import it by clicking on Profile>Open configuration directory.

Additionally, you can edit the filter values. Higher smoothing values do look nice, but also impact input lag. 

### Planned features
* Customizable modes
* Fix the startup crash in some cases (working on it, not yet tracked down.)
* Face tracking optimalizations (not yet started)
* Release to iOS (not yet started)
