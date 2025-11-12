<!-- =========================================================================
README.md

Copyright © 2025 Network Pro Strategies (Network Pro™)
SPDX-License-Identifier: CC-BY-4.0 OR GPL-3.0-or-later
This file is part of Network Pro.
========================================================================== -->

<sup>[SPDX-License-Identifier](https://spdx.dev/learn/handling-license-info/): `CC-BY-4.0 OR GPL-3.0-or-later`</sup>

<a id="top"></a>

# Hardening Brave Browser

**Network Pro Strategies** (Network Pro&trade;)  
**Last Updated:** November 11, 2025

&nbsp;

## Table of Contents

1. [Download Brave Browser](#download-brave)
2. [Turn Off Telemetry](#telemetry)
3. [Block Trackers & Ads](#trackers)
4. [Block JavaScript](#javascript)
5. [Block All Cookies](#cookies)
6. [Enable Strict Fingerprinting Mode](#fingerprint1)
7. [Block Fingerprinting](#fingerprint2)
8. [Turn Off Social Media](#social)
9. [Turn Off Usage Ping](#ping)
10. [Turn Off Web3 Notifications](#web3)
11. [Change Search Engine](#search)
12. [Turn Off Save Passwords & Auto Sign-in](#passwords)
13. [Change Appearance](#appearance)

---

<a name="download-brave"></a>

### 1. Download Brave Browser from [Brave](https://www.brave.com) or GitHub

✅ [brave/brave-browser](https://github.com/brave/brave-browser)

> _For managing privacy-centric browser installations and updates, we highly
> recommend **FFUpdater**:_
>
> - F-Droid: [FFUpdater](https://f-droid.org/packages/de.marmaro.krt.ffupdater/)
> - GitHub: [Tobi823/ffupdater](https://github.com/Tobi823/ffupdater)

---

<!-- markdownlint-disable MD029 -->

<a name="telemetry"></a>

### 2. Off Telemetry ✅

![Turn Off Telemetry](https://cdn.jsdelivr.net/gh/netwk-pro/hardening-brave@refs/heads/master/src/img/telemetry.jpg 'Turn Off Telemetry')

<sub>[Back to top](#top)</sub>

---

<a name="trackers"></a>

### 3. Block Trackers & Ads (Aggressive) ✅

![Block Trackers & Ads](https://cdn.jsdelivr.net/gh/netwk-pro/hardening-brave@refs/heads/master/src/img/trackers-ads.jpg 'Block Trackers & Ads')

<sub>[Back to top](#top)</sub>

---

<a name="javascript"></a>

### 4. Block JavaScript ✅

_Enable JavaScript for that site only when needed for trusted sites_  
 ![Block JavaScript](https://cdn.jsdelivr.net/gh/netwk-pro/hardening-brave@refs/heads/master/src/img/javascript.jpg 'Block JavaScript')

<sub>[Back to top](#top)</sub>

---

<a name="cookies"></a>

### 5. Block All Cookies ✅

_Enable cross-site cookies for only that site when needed_
![Block All Cookies](https://cdn.jsdelivr.net/gh/netwk-pro/hardening-brave@refs/heads/master/src/img/cookies.jpg 'Block All Cookies')

<sub>[Back to top](#top)</sub>

---

<a name="fingerprint1"></a>

### 6. Enable Strict Fingerprinting Mode ✅

<!-- markdownlint-disable MD036 -->

_Strict fingerprinting protection is now a hidden feature_

- Navigate to `brave://flags` and search for
  `brave-show-strict-fingerprinting-mode`
- Toggle the setting to `Enabled` and select the `Relaunch` button

![Enable Strict Fingerprinting Mode](https://cdn.jsdelivr.net/gh/netwk-pro/hardening-brave@refs/heads/master/src/img/fingerprinting1.png 'Enable Strict Fingerprinting')

<!-- markdownlint-enable MD036 -->

&nbsp;

<a name="fingerprint2"></a>

### 7. Block Fingerprinting (Strict) ✅

_Change to '**Fingerprinting blocked (Standard)**' for only that site when
needed for trusted sites_  
 ![Block Fingerprinting](https://cdn.jsdelivr.net/gh/netwk-pro/hardening-brave@refs/heads/master/src/img/fingerprinting2.jpg 'Block Fingerprinting')

<sub>[Back to top](#top)</sub>

---

<a name="social"></a>

### 8. Off Social Media & other privacy settings ✅

![Turn Off Social Media](https://cdn.jsdelivr.net/gh/netwk-pro/hardening-brave@refs/heads/master/src/img/social.jpg 'Turn Off Social Media')

<sub>[Back to top](#top)</sub>

---

<a name="ping"></a>

### 9. Off Usage Ping ✅

![Turn Off Usage Ping](https://cdn.jsdelivr.net/gh/netwk-pro/hardening-brave@refs/heads/master/src/img/ping.jpg 'Turn Off Usage Ping')

<sub>[Back to top](#top)</sub>

---

<a name="web3"></a>

### 10. Off Web3 Notifications ✅

![Turn Off Web3 Notifications](https://cdn.jsdelivr.net/gh/netwk-pro/hardening-brave@refs/heads/master/src/img/web3.jpg 'Turn Off Web3 Notifications')

<sub>[Back to top](#top)</sub>

---

<a name="search"></a>

### 11. Change Search Engine ✅

![Change Search Engine](https://cdn.jsdelivr.net/gh/netwk-pro/hardening-brave@refs/heads/master/src/img/search.jpg 'Change Search Engine')

<!-- markdownlint-enable MD029 -->

> [Brave Search](https://search.bravesearch.brave.com) or a self-hosted
> [SearXNG](https://docs.searxng.org) instance is preferable. Avoid Google and
> Bing at all costs!
>
> Other options, in no particular order:
>
> - [DuckDuckGo](https://www.duckduckgo.com)
> - [Mojeek](https://www.mojeek.com)
> - [Startpage](https://www.startpage.com)
> - [Kagi](https://kagi.com)<sup>1</sup>
>
> Ecosia is also supposedly a very good, privacy-centric search engine. We're
> not as familiar with Ecosia, so we can't recommend it, but it deserves
> mention.
>
> <sup>1</sup> <sub>Kagi is a paid service. However, anecdotally we've heard the
> service is well worth the price.</sub>

<sub>[Back to top](#top)</sub>

---

<!-- markdownlint-disable MD029 -->

<a name="passwords"></a>

### 12. Off Save Passwords & Auto Sign-in ✅

![Turn Off Save Passwords & Auto Sign-in](https://cdn.jsdelivr.net/gh/netwk-pro/hardening-brave@refs/heads/master/src/img/passwords.jpg 'Turn Off Save Passwords & Auto Sign-in')

> It is a best practice to utilize a password manager rather than the built-in
> browser password management.
>
> Recommended password managers:
>
> - [Proton Pass](https:/www.proton.me/pass)
>   ([Proton AG](https://www.proton.me))
> - [Bitwarden](https://www.bitwarden.com)

<sub>[Back to top](#top)</sub>

---

<a name="appearance"></a>

### 13. Change Appearance ✅

![Change Appearance](https://cdn.jsdelivr.net/gh/netwk-pro/hardening-brave@refs/heads/master/src/img/appearance.jpg 'Change Appearance')

<sub>[Back to top](#top)</sub>

---

**Please provide feedback and suggestions by [creating an issue](https://github.com/netwk-pro/netwk-pro.github.io/issues/new/choose) or posting in [Discussions](https://github.com/netwk-pro/netwk-pro.github.io/discussions). _If you liked this list, please give it a STAR ⭐._**

<!--markdownlint-enable MD029 -->

Special thanks to the original publisher of this material,
**[@finalboss@mas.to](https://mas.to/@finalboss).**  
Forked from
[piyushkumar-prog/Hardening-Brave-Browser](https://github.com/piyushkumar-prog/Hardening-Brave-Browser).

---

<div style="font-size: 12px; font-weight: bold; text-align: center;">

[Home](https://netwk.pro) &nbsp; | &nbsp;
[Terms of Use](https://netwk.pro/terms-of-use)  
[Privacy Policy](https://netwk.pro/privacy-policy) &nbsp; | &nbsp;
[Legal](https://netwk.pro/legal)

</div>

&nbsp;

<span style="font-size: 12px; text-align: center;">

Copyright &copy; 2025  
**[Network Pro Strategies](https://netwk.pro/)** (Network Pro&trade;)

Network Pro&trade;, the shield logo, and the "Locking Down Networks&trade;"
slogan are [trademarks](https://netwk.pro/legal#trademark) of Network Pro
Strategies.

Licensed under **[CC BY 4.0](https://netwk.pro/legal#cc-by)** and
the **[GNU GPL](https://netwk.pro/legal#gnu-gpl)**, as published
by the [Free Software Foundation](https://fsf.org), either version 3 of the
License, or (at your option) any later version.

</span>

<!-- cspell:ignore piyushkumar -->
