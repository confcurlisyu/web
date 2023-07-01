
 
# How to Unlock the Bootloader of Huawei and Honor Devices with Kirin SoCs Using PotatoNV
 
If you own a Huawei or Honor device with a Kirin processor and want to unlock its bootloader, you might have heard of PotatoNV. PotatoNV is an open-source tool that can generate bootloader unlock codes for several HiSilicon Kirin-powered Huawei and Honor devices. In this article, we will show you how to use PotatoNV to unlock the bootloader of your device.
 
## What is PotatoNV?
 
PotatoNV is a bootloader unlocker for select Huawei/Honor smartphones developed by Andrey Smirnoff. The tool makes use of a low-level bootloader flashing method discovered by XDA Senior Member hackintosh5. The tool requires users to open up the target device and access the test points on the motherboard. The tool can then generate a valid unlock code for the device using an algorithm that was deciphered by the developer.
 
**Download File ☆ [https://t.co/FBk7mCNOiZ](https://t.co/FBk7mCNOiZ)**


 
## What devices are supported by PotatoNV?
 
According to the developer, PotatoNV works with the following devices:

| Sr. No. | Device | Device Codename | XDA Forum Link | Bootloader |
| --- | --- | --- | --- | --- |

| 1 | Honor 7X (BND) | BND | [Link](https://forum.xda-developers.com/f/honor-7x.6880/) | Kirin 659 (A) |

| 2 | Honor 8 Pro / V9 (DUK) | DUK | [Link](https://forum.xda-developers.com/f/honor-8-pro.6881/) | Kirin 960 |

| 3 | Honor 9 Lite (LLD) | LLD | [Link](https://forum.xda-developers.com/f/honor-9-lite.6884/) | Kirin 659 (A) |

| 4 | Honor 9 (STF) | STF | [Link](https://forum.xda-developers.com/f/honor-9.6883/) | Kirin 960 |

| 5 | Huawei Mate 9 (MHA) | MHA | [Link](https://forum.xda-developers.com/f/huawei-mate-9.6716/) | Kirin 960 |

| 6 | Huawei Mate 9 Pro (LON) | LON | N/A | Kirin 960 |

| 7 | Huawei MediaPad M5 Lite (BAH2) | BAH2 | N/A | Kirin 659 (B)How to use PotatoNV?
<br>Before you use PotatoNV, you need to prepare your device and your computer. Here are the steps you need to follow:<br>
<ol>
<li>Backup your data. Unlocking the bootloader will erase all your data on the device.</li>
<li>Download and install the latest version of PotatoNV from <a href="https://github.com/mashed-potatoes/PotatoNV/releases">here</a>.</li>
<li>Download and install the Huawei USB drivers from <a href="https://consumer.huawei.com/en/support/phones/p8-lite/">here</a>.</li>
<li>Enable USB debugging and OEM unlocking on your device. To do this, go to Settings > About phone and tap on Build number seven times. Then go back to Settings > System > Developer options and enable USB debugging and OEM unlocking.</li>
<li>Turn off your device and remove the back cover. You may need a heat gun and a pry tool to do this. Be careful not to damage any components or cables.</li>
<li>Locate the test points on the motherboard. You can find the test point locations for your device on <a href="https://forum.xda-developers.com/t/bootloader-unlock-method-for-huawei-and-honor-devices-with-kirin-socs.4242481/">this XDA thread</a>. You may need a magnifying glass and a flashlight to see them clearly.</li>
<li>Connect two wires or tweezers to the test points and short them together. This will put your device into VCOM_DOWNLOAD mode.</li>
<li>Connect your device to your computer using a USB cable. You should hear a sound indicating that your device is detected.</li>
<li>Run PotatoNV as administrator on your computer. Select your device model and bootloader from the drop-down menus.</li>
<li>Click on Read Phone Info and wait for the tool to read your device information. If everything is correct, you should see your device serial number, IMEI, MEID, etc.</li>
<li>Click on Get Unlock Code and wait for the tool to generate an unlock code for your device. This may take a few minutes.</li>
<li>Copy the unlock code and paste it in a text file for later use.</li>
<li>Click on Unlock Bootloader and enter the unlock code when prompted. Wait for the tool to unlock your bootloader. This may take a few seconds.</li>
<li>Your device will reboot automatically. You should see a warning message on the screen indicating that your bootloader is unlocked.</li>
<li>Congratulations! You have successfully unlocked the bootloader of your Huawei or Honor device using PotatoNV.</li>
</ol>
What can I do after unlocking the bootloader?
<br>Unlocking the bootloader allows you to install custom ROMs, kernels, mods, root, etc. on your device. However, you should be careful about what you flash on your device as some files may be incompatible or harmful. Always make sure to download files from trusted sources and follow the instructions carefully. You should also backup your data before flashing anything on your device.<br>
<br>Some of the popular custom ROMs for Huawei and Honor devices are LineageOS, Pixel Experience, Resurrection Remix, etc. You can find them on [XDA Forums](https://forum.xda-developers.com/). To install a custom ROM, you need to have a custom recovery such as TWRP or OrangeFox installed on your device. You can find the custom recovery for your device on [TWRP website](https://twrp.me/Devices/Huawei/) or [OrangeFox website](https://orangefox.download/en/devices). To install a custom recovery, you need to flash it using fastboot commands.<br>
<br>To root your device, you can use Magisk or SuperSU. Magisk is preferred as it is more stable and has more features such as Magisk Hide, Magisk Modules, etc. You can download Magisk from [here](https://github.com/topjohnwu/Magisk/releases). To install Magisk, you need to flash the Magisk zip file using a custom recovery.<br> 8cf37b1e13
<br>
 |