---
title: Adjust Unsupported Software Package
date: 2024-07-03T05:11:20.553Z
updated: 2024-07-04T05:11:20.553Z
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
<li><a href="https://driver-install.techidaily.com/windows-fusion-reinstating-usb-port-functions/"><u>Windows Fusion: Reinstating USB Port Functions</u></a></li>
<li><a href="https://driver-install.techidaily.com/jumpstart-new-logitech-mouse-features-via-win11-update/"><u>Jumpstart New Logitech Mouse Features via Win11 Update</u></a></li>
<li><a href="https://driver-install.techidaily.com/wacom-intuos-4-driver-free-download-for-windows-100-safe/"><u>Wacom Intuos 4 Driver Free Download for Windows [100%% Safe]</u></a></li>
<li><a href="https://driver-install.techidaily.com/elevate-brother-mfp-precision-on-windows-11/"><u>Elevate Brother MFP Precision on Windows 11</u></a></li>
<li><a href="https://driver-install.techidaily.com/samsung-ssd-driver-issues-in-windows-solved/"><u>Samsung SSD Driver Issues in Windows [Solved]</u></a></li>
<li><a href="https://driver-install.techidaily.com/guide-to-get-windows-11-compatible-canon-driver-packs/"><u>Guide to Get Windows 11 Compatible Canon Driver Packs</u></a></li>
<li><a href="https://driver-install.techidaily.com/tech-tip-keeping-dells-audio-fresh-and-compatible/"><u>Tech Tip: Keeping Dell's Audio Fresh and Compatible</u></a></li>
<li><a href="https://driver-install.techidaily.com/revise-intel-windodrivers-guide/"><u>Revise Intel WindoDrivers Guide</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/how-to-unlock-apple-iphone-15-pro-without-passcode-or-face-id-by-drfone-ios/"><u>How to Unlock Apple iPhone 15 Pro without Passcode or Face ID</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-2024-approved-enhance-tiktok-velocity-with-these-hacks/"><u>[Updated] 2024 Approved  Enhance TikTok Velocity with These Hacks</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-viral-beats-top-tiktok-hits-for-a-dance-off/"><u>[Updated] Viral Beats  Top TikTok Hits for a Dance Off</u></a></li>
<li><a href="https://some-techniques.techidaily.com/in-2024-ideal-shade-modifier-software/"><u>In 2024, Ideal Shade Modifier Software</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/2024-approved-linux-listens-well-the-best-free-software-and-practices-for-capturing-exceptional-soundtracks/"><u>2024 Approved Linux Listens Well The Best Free Software and Practices for Capturing Exceptional Soundtracks</u></a></li>
<li><a href="https://snapchat-videos.techidaily.com/new-in-2024-snapchats-creative-frontier-mastering-more-than-120-stories-with-individual-flair/"><u>[New] In 2024, Snapchat's Creative Frontier  Mastering More than 120 Stories with Individual Flair</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/in-2024-12-proven-ways-to-increase-youtube-views/"><u>In 2024, 12 Proven Ways to Increase YouTube Views</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-best-10-sound-boosters-for-android-and-ios-sound-booster-app/"><u>Updated Best 10 Sound Boosters for Android and iOS-Sound Booster App</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-10-easy-to-use-frp-bypass-tools-for-unlocking-google-accounts-on-samsung-galaxy-a05s-by-drfone-android/"><u>In 2024, 10 Easy-to-Use FRP Bypass Tools for Unlocking Google Accounts On Samsung Galaxy A05s</u></a></li>
</ul></div>
