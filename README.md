<p align="center">
  <img src="https://github.com/Balackburn/Apollo/assets/93828569/532f0b7e-8c06-483c-9d04-8b84ada7b972" alt="Apollo for Reddit Banner" />
</p>

[![Platform](http://img.shields.io/badge/platform-iOS/iPadOS/macOS-blue.svg)](https://developer.apple.com/iphone/index.action)
![Release](https://img.shields.io/github/downloads/Balackburn/Apollo/total)
![GitHub issues](https://img.shields.io/github/issues-raw/Balackburn/Apollo)

<a href="https://tinyurl.com/ApolloAltstore"><img src="https://raw.githubusercontent.com/YTLitePlus/Assets/main/Github/Buttons/Altstore/Altstore.png" width="200"></a>
&nbsp;
<a href="https://altsource.by.lao.sb/browse/?source=https%3A%2F%2Fraw.githubusercontent.com%2FBalackburn%2FApollo%2Fmain%2Fapps.json"><img src="https://raw.githubusercontent.com/YTLitePlus/Assets/main/Github/Buttons/Altstore/altsource.by.lao.sb.png"
 width="200"></a>
&nbsp;
<a href="https://balackburn.github.io/Apollo/apps.json"><img src="https://raw.githubusercontent.com/YTLitePlus/Assets/main/Github/Buttons/Altstore/URL.png" width="200"></a>

## Device Preparation

### Place Device into Developer Mode

1. Settings > Privacy & Security > Developer Mode (Bottom) 
2. Set to On
3. Restart
4. "Ready to Enable Developer Mode" Screen
5. Swipe Up to Continue and Enable
6. Enter Passcode
7. Device will restart

### Register UDID

1. Connect device to Mac and allow Data Access
2. Open Finder and Select your device (on the left side)
3. Click under the device's name until UDID shows up
4. Copy UDID and send it to me

## For Sideloading

Browse to the below url on your device's browser and install:

https://ipa.ipasign.cc:2052/download/4762b9df-8ce0-3984-05f9-815dc6c8ed31/20240804232314401

## Reddit Settings

1. Sign into your reddit account (on desktop) and go here:  
    [https://reddit.com/prefs/apps](https://reddit.com/prefs/apps)
3. Click the `are you a developer? create an app...` button
4. Fill in the fields
	* name: Use whatever
	* Choose `Installed App`
	* description: Use whatever
	* about url: Use whatever
	* redirect uri: **`apollo://reddit-oauth`**
5. `create app`

6. After creating the app you'll get a client identifier

7. Enter it in the "Reddit API Key" in the settings.

8. It currently works without Imgur settings.

## Imgur Settings
**Only required if you'll upload pics to your account. Otherwise just use mine: 29ddc3cac7f06e2**

1. If you do not have an Imgur account, please create one:  
   https://imgur.com/

2. After creating an account, create an app from the following page  
   https://api.imgur.com/oauth2/addclient

3. Authorization type: is OK with "OAuth 2 authorization without a callback URL

4. Fill in the other fields to get a "Client ID".
  
   https://imgur.com/account/settings/apps  
   You can also check the Client ID from the above link if you are logged in.

5. Enter it in the "Imgur API Key" in the settings.

  Added ability to upload and delete images to Imgur.
  Multiple images (album creation) fails at first but works the next time.

# From 

https://github.com/JeffreyCA/Apollo-ImprovedCustomApi

https://apolloapp.io/
