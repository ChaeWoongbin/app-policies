---
layout: default
title: SiteDiet Privacy Policy
---

# SiteDiet Privacy Policy

**Effective date: October 7, 2026**

This Privacy Policy applies to the SiteDiet Android app provided by **WoongSW** ("we", "us", or "our"). SiteDiet helps you limit access to selected websites for a chosen focus period.

## 1. Information processed on your device

SiteDiet stores the following information in the app's private storage on your device to provide its features:

- Your selected websites, custom domains, and blocking preferences.
- Your selected language and focus duration or scheduled end time.
- Focus session records, including start and end times, applied duration, selected sites, changes to site selections, and the reason a session ended.
- Operational settings and status information needed to manage blocking and notifications.

These settings and focus records are not uploaded by SiteDiet to WoongSW. SiteDiet does not require an account and does not include advertising SDKs, analytics SDKs, tracking pixels, or marketing trackers.

Focus records describe your blocking sessions; they are not a log of the web pages you visit. SiteDiet does not save a history of DNS queries or read website content, messages, passwords, or the contents of encrypted HTTPS connections. It displays a count of blocked DNS requests during the current session without storing a per-request browsing history.

## 2. Local VPN and DNS processing

SiteDiet uses Android's VPN service, with your approval, to process DNS requests on your device and compare the requested domain names against your selected blocking list. Requests matching that list are answered locally with a blocking response.

DNS requests handled by SiteDiet that are not blocked are sent to **Cloudflare's public DNS resolver at 1.1.1.1** to resolve domain names. This processing can include DNS requests from other apps on your device, not only your browser. Cloudflare receives the requested domain name, DNS query information, and the network source IP address used to reach its resolver. WoongSW does not operate this resolver or receive these requests on its own servers.

The current app sends these DNS requests using standard **unencrypted UDP DNS on port 53**. The local VPN permission does not make these DNS requests encrypted. Network operators or others able to observe that network connection may be able to see the DNS queries. SiteDiet does not route ordinary web traffic through a WoongSW VPN server or decrypt HTTPS traffic.

Cloudflare's processing and retention practices are described in its [Public DNS Resolver privacy notice](https://developers.cloudflare.com/1.1.1.1/privacy/public-dns-resolver/) and [Privacy Policy](https://www.cloudflare.com/privacypolicy/). Its infrastructure may process DNS requests outside your country.

You can stop this DNS processing by ending the blocking session or revoking SiteDiet's VPN permission in Android settings. Another VPN cannot be used at the same time in the same Android user profile.

## 3. Permissions

- **VPN approval:** Allows local DNS filtering while a blocking session is running.
- **Internet and network state access:** Allows DNS resolution and network-related operation.
- **Foreground service:** Keeps an active blocking session running in the background.
- **Notifications:** If you allow notifications, SiteDiet displays blocking status, remaining time, and the scheduled end time. Notification visibility is controlled by your Android settings.

SiteDiet does not request access to your contacts, camera, microphone, or precise location.

## 4. Storage, retention, and deletion

Settings and focus history remain in the app's private device storage until you delete them. SiteDiet does not apply the generic 12-month or 24-month server retention periods used in some policy templates, and WoongSW does not maintain a server copy of your focus records.

- Use **Clear history** in the history tab to delete focus records. This does not stop an active blocking session or delete your site settings.
- Remove custom domains in the site settings.
- Clear SiteDiet's app storage in Android settings to remove its locally stored settings and history.
- Uninstalling the app normally removes its local app data.

Android may back up or transfer app data according to your device, operating system, backup provider, and backup settings. Such backups may include preferences and focus history. Clearing app storage or uninstalling does not necessarily delete an existing system backup, and a backup may be restored when the app is reinstalled. Manage backups through your device or backup provider's settings.

Cloudflare controls the retention and deletion of data processed by its DNS service under its own policies.

## 5. Information you send when contacting us

If you email **jerpi053@gmail.com**, we receive your email address and the information you choose to include. We use this information to respond to your inquiry and provide support, not for marketing. Email is processed by our email provider, Google, under its [Privacy Policy](https://policies.google.com/privacy).

We retain support correspondence only as needed to handle the inquiry and meet applicable legal obligations. You may contact us to request access, correction, or deletion of personal information held in that correspondence. We do not need your app's locally stored focus history to respond unless you choose to share it.

We do not sell your personal information or share it for targeted advertising.

## 6. Security

SiteDiet uses Android's private app storage for settings and focus history. Device security, backups, and notification visibility depend on your Android configuration. DNS transmission has the limitations described in Section 2. No storage or transmission method can guarantee absolute security.

## 7. Children

SiteDiet is not intended for children under 16 years of age. We do not knowingly solicit personal information from children. If you believe a child has sent personal information to us through support correspondence, contact us so we can address it and delete it where appropriate.

## 8. This policy website

This policy page is hosted on **GitHub Pages**. Opening the page is separate from using the SiteDiet app. GitHub may process technical information, including visitors' IP addresses, to provide and secure its hosting service, as described in the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## 9. Changes to this policy

We will post updates on this page and change the effective date when this policy is revised. If app features or data processing change, we will update the policy and provide any additional notice or consent required by applicable law.

## 10. Contact

**Service provider:** WoongSW  
**App:** SiteDiet  
**Email:** [jerpi053@gmail.com](mailto:jerpi053@gmail.com)
