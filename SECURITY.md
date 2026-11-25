# Security policy

Thank you for helping keep MJSCalc and its users safe.

## Supported versions

Only the **latest release** of MJSCalc receives security fixes. **Help → Check for
Updates…** in the app installs it, as do `dnf` and `apt` for the Linux packages. The
newest downloads are always at <https://mjsapps.net/mjscalc/>.

| Version | Supported |
|---|---|
| Latest release | ✅ |
| Older releases | ❌ — please update |

## Reporting a vulnerability

**Please don't report security problems in a public issue, discussion or post.** Report
them privately in either of these ways:

- **GitHub:** open the **Security** tab of this repository and click
  **Report a vulnerability**. Only you and the maintainer can see the report.
- **Email:** <support@mjsapps.net>, with "Security" in the subject.

Please include:

- the MJSCalc version and build — shown in **Help → About MJSCalc** (for example
  *3.18.3, macOS · Intel (x86_64)*), or which download or page it affects;
- your operating system and version;
- what the problem is and the steps to reproduce it, and what an attacker could do with it.

## What happens next

- You'll get a reply **within 3 business days** confirming the report was received.
- We'll keep you updated while we investigate, and tell you whether the report is
  accepted or declined and why.
- Fixes are released as a new version, delivered through Check for Updates, `dnf` and
  `apt`. With your permission, we're glad to credit you in the release notes.
- Please give us a reasonable time to release a fix before sharing details publicly.

## Scope

- The MJSCalc apps for macOS, Windows and Linux, and their installers and packages.
- The update information MJSCalc downloads (`update-*.json`) and the signed `dnf` and
  `apt` repositories at <https://msanty573.github.io/OmniCalc-Downloads/>.
- The browser demo at <https://mjsapps.net/mjscalc/try/>.

## How MJSCalc handles your data

MJSCalc works entirely on your computer. Your calculations, budgets, plans and settings
are stored locally and are never sent anywhere. The app's only network connection is
**Check for Updates**: it downloads MJSCalc's update information and, when you choose to
update, the new version — both over HTTPS from GitHub, checked against a SHA-256 checksum
before use. The automatic daily check can be turned off in the **Help** menu. The browser
demo runs in your browser the same way: what you type stays on your device.
