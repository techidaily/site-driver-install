---
title: Adjust Unsupported Software Package
date: 2024-07-11T16:29:01.455Z
updated: 2024-07-12T16:29:01.455Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverInstall
description: This Article Describes Adjust Unsupported Software Package
excerpt: This Article Describes Adjust Unsupported Software Package
keywords: Adjusting Unsupported Software,Unsupported Software Configuration (Long-Tail Keyword),Fix Unsupported Application Package,Updating Discontinued Programs,Remedy Outdated Software Issues (Long-Tail Keyword),Compatible Solutions for Unsupported Applications (Keyword + Long-Tail),Supporting Legacy Software Packages (Keywords & Long-Tail Keyword)
thumbnail: https://thmb.techidaily.com/d9a0fed70b3544c875727acbd189babb9991061b2738772aa77659169a12a4b8.jpg
---

## Adjust Unsupported Software Package

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0bf7fa95390.png)

 Does this look familiar? You may see this error message when launching a program or installing a driver in your Windows PC or laptop. The error usually reads:

* **This installation package is not supported by this processor type.**

 But don’t worry. Many users have resolved their problem with the solutions in this article. So check it out…

## Try these fixes

1. [**Restart PC and reinstall the application/program**](#Fix1) **[](#Method1)**
2. [**Automatically update your drivers**](#Fix2)
3. [**Update your Windows version**](#Fix3)

## Why does this problem occur when installing drivers?

 The reason why it happens when installing an application or program is that there is something wrong with the installation file when progressing, so you can try to restart your computer and try again.

As for the reason why it happens while installing drivers:

 Previously, you can successfully install the driver package when the Windows OS and processor type are as defined by the driver manufacturers.

 However, starting from 2016, Microsoft made changes to its update strategies. The change is in the format of**TargetOSVersion** decoration, an entry in **[INF file](https://docs.microsoft.com/en-us/windows-hardware/drivers/install/inf-manufacturer-section)**  . This format defines the installation information to install the driver package, such as the OS versions and the product types.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0bf47b50435.png)

 Starting with Windows 10, version 1607 (Build 14310 and later), the format adds a new part in the INF file: the**\[BuildNumber\]** part. That means that **it started to define the build number of the Windows version when installing the drivers** . Soon after, **Intel has started to adopt this new technique and also add the \[BuildNumber\] part into the installation information** .

 That is to say, If the build number of your Windows version doesn’t fit with the defined \[BuildNumber\] part of the package by the driver manufacturers, you will fail to install the driver package, despite the correct Windows version and processor type.

### **How to Check the Build Number in your Windows**

**Tips:** If you want to check whether the build number in your Windows fits with the one defined by the driver manufacturer, follow these instructions:

 Check your computer’s build number and other system information via Command Prompt:

 1) Type**cmd** in the search box, and right click **Command Prompt** to**Run as administrator** . Then click**Yes** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a018c0f66b68.png)

 2) Type**systeminfo** and press**Enter** . Then you will see your build number as below:

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0c202e7a2f5.png)

 Then check the defined build number in the driver package (take Intel graphics driver for Windows 10 64 bit as an example):

 1) Go to the [Intel download center](https://downloadcenter.intel.com/) , and search then download your preferred device driver.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0c21f7f0851.jpg)

 2) Open the downloaded file, and click the**Graphics** folder.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0c1a2de4eb3.png)

 3) Find a file with **.inf extension name** and open it.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0c1a97204a5.jpg)

 4) Check the **\[Manufacturer\]** part in the file, and you will see defined build number. As you can see 14393 in the \[BuildNumber\] part, this driver package supports to download on Windows 14393 and later.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0c1b58eebf9.png)

 If the build number of your Windows is not 14393 and later, you can’t install this graphics driver in your computer.

### Fix 1: Restart your PC and reinstall the application/program

 If you run into the error when you are downloading or installing a program in your computer, there may be something wrong with the installation file or parsing the file, so you can try to restart your PC, and download the installation file again to reinstall it.

### Fix 2: Automatically update your drivers

 A missing or outdated driver can also cause the error, so you can try to update the drivers in your computer to remove the error when installing the program. Though you may have problems to install drivers online, you can also try this method. There are two ways to download and install the drivers in your Windows.

**Option 1 – Manually** : You can manually download and install the drivers in your Windows. You may need to find the correct drivers on the website, check if the build number defined by the driver installation package match with the build number in your Windows (you can click [here](#Step1) to know how to check the build number), and then download it in your Windows. That may require time and computer skills.

**Option 2 – Automatically (Recommended)** : If you don’t have time or skills to find and install the drivers manually, you can do it automatically with [**Driver Easy**](https://tools.techidaily.com/drivereasy/download/) .

 With Driver Easy, you don’t need to know the exactly build number of your computer, and you don’t need to risk installing the wrong driver. Furthermore, it supports the new scan technique in Windows 10\. This will help you find more accurate scan results.

 You can update your drivers automatically with either the**FREE** or the**Pro version** of Driver Easy. But with the Pro version it takes just 2 clicks (and you get**full support and a 30-day money back guarantee**):

 1) [**Download**](https://tools.techidaily.com/drivereasy/download/)   and install Driver Easy.

 2) Run Driver Easy and click **Scan Now** . Driver Easy will then scan your computer and detect any problem drivers.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0c05705e2b9.jpg)

 3) Click the **Update**  button next to a flagged driver to automatically install the correct driver (you can do this with the FREE version).

