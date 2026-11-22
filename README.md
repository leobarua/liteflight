# Lite Flight

Lite Flight lets you draw aerial-imaging waypoint missions on saved satellite imagery and drop them straight into DJI Fly's waypoint list. It works even off-grid.

- Built for the DJI RC Pro 2 and Android 11+ smartphones on DJI RC-N2/RC-N3 controllers. Also works on the original DJI RC Pro, and on the DJI RC 2 once FreeFCC's helper apps are installed (see the manual's DJI RC 2 chapter).
- Compatible with current-generation DJI drones: Mini 4 Pro · Mini 5 Pro · Air 3S · Mavic 4 Pro
- Older DJI drones (Phantom 4, Mavic 2, Mavic Pro, Air 2S, Mavic Air 2, Mini 2, Mini 3 / 3 Pro / 4 Pro) can fly Lite Flight missions with the companion app **Lite Flyer** (limited release, see below).

## Download

Get the latest APK from the [Releases page](https://github.com/leobarua/liteflight/releases/latest).

New installs run as a 14-day trial. To get a license, email the device code shown in the app to LeoBar.

## Manual

Read the illustrated user manual at **<https://leobarua.github.io/liteflight/>** (source in [`docs/`](docs/)). It covers offline imagery, the five mission types (Area, Corridor, Circle, Quick and Orbit), mission settings including auto-capture and the flight checks, importing KML/KMZ files and loading mission plans, Shizuku setup, and sending missions to DJI Fly or Lite Flyer. The Lite Flyer manual is at **<https://leobarua.github.io/liteflight/liteflyer/>**.

A companion browser-based flight planner is now live at **<https://liteflight-planner.pages.dev/>** to create flight plans with, and deploy wirelessly onto you device. For smart phones, just scan the QR code generated for the flight plan, or for DJI RC models, enter the short code to load the flight. The browser-based manual is available at **<https://leobarua.github.io/liteflight/planner/>**

## Lite Flyer (limited release)

Lite Flyer is Lite Flight's companion app for older DJI drones that DJI Fly can't fly waypoint missions on. Lite Flight sends the mission across with one tap and Lite Flyer flies it and takes the photos.

Lite Flyer runs on a DJI SDK key that allows only a few devices, so it isn't on the Releases page. **At most 15 people will get access.** Requests are evaluated and access isn't guaranteed. To request it, email ldbarua@gmail.com or send a Facebook DM (https://www.facebook.com/leonardo.barua) with:

- Full name
- Affiliation
- Drone model, and the device it will be installed on
- 3–5 sentences on what you'll use the app for, and why you should be given one of the places

## DJI Fly Refresher

Optional companion for DJI RCs (RC Pro 2, original RC Pro, RC 2). It refreshes DJI Fly after a send without Shizuku or Wi-Fi, through an Android accessibility service. Phones don't need it. See the manual's chapter 04 before installing.

## Shizuku

Shizuku is optional. It lets Lite Flight refresh DJI Fly after sending a mission, and on Android 13+ it's needed to send at all. Get the latest Shizuku from its GitHub releases page: <https://github.com/RikkaApps/Shizuku/releases>. Shizuku is open-source software by RikkaApps, licensed under Apache 2.0.
