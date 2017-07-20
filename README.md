# Trustroots Expo.io Mobile App

Trustroots.org mobile app built with Expo.io

Getting started
---------------

#### There are two options:
1. Follow [these instructions](https://docs.expo.io/versions/introduction/installation.html) to instal Expo XDE. This is easier path to get everything up and running.
2. Install exp command line utility: `npm install -g exp`

#### Before you start:
1. You need NPM and Node. Install them. Currently it's recommended to use NPM v3 or v4, because there are still some defects in NPM v5.
1. Run `npm install` in project directory

#### If you use Expo XDE and develop against physical phone:
1. Get an expo account. You register from Expo web site or by using command line utility.
1. Install Expo XDE to your development machine
2. Install Expo App to your mobile phone
3. Open App in Expo XDE. It should start compiling it.
4. Connect your mobile phone to development server. In XDE there is share button when you click it you should see QR code you can scan with Expo App. Command line utility prints QR code to console.

#### If you use `exp` commandline utility and develop against physical phone:
1. Get an expo account. You register from Expo web site or by using command line utility.
1. Install exp `npm install -g exp`
1. in project directory `exp start --tunnel --android` (you may also use --lan if you development machine and mobile phone are in same network)  
1. Install Expo App to your mobile phone
1. Open mobile app and scan QR code

#### Running in emulator
If you prefer emulator instead of using physical phone check out [instructions form Expo site](https://docs.expo.io/versions/introduction/installation.html).

## License
MIT