Or click **Update All** to automatically download the correct version of _all_  the drivers that are missing or outdated on your system (this requires the [**Pro version**](https://tools.techidaily.com/drivereasy/download/) – you’ll be prompted to upgrade when you click Update All).

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0bf3e95e05a.jpg)

 4) Restart your Windows and you will have the latest and correct drivers in your Windows.

### Fix 3: Update your Windows version

 You can update your Windows 10 to the latest version to solve this problem. In doing that, your build number is always the latest. While installing the driver, you don’t need to worry whether your build number is correct or not. Follow these instructions to update:

 1) Click the**Settings** button in the**Start menu** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0beef3646db.png)

 2) Click **Update & security** .

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0bef3bdbe04.jpg)

 3) Click**Check for updates** to scan for the latest update, then your Windows will automatically download the updates.

![](https://images.drivereasy.com/wp-content/uploads/2017/11/img_5a0bf009896fc.png)

 4) Click**Restart Now** to restart your PC/laptop and finish the update.

 5) Try to install the driver again to see if it works.

 Hope these methods can help you fix the error. If you problem still persists, feel free to let us know and we will see what more we can do to further help.

* [Drivers](https://tools.techidaily.com/drivereasy/download/)
* [Windows 10](https://tools.techidaily.com/drivereasy/download/)

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>



<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>



<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://driver-install.techidaily.com/unleash-potential-lenovos-simple-upgrade-path/"><u>Unleash Potential: Lenovo's Simple Upgrade Path</u></a></li>
<li><a href="https://android-pokemon-go.techidaily.com/how-do-you-get-sun-stone-evolutions-in-pokemon-for-oppo-reno-11f-5g-drfone-by-drfone-virtual-android/"><u>How Do You Get Sun Stone Evolutions in Pokémon For Oppo Reno 11F 5G? | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/connectivity-made-easy-with-one-click-universal-driver-install/"><u>Connectivity Made Easy with One-Click Universal Driver Install!</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/new-discreetly-navigate-through-instagrams-stories-archive-for-2024/"><u>[New] Discreetly Navigate Through Instagram's Stories Archive for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/hacks-to-do-pokemon-go-trainer-battles-for-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>Hacks to do pokemon go trainer battles For Vivo T2 5G | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/simplifying-startech-for-a-multiverse-of-windows-systems/"><u>Simplifying StarTech for a Multiverse of Windows Systems</u></a></li>
<li><a href="https://driver-install.techidaily.com/quick-link-to-asus-bt400-driver-and-support-for-os-x/"><u>Quick Link to Asus BT400 Driver & Support for OS X</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720062708634-easy-access-to-latest-device-drivers/"><u>Easy Access to Latest Device Drivers!</u></a></li>
<li><a href="https://driver-install.techidaily.com/enhance-samsung-printer-capacities-in-windows-11/"><u>Enhance Samsung Printer Capacities in Windows 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/win7-streamlined-updates-to-improve-hp-graphics/"><u>Win7 Streamlined Updates to Improve HP Graphics</u></a></li>
<li><a href="https://driver-install.techidaily.com/mend-software-hardware-gap/"><u>Mend Software-Hardware Gap</u></a></li>
<li><a href="https://driver-install.techidaily.com/amd-gpu-update-rx-570-windows-11107-patch/"><u>AMD GPU Update: RX 570 Windows 11/10/7 Patch</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-bandicam-mastery-your-essential-checklist/"><u>In 2024, Bandicam Mastery – Your Essential Checklist</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/in-2024-learn-top-best-free-luts-for-premiere-pro/"><u>In 2024, Learn Top Best Free LUTs For Premiere Pro</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/new-in-2024-boost-channels-and-views-through-savvy-youtube-analysis/"><u>[New] In 2024, Boost Channels and Views Through Savvy YouTube Analysis</u></a></li>
<li><a href="https://driver-install.techidaily.com/easy-driver-updates-on-lenovo-ideapad/"><u>Easy Driver Updates on Lenovo Ideapad</u></a></li>
<li><a href="https://sim-unlock.techidaily.com/in-2024-top-10-vivo-v30-android-sim-unlock-apk-by-drfone-android/"><u>In 2024, Top 10 Vivo V30 Android SIM Unlock APK</u></a></li>
<li><a href="https://driver-install.techidaily.com/optimize-epson-driver-performance-in-win11/"><u>Optimize Epson Driver Performance in Win11</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720063153514-elevate-your-connections-effortlessly-with-our-driver-tools/"><u>Elevate Your Connections Effortlessly with Our Driver Tools</u></a></li>
<li><a href="https://driver-install.techidaily.com/nvidia-geforce-gtx-960-driver-version-update/"><u>Nvidia GeForce GTX 960 Driver Version Update</u></a></li>
<li><a href="https://driver-install.techidaily.com/automated-updates-for-your-pro-6-system/"><u>Automated Updates for Your Pro 6 System</u></a></li>
<li><a href="https://driver-install.techidaily.com/get-the-new-gtx-1650-windows-drivers/"><u>Get the New GTX 1650 Windows Drivers</u></a></li>
<li><a href="https://driver-install.techidaily.com/seamless-atheros-drivers-rollout-to-windows-11/"><u>Seamless Atheros Drivers Rollout to Windows 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/win-usb-driver-fixes-you-need-now/"><u>Win-USB Driver Fixes You Need Now</u></a></li>
<li><a href="https://driver-install.techidaily.com/get-secure-wireless-driver-for-your-computer-with-tp-link/"><u>Get Secure Wireless Driver for Your Computer with TP Link</u></a></li>
<li><a href="https://driver-install.techidaily.com/activate-tablet-pcs-via-new-marvell-wireless-ac-controller/"><u>Activate Tablet PCs via New Marvell Wireless-AC Controller</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-screen-saving-snapchat-memories-on-phone/"><u>[New] Screen Saving Snapchat Memories on Phone</u></a></li>
<li><a href="https://driver-install.techidaily.com/free-usb-wi-fi-adapter-for-ac1200-netgear/"><u>Free USB Wi-Fi Adapter for AC1200 Netgear</u></a></li>
<li><a href="https://driver-install.techidaily.com/bluetooth-usb-adapter-support-guide-asus-bt400/"><u>Bluetooth USB Adapter Support Guide - Asus BT400</u></a></li>
<li><a href="https://driver-install.techidaily.com/driver-for-u-are-u-fpr4500-download/"><u>Driver for U-Are-U FPR4500 Download</u></a></li>
<li><a href="https://driver-install.techidaily.com/transform-data-exchange-with-mtk-usb-drivers-for-winxp1110/"><u>Transform Data Exchange with MTK USB Drivers for WINXP11/10</u></a></li>
<li><a href="https://driver-install.techidaily.com/amplify-visuals-windows-10-plus-hp-graphics-update/"><u>Amplify Visuals: Windows 10 + HP Graphics Update</u></a></li>
<li><a href="https://driver-install.techidaily.com/mastering-windows-10-atheros-wi-fi-driver-refresh-techniques/"><u>Mastering Windows 10: Atheros Wi-Fi Driver Refresh Techniques</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/updated-terror-in-towns-selecting-the-best-8-zombie-gaming-titles/"><u>[Updated] Terror in Towns  Selecting the Best 8 Zombie Gaming Titles</u></a></li>
<li><a href="https://driver-install.techidaily.com/resolving-usbasp-driver-discrepancies-in-windows-environments/"><u>Resolving USBasp Driver Discrepancies in Windows Environments</u></a></li>
<li><a href="https://driver-install.techidaily.com/gaomon-s620-installation-quick-and-easy-steps/"><u>Gaomon S620 Installation - Quick and Easy Steps</u></a></li>
<li><a href="https://driver-install.techidaily.com/bridging-the-gap-between-new-msi-drivers-and-windows-versions/"><u>Bridging the Gap Between New MSI Drivers & Windows Versions</u></a></li>
<li><a href="https://driver-install.techidaily.com/enhance-your-design-free-secure-wacom-driver-for-windows/"><u>Enhance Your Design: Free, Secure Wacom Driver for Windows</u></a></li>
<li><a href="https://driver-install.techidaily.com/gtx-760-new-drivers-less-trouble/"><u>GTX 760: New Drivers, Less Trouble</u></a></li>
<li><a href="https://some-skills.techidaily.com/the-full-spectrum-slomo-recording-app-evaluation-for-2024/"><u>The Full Spectrum SloMo Recording App Evaluation for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamline-your-connectivity-with-one-click-adb-driver/"><u>Streamline Your Connectivity with One-Click ADB Driver</u></a></li>
<li><a href="https://driver-install.techidaily.com/efficiently-refreshing-wireless-drivers-on-pcs/"><u>Efficiently Refreshing Wireless Drivers on PCs</u></a></li>
<li><a href="https://driver-install.techidaily.com/a-step-by-step-process-to-update-intel-82579lm-on-pcs/"><u>A Step-by-Step Process to Update Intel 82579LM on PCs</u></a></li>
</ul></div>
