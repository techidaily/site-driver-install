---
title: Patch Unsupported Installer
date: 2024-07-11T15:29:33.624Z
updated: 2024-07-12T15:29:33.624Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverInstall
description: This Article Describes Patch Unsupported Installer
excerpt: This Article Describes Patch Unsupported Installer
keywords: Unsupported Installer Issues,Installer Patch Guide,Software Updates and Fixes,Troubleshooting Unsupported Software,Patching Installers for Out-of-Support Programs,How to Apply Patch on Unsupported Software,Support for Discontinued Installers
thumbnail: https://thmb.techidaily.com/bb9b7157cde51ae69f835473474384e7538166f2945a00387bf22cab11273e3c.jpg
---

## Patch Unsupported Installer

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
<li><a href="https://driver-install.techidaily.com/download-hd-webcam-driver-logitech-c270-for-windows-1011/"><u>Download HD Webcam Driver: Logitech C270 for Windows 10/11</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-how-to-add-text-to-youtube-video/"><u>[Updated] In 2024, How to Add Text to YouTube Video</u></a></li>
<li><a href="https://driver-install.techidaily.com/windows-10-easy-steps-for-mouse-driver-upgrade/"><u>Windows 10: Easy Steps for Mouse Driver Upgrade</u></a></li>
<li><a href="https://driver-install.techidaily.com/fixing-non-operational-windows-drivers-immediately/"><u>Fixing Non-Operational Windows Drivers Immediately</u></a></li>
<li><a href="https://change-location.techidaily.com/how-to-use-life360-on-windows-pc-for-samsung-galaxy-s24-ultra-drfone-by-drfone-virtual-android/"><u>How to Use Life360 on Windows PC For Samsung Galaxy S24 Ultra? | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-xbox-gaming-captured-a-beginners-screen-recording-journey/"><u>[Updated] 2024 Approved  Xbox Gaming Captured  A Beginner's Screen Recording Journey</u></a></li>
<li><a href="https://driver-install.techidaily.com/direct-download-guide-asus-usb-bt400-driver-and-support/"><u>Direct Download Guide: Asus USB-BT400 Driver & Support</u></a></li>
<li><a href="https://driver-install.techidaily.com/effortless-pro-6-driver-rollout/"><u>Effortless Pro 6 Driver Rollout</u></a></li>
<li><a href="https://driver-install.techidaily.com/seamless-driver-integration-surface-pro-4-on-windows/"><u>Seamless Driver Integration: Surface Pro 4 on Windows</u></a></li>
<li><a href="https://driver-install.techidaily.com/get-your-tp-link-wireless-adapter-software-today-free/"><u>Get Your TP Link Wireless Adapter Software Today, FREE!</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/10-most-popular-mp3-recorder-for-windows-and-mac/"><u>10 Most Popular MP3 Recorder for Windows and Mac</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamlined-gtx-750-ti-driver-downloads/"><u>Streamlined GTX 750 Ti Driver Downloads</u></a></li>
<li><a href="https://animation-videos.techidaily.com/new-animated-business-logos-and-tools-to-create/"><u>New Animated Business Logos and Tools to Create</u></a></li>
<li><a href="https://driver-install.techidaily.com/how-to-update-nvidia-high-definition-audio-drivers-for-windows-11-10/"><u>How to Update NVIDIA High Definition Audio Drivers for Windows 11 / 10</u></a></li>
<li><a href="https://driver-install.techidaily.com/enhance-pc-with-amd-chain-drivers-windows-steps/"><u>Enhance PC with AMD Chain Drivers - Windows Steps</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-world-meal-mastery-favorite-international-creations/"><u>In 2024, World Meal Mastery  Favorite International Creations</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-your-hp-printer-software/"><u>Update Your HP Printer Software</u></a></li>
<li><a href="https://driver-install.techidaily.com/gigabyte-motherboard-driver-download-and-install-for-windows/"><u>Gigabyte Motherboard Driver Download & Install for Windows</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/why-is-ipogo-not-working-on-realme-11-pro-fixed-drfone-by-drfone-virtual-android/"><u>Why is iPogo not working On Realme 11 Pro? Fixed | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/logitech-c270-compatibility-get-the-latest-windows-firmware/"><u>Logitech C270 Compatibility: Get the Latest Windows Firmware</u></a></li>
<li><a href="https://ai-driven-video-production.techidaily.com/new-the-ultimate-guide-to-free-mov-video-editors-top-10-picks-for-2024/"><u>New The Ultimate Guide to Free MOV Video Editors Top 10 Picks for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/tp-link-wireless-adapter-driver-download-for-windows-easily/"><u>TP Link Wireless Adapter Driver Download for Windows EASILY</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/instagram-stories-tempo-tactics-speeding-up-or-slowing-down-for-2024/"><u>Instagram Stories Tempo Tactics – Speeding Up or Slowing Down for 2024</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/updated-how-to-use-obs-chroma-key-withwithout-green-screen/"><u>Updated How to Use OBS Chroma Key With/Without Green Screen</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/2024-approved-the-art-of-hiding-hashtags-on-social-media-platforms/"><u>2024 Approved  The Art of Hiding Hashtags on Social Media Platforms</u></a></li>
<li><a href="https://driver-install.techidaily.com/pave-the-way-for-secure-transactions-with-amd-on-windows/"><u>Pave the Way for Secure Transactions with AMD on Windows</u></a></li>
<li><a href="https://driver-install.techidaily.com/optimize-mice-functionality-drivers-updated-on-pc-platform/"><u>Optimize Mice Functionality: Drivers Updated on PC Platform</u></a></li>
<li><a href="https://youtube-video-recordings.techidaily.com/keep-the-vision-clear-without-rests/"><u>Keep the Vision Clear Without Rests</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/premium-8-cam-enhancers-for-clear-broadcasting-for-2024/"><u>Premium 8 Cam Enhancers for Clear Broadcasting for 2024</u></a></li>
<li><a href="https://fox-cloud.techidaily.com/updated-best-online-bunches-of-premium-quality-vector-icons/"><u>[Updated] Best Online Bunches of Premium-Quality Vector Icons</u></a></li>
<li><a href="https://some-skills.techidaily.com/updated-venturing-into-virtual-studio-technology-vst-world/"><u>[Updated] Venturing Into Virtual Studio Technology (VST) World</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720063654674-access-universal-adb-instantly-no-complications/"><u>Access Universal ADB Instantly - No Complications</u></a></li>
<li><a href="https://driver-install.techidaily.com/essential-steps-for-installing-3dconnexion-software/"><u>Essential Steps for Installing 3Dconnexion Software</u></a></li>
<li><a href="https://fake-location.techidaily.com/life360-circle-everything-you-need-to-know-on-realme-gt-3-drfone-by-drfone-virtual-android/"><u>Life360 Circle Everything You Need to Know On Realme GT 3 | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/optimizing-intel-windodrivers-on-your-pc/"><u>Optimizing Intel WindoDrivers on Your PC</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamlined-process-for-lenovo-usb-c-driver-update/"><u>Streamlined Process for Lenovo USB-C Driver Update</u></a></li>
<li><a href="https://driver-install.techidaily.com/update-acer-graphics-drivers-in-windows-10/"><u>Update Acer Graphics Drivers in Windows 10</u></a></li>
<li><a href="https://driver-install.techidaily.com/revolutionize-your-printer-efficiency-windows-11-driver-upgrade-for-hp/"><u>Revolutionize Your Printer Efficiency: Windows 11 Driver Upgrade for HP</u></a></li>
</ul></div>
