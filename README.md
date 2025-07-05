# The Sims 2 Legacy Collection Fixer



The **Sims 2 Legacy Collection Fixer** fixes some of the issues with The Sims™ 2 Legacy Collection. 

---

## **Fixes & Improvements**
- Installs the IKEA Stuff Pack.

- Restores the radio songs cut due to licensing issues.

- Fixes an issue where some of the CAS items from the Happy Holidays Stuff Pack are missing.

- Sets all of the 'Objects.package' files to read only so you can't corrupt them.

- Changes the menus to say 'The Sims™ 2'.

- Changes the title screen music and loading text to be the ones from base game.

- Improves the built-in recording feature. Enabled support for smooth edges along with increased resolution, bitrate, and audio quality.

- Installs [dgVoodoo2](https://github.com/dege-diosg/dgVoodoo2) and [dxvk](https://github.com/doitsujin/dxvk) to improve compatiblity and performance. 

- Installs The Sims 2 Store and pre-order bonus exclusive items.

- Installs the 'TS2-Extender' created by [Lazy Duchess](https://www.tumblr.com/lazyduchess).

**Important Notice:** TS2-Extender is still a **work in progress**, and thus the version included in The Sims 2 Legacy Collection Fixer (**0.40**) **may be out of date**.

> **Check what the latest version is here:** [TS2 Extender](https://github.com/LazyDuchess/TS2-Extender/releases)

---

## **Use Instructions**
1. **Download** the program from the [Releases page](https://github.com/Secondhand-Feraligatr/The-Sims-2-Legacy-Collection-Fixer/releases).  
2. **Run** the `.exe`.  
3. **Select** your install location:
   - **Steam** → `C:\Program Files (x86)\Steam\steamapps\common\The Sims 2 Legacy Collection`
   - **EA App** → `C:\Program Files\EA Games\The Sims 2 Legacy Collection`
   - **Custom Install** → Select your Legacy Collection install directory manually.
4. **Click Install** and wait for the process to complete. 

---

## **VP6 Install Instructions**
If you get a **no valid video codec** error when trying to use the built-in recording feature, then it means your computer does not have the VP6 video codec installed. Here is how to install it:
1. Locate your Legacy Collection install.
2. Go into the `install` folder and then the `VP6` folder. 
3. Run the `vp6.reg` file.
4. Copy the `vp6vfw.dll` file.
5. Click the `Windows (C:)` button and then open the `Windows` folder.
6. Copy and paste the `vp6vfw.dll` file into the folders `System32` and `SysWOW64`.

---

## **Notes**
- Using the **verfity integrity of game files** option in Steam or EA App will **revert** some of the fixes made by this installer. This happens because it detects the modified game files and replaces them with the vanilla ones. So if you use verfity integrity of game files you will then need to use this program again. 

 - TS2-Extender auto skips the intro. You can change this by editing the 'TS2Extender.ini' located in TSBin in the EP9 folder.

 - I am aware of how you are not meant to use dgVoodoo2 and dxvk at the same time, but in my testing it just works. I've tried it on 2 different computers and I have found that dgVoodoo2 does improve performance while dxvk fixes an issue caused by dgVoodoo2 where family thumbnails are broken. I have not experienced any issues in my testing. If you do experience issues after installing this then please let me know.

 - I highly recommend you do not use "high, uncompressed" option with the built-in recording feature. This causes the file size of the videos to be insanely massive. I found that a 60 second video ended up being **4 GB**.

- The videos recorded with the built-in recording feature can not be played in Windows 11's default media player due to it not supporting VP6. I recommend using [VLC](https://www.videolan.org/vlc/) to watch them.
   
---

## **Recommended Mods & Programs**

These are all mods and programs that aren't included with this fixer, but I highly recommend you go install:

- [Body Shop Installer For Legacy Collection ](https://modthesims.info/d/690428/body-shop-installer-for-legacy-collection.html) - Installs Body Shop and makes it compatible with Legacy Collection.

**Important Notice:** The store hairs from this fixer are broken in Body Shop in whatever reason. They work fine in CAS, but in Body Shop you can't select them. If this really bugs you, then you can fix this by moving the store items (the "Extra-Items" files installed in `Base/TSData/Res/Catalog/Bins`) to your downloads folder.

- [Clean/Fixed Maxis Neighborhoods Installer ](https://modthesims.info/d/691808/clean-fixed-maxis-neighborhoods-installer.html) - Replaces all of the Maxis neighborhoods with clean/fixed versions made by the community.

- [Sims2Pack Clean Installer](https://modthesims.info/d/409950/sims2pack-clean-installer-v1-6-22-updated-aug-2-2014.html) - Legacy Collection doesn't include the Maxis program needed to install '[Sims2Pack](https://gadgetsranked.com/how-do-i-install-sims2pack/)' files, so you can use this Mootilda program instead.

- [HoodChecker](https://modthesims.info/d/456523) - Detects and fixes issues with your neighborhoods.

- [UI Text Fonts Fix for AL/MG](https://modthesims.info/d/563540) - Fixes an issue where the text is smaller than it should be.

- [TS2 Store Edition UI Icon Restored for Any Game Setup](https://modthesims.info/d/650961/ts2-store-edition-ui-icon-restored-for-any-game-setup.html) - FIxes an issue where The Sims 2 Store CAS items are missing the store icon.

- [Cper and Csla Archetypes - Now with 100% more working than the competition!](http://www.moreawesomethanyou.com/smf/index.php/topic,9028.0.html) - Fixes the 2 broken face templates 21 and 25. (If you don't know how these face templates are broken, then you should watch watch this youtube video: [The Sims 2: Broken Face Templates (explanation)](https://www.youtube.com/watch?v=HxfTTP21ZU0)

- [No Corrupted Death Memory](http://www.moreawesomethanyou.com/smf/index.php?topic=2368.0) - Fixes an issue where sims can get a corrupted death memory.

If you want to go even further into modding, then you can check out this far more extensive mod list called: [The Sims 2 Legacy Collection - Essential Mods Masterlist](https://modthesims.info/showthread.php?t=689467)
