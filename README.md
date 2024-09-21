# Device Preparation

## Place Device into Developer Mode

1. Settings > Privacy & Security > Developer Mode (Bottom) 
2. Set to On
3. Restart
4. "Ready to Enable Developer Mode" Screen
5. Swipe Up to Continue and Enable
6. Enter Passcode
7. Device will restart

## Register UDID

1. Connect device to Mac and allow Data Access
2. Open Finder and Select your device (on the left side)
3. Click under the device's name until UDID shows up

	<img src='https://github.com/penguicky/Sideload/blob/main/images/UDID.png?raw=true' alt='Finder UDID Location' width="500">

4. Copy UDID and send it to me


# Apollo
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


## Sideloading Apollo

On your device, browse to the Releases section (on the right) for Latest install URL or click below to be redirected:\
**Only works if device's UDID is registered with me.**

[Latest Signed Install URL](https://github.com/penguicky/Sideload/releases/latest)

## Reddit Settings

1. Sign into your reddit account (on desktop) and go here:  
    [https://reddit.com/prefs/apps](https://reddit.com/prefs/apps)
2. Click the `are you a developer? create an app...` button
3. Fill in the fields
	* name: Use whatever
	* Choose `Installed App`
	* description: Use whatever
	* about url: Use whatever
	* redirect uri: **`apollo://reddit-oauth`**
4. Click `create app`

5. After creating the app you'll get a client identifier

6. Enter it in the "Reddit API Key" in the Apollo app settings\
   (Apollo > Settings > General > Custom API)

	<img src='https://github.com/penguicky/Sideload/blob/main/images/redditAPI.png?raw=true' alt='Apollo Reddit Api Location' width="300">

## Imgur Settings
**Apollo currently works without Imgur settings. Only required if you'll upload pics to your account.**

1. Sign into your reddit account (on desktop) and go here:  
    [https://api.imgur.com/oauth2/addclient](https://api.imgur.com/oauth2/addclient)
2. Fill in the fields
    
	* Application name: Use whatever
	* Authorization type: Choose `OAuth 2 authorization without a callback URL`
	* Email: Use your email
	* Description: Use whatever

3. Click `submit`
4. After creating the app you'll get a client identifier "Client ID"
5. Enter it in the "Imgur API Key" in the Apollo app settings\
   (Apollo > Settings > General > Custom API)

	<img src='https://github.com/penguicky/Sideload/blob/7dbbed2f47d57e9eecea48ecd8657f6799d57ec5/images/imgurAPI.png?raw=true' alt="Apollo Imgur Api Location" width="300">

# Credits 

[Balackburn](https://github.com/Balackburn/Apollo)\
[JeffreyCA](https://github.com/JeffreyCA/Apollo-ImprovedCustomApi)\
[Apollo](https://apolloapp.io/)
