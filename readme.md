---------------------------------------------------------------------------------------------------------
HZOS-Project
====================
Another cherry-picking ROM, developed by an usual person, nothing special


To initialize your local repository, use this command:
-----------------------------------------------------

    repo init -u https://github.com/HZOSPRJ/android_manifest.git -b udc

To sync the repository, use this command:
-----------------------------------------

    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags --optimized-fetch --prune

To Build, use following commands:
---------------------------------
    
    . build/envsetup.sh
    lunch hz_<devicecodename>-userdebug
    make bacon

---------------------------------------------------------------------------------------------------------

Special thanks to All ROM Developers in this community

---------------------------------------------------------------------------------------------------------

Credits
---------------
* [**LineageOS**](https://github.com/LineageOS)
* [**crDroid**](https://github.com/crdroidandroid)
* [**Omnirom**](https://github.com/omnirom)
* [**Evolution-X**](https://github.com/Evolution-X)
* [**RisingTechOSS**](https://github.com/RisingTechOSS)
* [**PixelExperience**](https://github.com/PixelExperience)

And other ROMs 

Thank you!

---------------