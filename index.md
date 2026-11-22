---
title: Privacy Policy — Meridian: Forex Session Clock
---

# Privacy Policy — Meridian: Forex Session Clock

**Effective date:** 22 November 2026
**Last updated:** 22 November 2026
**Applies to:** the Meridian — Forex Session Clock browser extension (the "Extension"), all versions

This Privacy Policy explains how the Extension handles information, and sets out the terms, disclaimers and limitations of liability that apply when you install or use it. In this policy, "we", "us" and "our" mean the developer and publisher of the Extension, and "you" means any person who installs or uses it.

**By installing or using the Extension you agree to this policy. If you do not agree, do not install or use the Extension, and uninstall it if you already have.**

---

## 1. Summary

- The Extension **does not collect, transmit, sell, rent, share or monetise any personal data or user data**.
- The Extension **makes no network requests**. It has no servers, accounts, analytics, advertising, tracking, cookies, telemetry, crash reporting or third-party software development kits.
- The only data the Extension keeps is your own **settings** and a **short-lived alert log**. Both are stored **locally in your browser on your device** and never leave it.
- The Extension is provided **"as is", free of charge, with no warranties**. We **do not promise any updates, fixes, support or continued availability**, and **we are not liable for any loss**, including trading or financial loss (see Sections 10 to 14).
- The Extension is **for information only and is not financial, investment or trading advice**.

---

## 2. Information we do not collect

We do not collect, receive, store on our systems, or have access to any of the following:

- Personally identifiable information (name, email address, postal address, phone number, age, identity documents or similar)
- Account or authentication information (the Extension has no accounts, logins or passwords)
- Financial or payment information, trading account details, balances, positions or orders
- Location data: the Extension does not use GPS, does not look up your IP address and does not request the geolocation permission
- Web browsing history, visited URLs, open tabs, page content, search queries or browsing activity
- Personal communications (emails, messages, chats)
- Health information
- User activity such as clicks, mouse movements, keystrokes or scrolling
- Device identifiers, advertising identifiers or browser fingerprints

The Extension has **no host permissions** and **no content scripts**, so it cannot read or change the web pages you visit.

---

## 3. Information stored locally on your device

To work, the Extension keeps a small amount of data in your browser's extension storage (`chrome.storage.local`). This data is created by you or by the Extension itself, stays on your device, and is **never sent to us or to anyone else**.

| Data | Purpose | Where it is stored | How long it is kept |
| --- | --- | --- | --- |
| Your settings: theme, layout, display time zone, session watchlist and order, dashboard sections, trading hours, alert and badge preferences | Remembering your choices | `chrome.storage.local`, on your device only | Until you change or reset them, or uninstall the Extension |
| Alert log: identifiers of alerts already shown (for example `open:london:<time>#15`), containing no personal information | Preventing duplicate notifications | `chrome.storage.local`, on your device only | Each entry is deleted automatically after 3 days |

- The Extension does **not** use `chrome.storage.sync`, so your settings are not synced through your browser account.
- **Time zone:** the Extension reads your device's time-zone setting through the browser's built-in internationalisation API (`Intl`) to display times correctly. This value is used in memory on your device and is not transmitted. If you choose a manual time zone, that choice is stored with your settings as described above.
- **How to delete it:** uninstalling the Extension removes all of this data. You can also use the reset option in the Extension's settings.

We cannot see, access, recover, export or delete this local data for you, because it never reaches us.

---

## 4. Permissions and why they are used

| Permission | Required? | Why it is used |
| --- | --- | --- |
| `storage` | Yes | Saves your settings and the alert log locally on your device (Section 3). |
| `alarms` | Yes | Wakes the Extension's background worker at the right times to deliver alerts and refresh the toolbar badge. This triggers local calculations only. |
| `notifications` | Optional | Requested only if you turn on alerts. Shows local desktop notifications for the market events you choose. You can revoke it at any time in your browser's settings. |

The Extension requests no other permissions.

---

## 5. Notifications

If you turn on alerts, notifications are generated and scheduled **entirely on your device** using your browser's notification system. There is no push service, no remote server and no message sent over the network. How your operating system or browser displays, stores or syncs notifications is controlled by those providers and their privacy policies, not by us.

