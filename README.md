# ChickencamiOS

## What is this app?
By default when uploading a gallery photo to Snapchat either to a friend or story, it will either send via chat or add a annoying watermark to your story. Chickencam eliminates this, by using Snapchat's developer kit you could completely bypass this.
### Use this to:
* Upload stock camera photos/videos without shitty snapchat quality
* High Quality Advertisments
* Custom GIF/Stickers

## Why this App?
People in the past have created similar apps and charged people hundreds of dollars just to use it. ChickenCam is completely free and open source so it will stop sketchy scammers

## Will I get banned for using this?
It is known that passed Snapchat tweaks would result in a ban, for example Casper, Snaptools, etc. However because this is directly from Snapchat's developer kit there is absolutely no chance of being banned. **Keep in mind there is a risk of someone reporting you for uploading something "nasty" -- be careful of who's on your friend's list.**

## Installation - https://www.youtube.com/watch?v=7yo7Z1NSAzY&feature=youtu.be
1. Start up Mac or VMware

2. Install xcode via app store

3. Start terminal and paste the following

  3A. xcode -select --install 
  
  3B. /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
  
  3C. When you enter password, it will be invisible but just hit enter after you do.
  
4. Close terminal completely and drag the application icon to task bar.

  4A. Open terminal once again. Right click the icon on task bar and Start New with Profile. Choose Honybrew
  
5. After Honeybrew opens paste the following:

  5A. Brew Install Ruby
  
6. Back to normal terminal. Paste: Sudo gem install cocoapods

7. Download and extract folders from github to desktop

  7A. Right click the folder "install first" and New Terminal at Folder. Type the following:
  
  7B. Bundle Install  *Hit Enter*
  
  7C. Pod Install  *Hit Enter*
  
  7D. Move main folder out completely to desktop.
  
  7E. Go into "install first" folder and move "pods" to the main folder and replace all.
  
8. Right click main folder and click New Terminal at folder. Type the following

  8A. Pod Install *Enter*
  
  8B. Pod Update *Enter*
  
  8C. Close terminal. Open CReativeKitSample.xcworkspace
  
9. Open "Signing and Capabilities"

  9A. Sign in with a apple ID
  
  9B. Type your own bundle ID. This has to be unique so come up with your own.
  
10. Go to Snapkit and create a account. Create a new app.

  10A. Scroll down to Development Enviroment
  
  10B. Type the same Bundle ID you typed in xcode into Snapkit
  
  10C. Copy the long code right below the three boxes.
  
  10D. Add your Snapchat username to "Demo Users" at the bottom of the page
  
11. Go back to xcode and into "Info" tab. Find SCSDKClientID and paste the code into "PASTEAUTHCODEHERE"

12. Hit the Play button at the top left

13. Go on your iPhone settings. General -> Device Management -> Your email -> Trust App.

14. That's it, Enjoy!

## If you don't want your stories to show "from Camera"
1. Upload image/video using the app.
2. Edit the photo however you want
3. Save the photo to memories
4. Immediately upload the photo to your story.

  
  
