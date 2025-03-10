You should now see the the data source selection wizard.

<img src="../images/Install08.png" style="zoom:75%;" />

If you don't, touching this button will display the wizard.

<img src="../images/Install12.png" style="zoom:75%;" />

If the button is not visible you can display it using a long touch on the xDrip+ icon and enabling the `Source Wizard Button`.

<img src="../../images/UImenu.png" style="zoom:75%;" />

</br>

## Bluetooth connection to a sensor or a bridge

xDrip+ will take care of the Bluetooth connection to your sensor or to the Bluetooth device sending data from your device (called a bridge). 

!!!warning    
    Do **NOT** try to use Android Settings -> Connections -> Bluetooth to connect! 

<img src="../images/Install26.png" style="zoom:100%;" />

If your bridge paired to Android, unpair it before continuing.

<img src="../images/Install27.png" style="zoom:100%;" />

!!!warning "One device at a time"  
    Sensors and bridges can only connect to one smartphone (or tablet) at a time, and only to one app at a time.  
    You should uninstall the vendor app in order to connect xDrip+ to your sensor or bridge.  
    If another device is connect to your sensor or bridge you should turn it off or disable the other app before trying to connect with xDrip+.  
    **You cannot connect to two phones or applications. With an exception for G6: the second device can only be a receiver/connected pump or BlueJay watch.**

</br>

## Sensor selection

The following sensors are supported directly by xDrip+:

- [G4 (with bridge) or G4 Platinum receiver](../g4)    
  <img src="../images/Install28.png" style="zoom:54%;" />    <img src="../images/Install29.png" style="zoom:50%;" />
- [G5](../g5)  
  <img src="../images/Install28.png" style="zoom:54%;" />    <img src="../images/Install30.png" style="zoom:49%;" />
- [G6 and One](../g6)  
  <img src="../images/Install28.png" style="zoom:54%;" />    <img src="../images/Install31.png" style="zoom:50%;" />
- [Libre (with bridge)](../libreBT)  
  <img src="../images/Install32.png" style="zoom:54%;" />    <img src="../images/Install33.png" style="zoom:50%;" />
- [Libre with patched SWR50 smartwatch](../librealarm)  
  <img src="../images/Install32.png" style="zoom:54%;" />    <img src="../images/Install34.png" style="zoom:51%;" />
- [Libre 2 (only EU)](../libre2)  
  <img src="../images/Install32.png" style="zoom:54%;" />    <img src="../images/Install33.png" style="zoom:50%;" />
- [Medtrum A6/S7](../medtrum)  
  <img src="../images/Install36.png" style="zoom:54%;" />    <img src="../images/Install37.png" style="zoom:53%;" />

The following sensors and features are supported with a companion app:

- [Libre 2 (only EU)](../libre2patch)  
  <img src="../images/Install32.png" style="zoom:51%;" />    <img src="../images/Install35.png" style="zoom:53%;" />
- [Eversense](../eversense)  
  <img src="../images/Install36.png" style="zoom:52%;" />    <img src="../images/Install41.png" style="zoom:53%;" />
- [640G/670G pumps](../640_670)  
  <img src="../images/Install36.png" style="zoom:52%;" />    <img src="../images/Install40.png" style="zoom:53%;" />
- [Build your own app (BYODA)](../byod) for G6 sensors  
  <img src="../images/Install36.png" style="zoom:52%;" />    <img src="../images/Install40.png" style="zoom:53%;" />
- [Aidex](../aidex)  
  See below.
- [Companion app](../companion) for G6, G7, One and CamAPS  
  See below.

</br>

## Follower mode

- [xDrip+ Sync](../xdripfollower) (requires Google Play Services)
- [Nightscout and Diabox](../nightscoutfollower)  
  <img src="../images/Install36.png" style="zoom:52%;" />    <img src="../images/Install38.png" style="zoom:53%;" />
- [Dex Share](../dexshare)  
  <img src="../images/Install36.png" style="zoom:52%;" />    <img src="../images/Install39.png" style="zoom:53%;" />
- [CareLink](../carelinkfollow)  
  <img src="../images/Install36.png" style="zoom:52%;" />    <img src="../images/Install42.png" style="zoom:60%;" />

</br>

## Changing data source

You can select another data source without using the wizard from the settings menu:

`Menu` / `Settings` / `Hardware data source`

<img src="../../images/hamburger_menu.png" style="zoom:75%;" />

<img src="../../images/M-S.png" style="zoom:75%;" />

<img src="../../images/M-S-HDS.png" style="zoom:75%;" />

[G4 (with bridge) or G4 Platinum receiver](../G4)  

<img src="../images/M-S-HDSlistA.png" style="zoom:75%;" />

[G5](../G5), [G6 and One](../G6) 

<img src="../images/M-S-HDSlistB.png" style="zoom:75%;" />

[Libre (with bridge)](../libreBT) 

<img src="../images/M-S-HDSlistC.png" style="zoom:75%;" />

[Libre whole house](https://github.com/tzachi-dar/LibreAllHouse)

<img src="../images/M-S-HDSlistD.png" style="zoom:75%;" />

[xDrip+ Sync](../xdripfollower)

<img src="../images/M-S-HDSlistE.png" style="zoom:75%;" />

[Libre with patched SWR50 smartwatch](../librealarm) 

<img src="../images/M-S-HDSlistF.png" style="zoom:75%;" />

[Libre 2 (only EU)](../libre2patch)

<img src="../images/M-S-HDSlistG.png" style="zoom:75%;" />

[640G/670G pumps](../640_670), [Eversense](../eversense) and [Build your own app (BYODA)](../byod)

<img src="../images/M-S-HDSlistH.png" style="zoom:75%;" />

[Medtrum A6/S7](../medtrum) 

<img src="../images/M-S-HDSlistI.png" style="zoom:75%;" />

[Nightscout and Diabox](../nightscoutfollower) 

<img src="../images/M-S-HDSlistJ.png" style="zoom:75%;" />

[Dex Share](../dexshare) 

<img src="../images/M-S-HDSlistK.png" style="zoom:75%;" />

[Companion app](../companion) for G6, G7, One and CamAPS

<img src="../images/M-S-HDSlistN.png" style="zoom:75%;" />

[GlucoRx/Aidex](../aidex)

<img src="../images/M-S-HDSlistP.png" style="zoom:75%;" />

[Web Follower](../webfollower) for Libre 3

<img src="../images/M-S-HDSlistO.png" style="zoom:75%;" />

[CareLink](../carelinkfollow)

<img src="../images/M-S-HDSlistM.png" style="zoom:75%;" />

##### Disable Collection

If you want to disable xDrip+.

<img src="../images/M-S-HDSlistL.png" style="zoom:75%;" />

</br>

[*Last modified 13/6/2022*](https://github.com/NightscoutFoundation/xDrip/releases/tag/2022.06.13)
