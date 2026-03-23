# Breadcrumbs Application Customizer

## Summary

This shows how to create a breadcrumb element and append it to your site via the SharePoint Framework Application Customizer extension.

## Used SharePoint Framework Version v1.11.0
<img width="1076" height="571" alt="image" src="https://github.com/user-attachments/assets/0285ed6b-89d1-4f6c-92ae-e13c1c3ff049" />
<img width="687" height="406" alt="image" src="https://github.com/user-attachments/assets/999b1da8-47ee-4512-839b-a9c8a7b1b7b8" />

## Solution
SPFx Breadcrumbs Application Customizer "Extension"

Solution|Author(s)
--------|---------
React-application-breadcrumb | Hanh Duong (CEO,(https://htdsharepointsoftwarellc.com))
React-application-breadcrumb | Elio Struyf (MVP, U2U, [@eliostruyf](https://twitter.com/eliostruyf))
React-application-breadcrumb | Swaminathan Sriram ([@SwaminathanSri3](https://twitter.com/SwaminathanSri3)) -- Upgrade to SPFx 1.11

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## Minimal Path to Awesome

- Clone this repository
- Move to folder where this readme exists
- In the command window run:
  - `npm install`
  - `gulp serve --nobrowser`
  - If there are any dependency issues, install the CLI for Microsoft 365 (https://pnp.github.io/cli-microsoft365), log in, and run the command "m365 spfx doctor" (without the quotes). Then follow the instructions to upgrade or downgrade dependency packages.
- Open your SharePoint developer site and append the provided query string parameters from the command output

> If you want, you can also test bundle and package it. The necessary feature configuration has already been done.

## Debug URL for testing

Here's a debug URL for testing around this sample.

```
?loadSPFX=true&debugManifestsFile=https://localhost:4321/temp/manifests.js&customActions={"57fa430d-8154-4b00-b285-679314f4f390":{"location":"ClientSideExtension.ApplicationCustomizer"}}
```

## Features

This project contains SharePoint Framework extensions that illustrates next features:
* Calling the SharePoint REST APIs
* Using React components in SharePoint Framework application customizer extensions
* Using an Office UI Fabric component to built the site breadcrumb component
