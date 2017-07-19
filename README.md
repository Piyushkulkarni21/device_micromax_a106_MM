# Micromax Unite 2 A106

Micromax Unite 2 device (codenamed as _"a106"_) is low-range smartphone from Acer.

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | Quad-core 1.3 GHz Cortex-A7
GPU     | Mali-400MP2
Memory  | 1GB RAM
Shipped Android Version | 4.4.2
Storage | 4/8 GB
Battery | 2000 mAh
Display | 4.7" 480 x 800 px
Camera  | 8MPx, LED Flash



This branch is for building LineageOS 13.0 ROMs.

## What's working
- [x] FM Radio
- [x] Calls
- [x] USSD code
- [x] WiFi
- [x] Bluetooth
- [x] Video recording
- [x] Camera
- [x] SMS (sending & recieving)
- [x] All sensors
- [x] Offline charging
- [x] 2G/3G switch
- [x] Data connection
- [ ] VPN


# Build Commands :-

  * repo init -u git://github.com/LineageOS/android.git -b cm-13.0
  * repo sync
  * git clone https://github.com/EndLess728/android_device_micromax_unite2_a106.git device/micromax/a106
  * git clone https://github.com/EndLess728/android_vendor_micromax_a106.git vendor/micromax/a106
  * cd device/micromax/a106/patches
  * source apply.sh 
  * source build/envsetup.sh
  * brunch a106
  * Done :)
  
# Credits/Thanks to:-
  * Fire855 
  * Axet
  * chrmhoffmann
  * DerTeufel1980
  * Al3XKOoL
  * xen0n
  * kashifmin
  * hyperion70
  * tribetmen
  * CyanogenMod Team
  * hejsekvojtech (For his Device Tree as Base)
  * manjotsidhu
  * EndLess728