---

## 6. Third parties, sale and sharing of data

- We do **not** sell, rent, trade, transfer or disclose user data to any third party, because we do not collect any.
- We do **not** use or transfer user data for advertising, personalised ads, creditworthiness, lending or any purpose unrelated to the Extension's single purpose.
- The Extension includes no third-party analytics, advertising or tracking code. Its fonts (Inter and JetBrains Mono) are **bundled inside the Extension** and are not downloaded from any external server.
- The Extension is distributed through browser extension stores such as the Chrome Web Store. Those stores are run by third parties who may collect information (for example install statistics or crash data) under **their own** privacy policies. We do not control that collection and are not responsible for it.

**Chrome Web Store User Data Policy.** The Extension's use of information complies with the Chrome Web Store User Data Policy, including the Limited Use requirements. Because the Extension collects no user data, no user data is transferred, sold or used for any other purpose.

---

## 7. Data security

Because no data is transmitted or stored outside your device, no data is held on any server that could be breached. Data stored locally is protected by your browser's extension storage isolation and by the security of your device. **You are responsible for the security of your own device, browser and operating system.** We cannot guarantee the security of data on devices we do not control.

---

## 8. Children's privacy

The Extension is not directed at children under 13 (or under the minimum age of digital consent where you live, such as 16 in parts of the European Union). It collects no personal information from anyone, including children. If you are under the age of majority where you live, use the Extension only with the permission and supervision of a parent or legal guardian.

---

## 9. Your privacy rights (GDPR, UK GDPR, CCPA/CPRA and similar laws)

Data protection laws such as the EU and UK General Data Protection Regulation, the California Consumer Privacy Act (as amended by the CPRA), India's Digital Personal Data Protection Act 2023, Brazil's LGPD and Canada's PIPEDA give individuals rights over personal data that organisations collect about them.

**We do not collect or process any personal data about you**, so we hold no personal data to access, correct, delete, restrict, port or object to. We do not "sell" or "share" personal information as those terms are defined under the CCPA/CPRA. You keep full control of the locally stored settings described in Section 3 and can delete them at any time by resetting or uninstalling the Extension.

If you contact us voluntarily (for example by email or through a public issue tracker), we will use the information you choose to send only to reply to you. Public issue trackers such as GitHub are run by third parties under their own policies, and anything you post there is public.

---

## 10. Not financial advice; information accuracy

- The Extension is an **informational and educational tool only**. Nothing it displays, including session times, statuses, countdowns, overlaps, activity heatmaps, "best hour" suggestions, rollover, fixings, holidays, alerts or any other content, is **financial, investment, trading, tax or legal advice**, or a recommendation to buy, sell or hold any financial instrument.
- Forex "session" hours are **market conventions**, not official exchange hours. They may differ from your broker's or platform's hours, server time, liquidity or pricing.
- Holiday calendars, daylight-saving rules and time-zone data come from public sources, rules and your browser's built-in time-zone database. They **may be incomplete, outdated, projected or wrong**. Holidays can be announced, moved or cancelled at short notice, and dates outside the verified range are projections.
- Alerts depend on your device, operating system, browser, settings, power state, permissions and other factors outside our control. **Alerts may be late, duplicated, missed or not delivered at all.** Never rely on the Extension as your only source of timing for any trading or financial decision.
- **Trading foreign exchange, CFDs and other leveraged products carries a high risk of loss and may not be suitable for everyone. You can lose more than you deposit.** Always check times and information with your broker and official sources, and get advice from a qualified professional before making any financial decision.

---

## 11. No warranty

THE EXTENSION IS PROVIDED **"AS IS" AND "AS AVAILABLE"**, FREE OF CHARGE, **WITHOUT WARRANTY OF ANY KIND**, EXPRESS, IMPLIED OR STATUTORY. THIS INCLUDES, WITHOUT LIMITATION, ANY WARRANTY OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE, NON-INFRINGEMENT, ACCURACY, COMPLETENESS, TIMELINESS, RELIABILITY OR AVAILABILITY, AND ANY WARRANTY THAT THE EXTENSION WILL BE UNINTERRUPTED, ERROR-FREE, SECURE OR FREE OF HARMFUL COMPONENTS, OR THAT DEFECTS WILL BE CORRECTED. YOU USE THE EXTENSION ENTIRELY AT YOUR OWN RISK.

