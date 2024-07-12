---
title: Alter Hardware Compatibility
date: 2024-07-11T16:29:43.646Z
updated: 2024-07-12T16:29:43.646Z
tags:
  - win11
  - win10
  - win7
categories:
  - DriverInstall
description: This Article Describes Alter Hardware Compatibility
excerpt: This Article Describes Alter Hardware Compatibility
keywords: Hardware Compatibility Guide,Device Interoperability Checklist,Cross Platform System Support,Compatible Computer Hardware Listings,Upgrading Your PC's Hardware,Peripheral Devices & Motherboard Compatibility,Hardware Expansion Options for Laptops
thumbnail: https://thmb.techidaily.com/3dc1e13d990f9f4ed1b30979889fa15d157b3da05c97d832955a545581c7804d.jpg
---

## Alter Hardware Compatibility

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
<li><a href="https://vp-tips.techidaily.com/updated-luxury-leisure-levels-review-roundup-for-2024/"><u>[Updated] LUXURY LEISURE LEVELS  Review Roundup for 2024</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-realme-narzo-60-pro-5g-phone-password-without-factory-reset-by-drfone-android/"><u>How to Unlock Realme Narzo 60 Pro 5G Phone Password Without Factory Reset?</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/beat-blast-innovative-audio-for-2024/"><u>Beat Blast  Innovative Audio for 2024</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-pokemon-go-cooldown-chart-on-honor-90-gt-drfone-by-drfone-virtual-android/"><u>In 2024, Pokémon Go Cooldown Chart On Honor 90 GT | Dr.fone</u></a></li>
<li><a href="https://driver-install.techidaily.com/accelerate-your-usb-headset-drivers-logitech/"><u>Accelerate Your USB Headset Drivers, Logitech</u></a></li>
<li><a href="https://screen-video-capture.techidaily.com/in-2024-identifying-the-best-no-cost-video-calling-apps-iosandroid/"><u>In 2024, Identifying the Best No-Cost Video Calling Apps (iOS/Android)</u></a></li>
<li><a href="https://driver-install.techidaily.com/1720063429665-get-your-tp-link-wireless-adapter-software-today-free/"><u>Get Your TP Link Wireless Adapter Software Today, FREE</u></a></li>
<li><a href="https://driver-install.techidaily.com/maximize-your-gameplay-with-updated-logitech-drivers-on-windows-7/"><u>Maximize Your Gameplay with Updated Logitech Drivers on Windows 7</u></a></li>
<li><a href="https://driver-install.techidaily.com/boost-your-desktop-gaming-update-logitech-mouse-drivers-in-win11/"><u>Boost Your Desktop Gaming: Update Logitech Mouse Drivers in Win11</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-orderly-quest-for-veiled-youtube-vaults/"><u>[New] The Orderly Quest for Veiled YouTube Vaults</u></a></li>
<li><a href="https://driver-install.techidaily.com/windows-7-upgrade-path-for-enhanced-hp-graphical-output/"><u>Windows 7: Upgrade Path for Enhanced HP Graphical Output</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-cant-ignore-these-hit-tiktok-challenges/"><u>[Updated] 2024 Approved  Can't Ignore These Hit TikTok Challenges</u></a></li>
<li><a href="https://driver-install.techidaily.com/realtek-upgrade-guide-for-optimal-pc-audio-performance/"><u>Realtek Upgrade Guide for Optimal PC Audio Performance</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-optimize-your-streaming-quality-with-these-top-4-video-boosters/"><u>2024 Approved Optimize Your Streaming Quality with These Top 4 Video Boosters</u></a></li>
<li><a href="https://driver-install.techidaily.com/secure-your-printer-update-officejet-pro-8620-drivers-in-windows/"><u>Secure Your Printer: Update OfficeJet Pro 8620 Drivers in Windows</u></a></li>
<li><a href="https://apple-account.techidaily.com/in-2024-how-to-unlock-apple-iphone-12-when-we-dont-have-apple-id-or-password-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 12 When We Dont Have Apple ID or Password?</u></a></li>
<li><a href="https://driver-install.techidaily.com/rapid-radeon-5450-driver-updates-for-win11/"><u>Rapid Radeon 5450 Driver Updates for Win11</u></a></li>
<li><a href="https://fox-links.techidaily.com/essential-iphone-app-recommendations-for-watermarking-pics/"><u>Essential iPhone App Recommendations for Watermarking Pics</u></a></li>
<li><a href="https://driver-install.techidaily.com/win11-audio-repair-rebooting-driver-can-help/"><u>Win11 Audio Repair: Rebooting Driver Can Help</u></a></li>
<li><a href="https://driver-install.techidaily.com/snappy-driver-refreshes-for-logitech-earbuds/"><u>Snappy Driver Refreshes for Logitech Earbuds</u></a></li>
<li><a href="https://driver-install.techidaily.com/step-by-step-procedure-to-update-wi-fi-adapter-driver/"><u>Step-by-Step Procedure to Update Wi-Fi Adapter Driver</u></a></li>
<li><a href="https://driver-install.techidaily.com/direct-support-toolkit-epson-2650-model-drivers-bundle/"><u>Direct Support Toolkit: Epson 2650 Model Drivers Bundle</u></a></li>
<li><a href="https://driver-install.techidaily.com/tp-link-wifi-usb-drivers-secure-no-cost-downloads/"><u>TP Link WiFi USB Drivers - Secure, No-Cost Downloads</u></a></li>
<li><a href="https://driver-install.techidaily.com/effortless-z50-70-driver-update-process/"><u>Effortless Z50-70 Driver Update Process</u></a></li>
<li><a href="https://driver-install.techidaily.com/step-by-step-guide-to-update-netgear-a6200-usb/"><u>Step by Step Guide to Update Netgear A6200 USB</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/updated-inside-track-on-elite-webinar-software-for-2024/"><u>[Updated] Inside Track on Elite Webinar Software for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/automating-and-customizing-device-drivers-a-windows-8-tutorial/"><u>Automating and Customizing Device Drivers: A Windows 8 Tutorial</u></a></li>
<li><a href="https://driver-install.techidaily.com/streamline-your-os-with-mf4770n-updates/"><u>Streamline Your OS with MF4770n Updates</u></a></li>
<li><a href="https://driver-install.techidaily.com/boost-visual-performance-new-acer-tech-for-w11/"><u>Boost Visual Performance: New Acer Tech for W11</u></a></li>
<li><a href="https://driver-install.techidaily.com/how-to-update-atheros-wifi-drivers-in-windows-11/"><u>How to Update Atheros Wifi Drivers In Windows 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/how-to-revamp-xps-hardware-using-hand-crafted-methods/"><u>How To Revamp XP's Hardware Using Hand-Crafted Methods</u></a></li>
<li><a href="https://phone-solutions.techidaily.com/easy-steps-to-recover-deleted-videos-from-xiaomi-redmi-a2-by-fonelab-android-recover-video/"><u>Easy steps to recover deleted videos from Xiaomi Redmi A2</u></a></li>
<li><a href="https://driver-install.techidaily.com/usb-driver-fixes-for-7-8-and-earlier-windows-families/"><u>USB Driver Fixes for 7, 8 & Earlier Windows Families</u></a></li>
</ul></div>
