# Sable Paint — Privacy Policy

**Last updated: 2026-06-22**

Sable Paint ("the Software") is a desktop painting application developed by
Stephen Schirle ("we", "us"). This policy explains what data the Software
involves and how it is handled. The short version: Sable Paint is built to
run on your own device, your artwork stays with you, and we do not profile
you or sell your data.

## 1. Summary

- Your artwork and files stay on your device. We do not upload, access, or
  store them.
- We do not profile you, track which features you use, or serve advertising.
  The only data we record is one coarse, anonymous data point per update
  check (see Section 3).
- Normal network activity is limited to checking for updates and — if you
  buy a license — activating and periodically re-validating your license key.
- A few optional features (off by default) talk to third parties only when
  you turn them on.
- We do not sell or rent your personal information.

## 2. Your artwork and files

Everything you create or open in Sable Paint — images, layers, brushes,
projects — is stored locally on your device. It is never transmitted to us
and we have no ability to access it. You are responsible for keeping your
own backups.

## 3. Data the Software handles

**License keys.** When you activate a paid license, the Software sends your
license key, an organization identifier, and a device label (your computer's
name, so you can tell your devices apart in your account portal) to our
licensing provider, **Polar**, to register this device and verify the key.
The Software re-validates the key with Polar in the background on later
launches; once verified it keeps working offline for up to 14 days between
checks. Polar returns your associated name (shown in-app as "Licensed to …")
and the key's status. That verdict is cached locally on your device. You can
free a device's slot at any time from your Polar customer portal or with
"Deactivate this device" in the Software. (If you instead obtained the
Software through Steam, no key is involved — see below.)

**Update checks.** The Software periodically checks whether a newer version
is available by contacting our update service (`api.sablepaint.com`, run on
Cloudflare). That service records one coarse, anonymous data point per
check — the app version, a free/paid flag, and an approximate country derived
at the network edge — and then serves the update manifest. No IP address is
stored and nothing identifying you personally (no name, email, or license id)
is sent; the free/paid flag is resolved entirely offline from your installed
license. If that service is unavailable, the Software falls back to fetching
the manifest directly from GitHub Releases (no logging). Installers are
downloaded from GitHub Releases; as with any web request, the host receives
your IP address in order to serve the file. See GitHub's and Cloudflare's
privacy statements for how they handle request logs.

**Optional Discord features (off by default).** These transmit data only if
you enable and use them:

- *Rich Presence* shares a "now painting" status with the Discord client
  running on your own computer.
- *Share to Discord* uploads an image you choose to a Discord webhook URL
  that you configure.

When used, these are subject to Discord's privacy policy.

**Steam.** If you obtained the Software through Steam, your ownership and
entitlement are handled by Steam and are subject to Valve's privacy policy.

## 4. Purchases

If you purchase a license, the transaction is handled by **Polar**
(polar.sh), which acts as the merchant of record for Sable Paint and
handles payment processing and any applicable sales tax or VAT under its own
privacy policy. We do not receive or store your full payment details. We
receive only the limited information needed to issue and support your
license, such as your name, email address, and license/activation status.

## 5. What we do not collect

We do not profile you, do not track which tools or features you use, do not
serve advertising, and do not use tracking cookies (it is a desktop
application). Aside from the single coarse, anonymous data point per update
check described in Section 3 (app version, free/paid flag, approximate
country), we collect no usage analytics or telemetry, and we do not sell,
rent, or trade your personal information.

## 6. Third-party services

Depending on the features you use, the Software may interact with:

- **Polar** — our licensing provider and merchant of record; handles
  purchases, license-key issuance, and online key activation/validation.
- **Cloudflare** — runs our update-check service (`api.sablepaint.com`).
- **GitHub** — hosting software updates and installer downloads.
- **Discord** — optional Rich Presence and image sharing, only when enabled.
- **Steam / Valve** — only if you obtained the Software via Steam.

Each of these operates under its own privacy policy, which governs the data
it handles.

## 7. Data retention

License and configuration data are stored locally on your device. You can
remove them by uninstalling the Software and deleting its data folder.

## 8. Children

Sable Paint is a general-purpose creative tool and is not directed to
children under 13. We do not knowingly collect personal information from
children.

## 9. Your rights

We hold little to no personal information about you on our own systems.
Depending on where you live (for example, under the GDPR or the CCPA/CPRA),
you may have rights to access, correct, or delete personal information a
business holds about you. Because most data stays on your device, you can
exercise much of this yourself by managing or deleting your local files. For
anything else, contact us at the address below.

## 10. Changes to this policy

We may update this policy from time to time. Material changes will be
reflected by updating the "Last updated" date above, and where appropriate
surfaced in the Software.

## 11. Contact

Questions about this policy or your data: **hello@sablepaint.com**
