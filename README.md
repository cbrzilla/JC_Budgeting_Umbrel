# JC Budgeting Umbrel App Store

## What This Repo Is
This is a custom Umbrel Community App Store repo for JC Budgeting Server.

<p align="left">
  <a href="https://www.youtube.com/watch?v=zbjzAUdrEmU" target="_blank">
    Watch the Intro to JC Budgeting Video<br>
    <img src="https://img.youtube.com/vi/zbjzAUdrEmU/maxresdefault.jpg" alt="Watch the Intro to JC Budgeting video" width="300"/>
  </a>
</p>

## App ID
- Store ID: `cbrzilla`
- App ID: `cbrzilla-jc-budgeting-umbrel`

## What The App Does
- builds the JC Budgeting Server directly on Umbrel
- pulls a prebuilt JC Budgeting Server image from GitHub Container Registry
- stores databases and server config in persistent Umbrel app data
- exposes the setup page through the Umbrel UI
- exposes the direct JC client/server connection on port `5099`

## How To Use
1. Add this GitHub repo as a Custom App Store in Umbrel.
2. Wait for the Publish Umbrel Image GitHub Action to complete successfully.
   If Umbrel keeps returning to the Install button, the container image tag usually has not been published yet.
3. Open the JC Budgeting App Store entry.
4. Install JC Budgeting Server.
5. Open the app in Umbrel and go through /server.
6. Install JC Budgeting clients from: https://github.com/cbrzilla/JC_Budgeting_Client
7. Connect the JC Budgeting desktop or phone client to your Umbrel device on port 5099.

## Links
- Umbrel repo: https://github.com/cbrzilla/JC_Budgeting_Umbrel
- Client installs: https://github.com/cbrzilla/JC_Budgeting_Client
