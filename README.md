# ES-BasicHUD - A FiveM HUD for EYES STORE Server

Welcome to ES-BasicHUD, a feature-packed FiveM Heads-Up Display (HUD) designed to enhance your gaming experience on the EYES STORE server.

![eyestore](https://github.com/raiderss/es-basichud/assets/53000629/a7f5ce11-55f6-45b0-9bb6-2ee3e2077eaa)



## Features
- Clean and minimalistic design.
- Essential information at a glance.
- Customizable elements for your preferences.

## How to Install
1. Download the latest release from the [Releases](https://github.com/raiderss/es-basichud/releases) page.
2. Extract the files into your FiveM resources folder.
3. Add `start es-basichud` to your `server.cfg` file.

## Discord Community
Join our Discord community for support and updates:
[![Discord](https://img.shields.io/badge/Discord-ES%20Community-7289DA.svg)](https://discord.gg/EkwWvFS)

## Tebex Store
Browse our Tebex store for premium features and support:
[![Tebex](https://img.shields.io/badge/Tebex-EYE%20STORE-00A2FF.svg)](https://eyestore.tebex.io/)

## Contributors
- **_ESCKaybeden#0488_**
- **_! Raider#0101_**

## Tags
#FiveM #Gaming #HUD #EYESSTORE #ESBasicHUD


There are special notification system that use it to trigger the notification

[1]

   ```exports[GetCurrentResourceName()]:Notification('NOTIFICATION', 'To purchase the product visit <span style="color: #FF5733;">https://</span><span style="color: #33B1FF;">dark</span><span style="color: #33FF57;">-store</span><span style="color: #FFD833;">.tebex.io</span>``` you can trigger this notification with export, we are happy and proud to serve you.')


   ```RegisterNetEvent('HudNotification') -- Trigger ==> Export
   AddEventHandler('HudNotification', function(Type, Header,Message)
      exports[GetCurrentResourceName()]:Notification(Header, Message)
   end)```
