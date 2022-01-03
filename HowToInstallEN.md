# How to install ACT FFXIV Mini Parse

## 1 - Install Advanced Combat Tracker (ACT) and FFXIV plugin

Go to this page: https://advancedcombattracker.com/download.php and download the latest version of ACT and the FFXIV plugin.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/doc_download.png)

Once both files are downloaded, start the ACT installation by running `ACTv3-Setup.exe` and validating each step.

You can extract the archive `FFXIV_ACT_Plugin_2.6.3.3.zip` (right click => extract all => extract).

Copy the extracted folder to a safe directory that you wouldn't accidentally delete or, in the default plugin folder
ACT: `C:\Users\%username%\AppData\Roaming\Advanced Combat TrackerPlugins`

## 2 - Download the OverlayPlugin

Go to this page : https://github.com/RainbowMage/OverlayPlugin/releases and download the version corresponding to your operating system :

- x86 for a 32 bits system
- x64 for a 64 bits system

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/doc_download_overlay.png)

You can extract the archive and copy it to the same place as the FFXIV plugin.

## 3 - Download the MiniParse

Go to this page: https://github.com/Jericho1060/ffxiv-miniparse/releases and download the archive of the latest version.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/doc_download_miniparse.png)

As for the two previous archives, extract the content and copy it in the same folder.

## 4 - Activate plugins in ACT

Start ACT and go to the `Plugins` tab and then to the `Plugin Listing` tab.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/install_act_plugins.png)

Then click on the `Browse` button and go to the folder where you copied all the folders.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/install_act_browse_dirs.png)

Open the `FFXIV_ACT_Plugin_x.x.x.x` folder (the x's here refer to the version of the plugin, the numbers may change depending on the current version when you install plugin),
select the file `FFXIV_ACT_Plugin.dll` and validate by clicking on the `Open` button.

Back on ACT, click on the `Add/Enable Plugin` button.

Do this again with the `OverlayPlugin-0.3.3.9-x64-full` folder (the name may also change depending on the version) and select the `OverlayPlugin.dll` file, be careful, there are
several dll files in this folder, make sure you select the right one. Click `Add/Enable Plugin` again to activate it.

You should now see both plugins in the list below with the `Enabled` box selected.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/install_act_plugins_enabled.png)

## FFXIV Plugin Settings

Click on the `FFXIV ACT Plugin` tab and then select the language your game is set to.

You can also change the value of the `Parse Filter` list to `Party` to display only the members of your group. Showing everyone in a 2-player raid is not always easy to read.

You can also check the `Disable Combine Pets with Owner` box to display pet information (such as summonses) separately from those to whom they are linked. linked to.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/install_act_plugins_ffxiv_settings.png)

## OverlayPlugin settings and miniparse skin activation

Now click on the `OverlayPlugin.dll` tab and then on the `Mini Parse` sub-tab.

Check that the `Show Overlay` box is checked (you can also enable the `Enable clickthru` option so that the mini parse is not clickable, your clicks will go through in this case
and the overlay will not be displayed). in this case and the overlay will not interfere with your game).

Then click on the `...` button at the end of the line next to the `URL` option and open the folder where you copied everything again, go to the `ffxiv-miniparse` folder and select
the file `Torgan.MiniParse.html` and click the `Open` button.

![Display](https://raw.githubusercontent.com/Jericho1060/ffxiv-miniparse/main/resources/install_act_plugins_overlay_settings.png)
