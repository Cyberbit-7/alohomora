# Alohomora
### Alohomora is a plugin/extension that unlocks a few useful features while using the Alohomora kiosk web-view exploit. For any issues/tech support questions, use the Google Form at the bottom.

### Don't use Alohomora for any illegal activities.

### Note: The steps listed below are for Chromebooks running on ChromeOS v119 and under. For Chromebooks v120 and above, scroll to the bottom of the guide for special instructions.

## Alohomora Kiosk Web-View Exploit

### Step 1a
Go to logout screen, and turn off Wi-Fi using the control panel on bottom right.

### Step 2a
Click on one of the apps in the "apps" section on the bottom left. "Formative Lockdown Browser" has been shown to have the best results, but others may also work. Quickly press Alt+Shift+S, this should open up a control panel window. Don't click anything while waiting for the next step.

### Step 3a
Wait until a "Network not available" screen appears. Click "Accessibility", then click the "help" question mark. This will close the control panel window, but an invisible window will appear in the background.

### Step 4a
Click "Diagnose", then click "Add other Wi-Fi network" to turn Wi-Fi back on. Don't type anything into the pop-up; just wait until a "Connectivity Diagnostics" window appears. 

### Step 5a
Click on "Wi-Fi", then in the dropdown, click on "Open in settings", which will boot you into a basic Google window, which is missing a few key features. To unlock these features, you will need to to download Alohomora.

## Installing Alohomora

### Step 1b
Download the extension onto your Chromebook from https://github.com/KC728/alohomora. Click on "Releases" on the left menu, then click "Source Code (zip)" under the latest release. The extension should now download onto your Chromebook.

### Step 2b
Go to chrome://extensions, or click the puzzle piece in the top right then click "Manage extensions". Turn on "Developer mode" using the switch in the top right.

### Step 3b
Click on "Load Unpacked," then in the file prompt window, right-click on "alohomora-main," which will be a greyed-out .zip file. Click "Extract all". Then, double-click the folder also named "alohomora-main", then click once to select the folder inside. Click the "Open" button, located on the bottom right of the file prompt window.

### Step 4b
A keyboard shortcuts menu will appear. To set shortcuts, click on the pencil and copy the shortcut listed on the left. This will unlock shortcut functionality. You can also set your own shortcuts to your preferences. I suggest leaving the Ctrl+U shortcut unfilled, as this can cause issues when using apps such as Google Docs, and is not necessary except for developers.

### Step 5b
Open up a new tab, then click the "window" icon to resize the window, then click it again to reach fullscreen. You are now fully booted into Alohomora.

### Try and take 5 minutes to read the whole guide. This will save you a lot of time and suffering, and will teach you how to utilize the Alohomora to it's full potential. If you want to play Fortnite, read the guide.

## Guide

### Unlocking Google Applications
To use Google applications such as Google Docs, click on the "add user" icon, which will be the third icon from the right on the top right. Sign-in to your school account normally. 

### Connecting Bluetooth Devices
To connect Bluetooth devices such as earbuds, click on the "Bluetooth" icon, which will be the third icon from the right on the bottom left. This will open a new tab that allows you to pair, connect, and disconnect Bluetooth devices

### Exiting Full Screen While Watching Videos
One problem unique to the Alohomora exploit is that it is not possible to exit fullscreen while watching videos on websites such as YouTube and Netflix. To exit fullscreen, simply press Ctrl+T, which will open a new tab, exiting you from fullscreen.

### Exiting the Exploit
To exit the exploit and use the Chromebook normally, simply hold down the Power button on the left side of your Chromebook, then click "Sign-out"

### Circumventing Network Blocks/Firewalls
While using school Wi-Fi, network blocks for things like GeForce NOW and Coolmathgames (if anyone still plays that) may still be present. To circumvent this, you will need to download a VPN extension. Most VPN extensions are also blocked, but Windscribe has been found to work, linked here: https://tinyurl.com/28xv8jp8. Windscribe does have limited bandwidth to 10GB, but there are many promo codes that give you an additional 30 GB Each. You will also need to create a Windscribe account. uVPN also works, linked here: http://tinyurl.com/t5kktukv. The only available free servers are located in Europe, so latency and availability for websites like Netflix will be affected. The Madrid server has been found to have the lowest latency, while the Milan server retains most popular Netflix shows due to Italian entertainment laws. If you are using Windscribe, turn off the VPN in the extension bar on the top right when a VPN is not needed, such as when accessing websites that are not network-blocked.

### Taking a Screenshot
To take a screenshot or screen recording, you need to use an extension, since the Alohomora exploit unfortunately disables the normal ChromeOS screenshot capability. I highly suggest using Awesome Screenshot, linked here: https://tinyurl.com/5863bna4. The process of taking a screenshot is a bit more complicated, but is still quite simple to understand. Take a screenshot by clicking on the extension in the top right, then clicking "Capture" and then click either "Visible Part" or "Selected Area". After you take your screenshot, a new tab should appear allowing you to view and edit your screenshot. Click "Done", then click "Download". Your screenshot should now be saved in your files.

### Using Kiosk App Normally
You may sometimes need to use the kiosk app for things like standardized testing. To use the kiosk app normally, hold down the Power button on the left side of your Chromebook, then click "Sign-out" in order to exit the exploit. Then boot into the kiosk app normally.


### Web Gaming (How to play Fortnite)
Now to teach you what you are probably here to learn; how do I play Fortnite? First, you will need to turn on one of the VPN extension listed above. Then, you will navigate to either https://play.geforcenow.com/ or https://luna.amazon.com/. GeForce NOW can be used for free, but has a queue. Amazon Luna does not have any queue, but you will require an Amazon Prime subscription to use Amazon Luna. Link your Epic Games account to the web gaming site, then boot into Fortnite. This can also be used for any other games available in either GeForce Now and Amazon Luna, or any other web gaming site, although other web gaming sites are currently untested. 

### Advanced: Creating a New Window
Warning: Advanced users only! Previously, the Alohomora exploit was locked to only one window. However, through some clever usage of Javascript and Bookmarklets, this problem was solved, albiet in a slightly complicated method. First, type in about:blank into your URL bar. Press enter to load the blank tab. Next, type in javascript:(function(){window.onbeforeunload=function(){return '';}})(); into the URL bar. Chrome will automatically delete the "javascript" portion of the string, so you will need to reenter "javascript" in front of the bookmarklet string before continuing. Press enter to load the bookmarklet. Then, right-click the tab, and click "Move to new window" in the pop-up that appears.  A new window will then be created. Finally, click "Cancel" in the popup that reads "Leave site? Changes you made may not be saved." Clicking leave will close the window. You now have two unblocked windows instead of one. However the Alt+Q shortcut will only work to switch between two windows maximum. You are able to create more than two windows, but creating a third window will prevent you from accessing your first window until either the second or third window is deleted. 

## Warning
Warning: Alohomora runs off of a file that will be located inside your downloads folder. This file will either be called "alohomora-1.1" or "alohmora-main". Deleting this file will cause the extension to cease functioning. If this happens, you will need to redownload the file, and follow steps 1b-5b in order to restore functionality.

## Issue Reports/Tech Support:
https://forms.gle/wu4ocQ1q4bPGiUSr7
