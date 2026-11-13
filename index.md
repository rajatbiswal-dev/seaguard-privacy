---
title: SeaGuard Firewall Privacy Policy
---

# SeaGuard Firewall Privacy Policy

_Last updated: November 13, 2026_


## Summary

SeaGuard Firewall is a local firewall for Android. It runs entirely on your device. We have no servers, no accounts, no analytics, no advertising and we do not collect, sell or share your personal data.

## How SeaGuard Firewall uses the VPN permission

SeaGuard Firewall uses Android’s VPN service (VpnService) only to apply the per-app network rules you choose. Traffic of apps you block is dropped on your device. Traffic of other apps is not routed through SeaGuard Firewall, except while the Focus Timer (for a set time or until you turn it off), the “Block all” shortcut or a schedule that blocks all apps is active, when every app is blocked until it ends or you turn it off. SeaGuard Firewall does not connect to any remote VPN server and does not inspect or store the content of your traffic.

## Data stored on your device

App Lock uses Android’s own fingerprint, face or screen-lock check. SeaGuard Firewall only learns whether the check passed; it never sees or stores your fingerprint, face data or screen-lock code. Your firewall rules, schedules, settings (including whether App Lock is on) and a short log of connections that SeaGuard Firewall blocked (app name, destination IP address, port, protocol and whether it was on Wi-Fi or mobile data; up to 300 entries kept for at most 7 days), your Allowlist choices and any running timers (temporary allow or block, Focus Timer), a count of blocked tries for each of the last 7 days, your favorite apps and a small copy of each app’s icon (so lists open quickly) are stored only on your device. The roaming guard reads the country of your SIM and of the mobile network (not your phone number or location) to tell whether you are abroad; this is not stored or sent anywhere. The Technical information page shows the state of the phone and the firewall and is only shared if you choose Copy or Send. You can clear the log in the Logs tab, and you can reset all rules in Settings. Uninstalling SeaGuard Firewall removes all of this data. SeaGuard Firewall does not upload it anywhere.

## Data usage

If you open Data Usage and allow Android’s “Usage access”, SeaGuard Firewall reads the data totals Android keeps for each app (how many bytes each app used on Wi-Fi and mobile data) to show them to you. These numbers are read on your device, are not stored by SeaGuard Firewall, and are never uploaded. You can withdraw the permission at any time in Android settings. If you set a daily, weekly or monthly data limit, SeaGuard Firewall compares the totals with it on your device, notifies you at 80% and 100%, and, only if you chose it, blocks the apps you picked until the limit resets. It also uses the split Android keeps between data used while an app is open and while it is closed to suggest apps that use data in the background. All of this happens on your device. To check for a new version, the app asks the Google Play app on your phone; SeaGuard Firewall itself sends nothing.

## Backup and export

Backup & Restore and Export CSV create text or a file only when you tap them and hand it to Android’s share sheet or file picker; you choose where it goes. SeaGuard Firewall itself sends nothing. A backup contains your block rules, schedules, favorite apps, the app lists you made (for example for the roaming guard, screen-on apps and data limits) and your firewall preferences. It never contains App Lock settings, the blocked-connection log or any usage history. A CSV export contains the blocked-connection log (time, app, destination IP, port, protocol, Wi-Fi or mobile data).

## Permissions

- **VPN (BIND_VPN_SERVICE):** to apply your firewall rules.
- **See installed apps (QUERY_ALL_PACKAGES):** to list your apps so you can set a rule for each one.
- **Notifications:** to show the firewall status, the pause button, new-app alerts, timer reminders and data-limit warnings.
- **Foreground service:** to keep the firewall running.
- **Start at boot:** to restore protection after a restart, only if you turn this on.
- **Network state:** to apply Wi-Fi and mobile-data rules.
- **Usage access (PACKAGE_USAGE_STATS):** optional, to show per-app data use, check your data limits, suggest apps that use data in the background and, if you turn them on, fill the extra lines in the status notification.
- **Fingerprint (USE_BIOMETRIC):** only if you turn on App Lock, to ask Android to check your fingerprint or face.
- **Internet:** a standard permission of the app framework; SeaGuard Firewall itself makes no network connections and uploads nothing.
- **Vibrate:** for haptic feedback.

## Children

SeaGuard Firewall is not directed to children under 13 and does not knowingly collect any personal information.

## Changes and contact

If this policy changes, the new version will be published in the app and on the store listing. Questions: support.seaguard@gmail.com