---

## 12. No obligation to update, fix, support or maintain

- We provide the Extension voluntarily and **make no promise, commitment or guarantee of any future updates, bug fixes, security fixes, new features, data updates (including holiday calendars or session hours), compatibility with future browser or operating-system versions, technical support or customer service**.
- We may change, suspend, discontinue, remove from any store or stop maintaining the Extension, in whole or in part, **at any time, for any reason, without notice and without liability to you**.
- Any update, fix or support we do provide is given at our sole discretion, as a courtesy, and creates no obligation to provide more in the future.

---

## 13. Limitation of liability

TO THE MAXIMUM EXTENT PERMITTED BY APPLICABLE LAW:

1. **WE ARE NOT LIABLE FOR ANY LOSS OR DAMAGE OF ANY KIND** arising out of or in connection with the Extension, this policy, or your use of, inability to use, or reliance on the Extension or any information it provides. This applies whether the claim is based on contract, tort (including negligence), strict liability, statute or any other legal theory, and even if we were advised of the possibility of such loss.
2. This includes, without limitation, any **trading losses, investment losses, missed trades or opportunities, loss of profits, revenue, savings, business, goodwill, data or use**, losses caused by incorrect, delayed or missing times, holidays, statuses or alerts, device or software malfunction, and any **direct, indirect, incidental, special, consequential, exemplary or punitive damages**.
3. Where liability cannot be fully excluded under applicable law, our **total aggregate liability** for all claims is limited to the **amount you paid us for the Extension, which is zero (0)**, or, if a minimum amount is required by law, the smallest amount permitted.
4. Some jurisdictions do not allow certain warranties or liabilities to be excluded or limited. In those jurisdictions, the exclusions and limits above apply to the fullest extent the law allows, and nothing in this policy excludes liability that cannot legally be excluded.

---

## 14. Indemnification

To the extent permitted by law, you agree to indemnify, defend and hold harmless the developer and any contributors from and against any claims, liabilities, damages, losses, costs and expenses (including reasonable legal fees) arising out of or relating to your use or misuse of the Extension, your trading or financial decisions, your breach of this policy, or your violation of any law or third-party right.

---

## 15. Open-source licence

The Extension's source code is made available under the MIT License. Where the licence's own warranty disclaimer and limitation of liability apply, they apply in addition to Sections 11 to 14, and the stronger protection for the developer prevails to the extent permitted by law.

---

## 16. International use

The Extension works offline and transfers no data across borders. You are responsible for complying with the laws that apply where you live or use the Extension, including any laws on trading or financial activity.

---

## 17. Governing law and disputes

This policy and any dispute arising from it or from the Extension are governed by the laws of **[GOVERNING JURISDICTION, e.g. "India"]**, without regard to conflict-of-law rules. The courts of **[CITY / STATE, COUNTRY]** have exclusive jurisdiction, unless the mandatory consumer-protection law of your country of residence requires otherwise.

---

## 18. Severability and entire agreement

If any provision of this policy is held invalid or unenforceable, it will be enforced to the maximum extent permissible and the remaining provisions stay in full force and effect. Our failure to enforce any provision is not a waiver of it. This policy is the entire statement of how the Extension handles information and of the disclaimers that apply to it.

---

## 19. Changes to this policy

We may update this policy from time to time, for example if the Extension's features or permissions change. The updated version will be posted at the same URL with a new "Last updated" date. If a future version ever starts to collect or transmit user data, we will update this policy **before** that version is released and, where the law or the store's policies require it, ask for your consent. Continuing to use the Extension after an update takes effect means you accept the updated policy.

---

## 20. Contact

Questions about this policy can be sent to: **[nikunj18bansal@gmail.com](mailto:nikunj18bansal@gmail.com)**

We may respond at our discretion and do not guarantee a response time (see Section 12).
