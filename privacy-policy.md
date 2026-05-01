---
layout: page
title: Privacy Policy
---

# Privacy Policy for Freedom VPN

Last updated: May 1, 2026

Freedom VPN is an Android VPN client for Xray/VLESS configurations. This policy explains what data the app processes, what is stored on your device, and what third-party services may receive data when the app works.

## Summary

Freedom VPN does not include advertising SDKs, analytics SDKs, or crash reporting SDKs. The app does not require an account and does not send personal data to a developer-operated backend.

Because this is a VPN app, network requests made through the VPN may be visible to the VPN/proxy servers you choose to use and to the websites or services you access. Freedom VPN does not operate those third-party VPN/proxy servers.

## Data Stored on Your Device

Freedom VPN stores app settings and operational data locally on your device, including:

- selected network mode;
- downloaded VLESS configuration links, server names, and source names;
- connection status, last error, and connection details;
- active exit IP address and country shown in the app;
- server health data such as success/failure counts, recent check times, and latency estimates.

This data is used to connect the VPN, choose working servers, show connection status, and avoid repeatedly trying failing servers. It is stored in the app's private local storage. Android backup is disabled for this app.

You can delete this local data by clearing the app's storage or uninstalling the app.

## VPN Traffic

When you enable the VPN, Android routes traffic through the VPN tunnel created by Freedom VPN and the selected Xray/VLESS configuration. Freedom VPN itself does not log, inspect, sell, or share your browsing history.

The remote VPN/proxy server provider may be able to see technical connection metadata, such as your IP address and connection times. Destination websites and services may also receive your requests as they normally would. Encrypted HTTPS traffic remains encrypted between your device and the destination service, subject to the normal behavior of the destination app or website.

Use only VPN/proxy servers and subscription sources you trust.

## Network Requests Made by the App

Freedom VPN makes network requests that are necessary for app functionality:

- subscription downloads from public mirrors of `igareck/vpn-configs-for-russia`, including GitHub raw content, jsDelivr, Statically, and GitHack mirrors;
- connectivity probes to `https://max.ru` and `https://cp.cloudflare.com/generate_204` to detect the available network mode;
- IP and country lookups from `ipinfo.io`, `ipapi.co`, `ifconfig.co`, and `api.ipify.org` to show the current exit IP information.

These third-party services may receive standard technical information from your device or network request, such as IP address, user agent, request time, and requested URL. Their handling of that information is governed by their own privacy policies.

## Support Logs

Freedom VPN can generate a diagnostic log only when you choose to share logs from the app. The log may include:

- app version;
- Android version and device model;
- current network mode and VPN status;
- last error and connection detail;
- active exit country;
- recent app log output.

Support logs may contain technical details that could be sensitive. Review logs before sending them. Logs are shared only through the Android share sheet or email app you choose.

## Permissions

Freedom VPN requests these Android permissions:

- Internet access, to download subscriptions, perform connectivity checks, look up exit IP information, and connect the VPN;
- network state access, to detect whether a usable network is available;
- foreground service access, to keep the VPN tunnel running;
- notification access on supported Android versions, to show the active VPN notification;
- receive boot completed, to support scheduled subscription refresh behavior after device restart;
- VPN service binding, required by Android for VPN apps.

## Children

Freedom VPN is not directed to children and does not knowingly collect personal information from children.

## Changes

This policy may be updated when the app's behavior changes. Updates will be published on this page with a new "Last updated" date.

## Contact

For privacy questions or support, contact: [ariurn@gmail.com](mailto:ariurn@gmail.com)
