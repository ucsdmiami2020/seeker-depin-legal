# Privacy Policy

_Last updated 2026-09-27_

## Summary

Seeker DePIN Explorer does not collect, store, transmit or sell any personal data. The app has no account system, no analytics SDK, no advertising SDK, no crash-reporting service and no backend of its own. Everything you see is bundled inside the app.

## Data the app processes on your device

Favourites, compare selections, the guided tour and anything typed into the suggestion form are kept in memory only and are discarded when the app closes. Search text is processed locally and never leaves the device. The app does not read your wallet, contacts, location, files, camera, microphone or clipboard.

## The one setting saved on your device

If you tick "Don't show this again" after the opening film, that single choice is written to this app's private storage so it can be honoured next time you open the app. It is the only thing the app saves. It holds no personal data, no identifier and no record of what you looked at; it is readable only by this app, is excluded from Google backup, and is deleted when you uninstall. You can also delete it at any time without uninstalling: Android Settings → Apps → Seeker DePIN Explorer → Storage → Clear storage. Playing the film again from the help button does not change it.

## Network access

Until you connect a wallet, the app makes no network requests of its own. When you tap a vendor or documentation link, the page opens in an Android Custom Tab (Chrome) or your default browser over HTTPS. From that point the vendor's own privacy policy applies; we do not receive any information about what you do there. Only a fixed allow-list of vendor domains can be opened. If you connect a wallet, the app queries a public Solana RPC endpoint over HTTPS to read balances for that address — see "Wallet and on-chain data" below.

## Permissions

The app requests no dangerous Android permissions — nothing that Android prompts you to approve, and no access to your camera, microphone, location, contacts, photos or files. The manifest declares five: INTERNET (to open links and read public chain data), VIBRATE (light haptic feedback), ACCESS_NETWORK_STATE (to tell whether you are online), WAKE_LOCK (used by the video player for the opening film), and one signature-level permission Android generates automatically for this app’s own internal receivers. Backup of app data to Google is disabled.

## Wallet and on-chain data

Connecting a wallet is optional and off by default. If you connect one, the app uses Mobile Wallet Adapter to ask your wallet app (or Seed Vault on a Seeker) to share a public address. The app never sees, requests or stores your seed phrase or private keys, and it never creates or submits a transaction — the only signature it can ask for is an off-chain text message you read first. Your address and the authorisation token are held in memory for the session and are cleared when you disconnect or close the app. To show balances, the address is sent to a public Solana RPC endpoint (api.mainnet-beta.solana.com or api.devnet.solana.com, or an endpoint configured at build time); that provider necessarily sees the address and your IP address and is governed by its own policy. Anything you sign or hold on-chain is public data on Solana.

## Suggesting a device or a correction

The suggestion form is optional. Everything you type stays in memory on this device and is composed into text locally — no draft is written to storage and the app sends nothing itself. When you tap "Continue to GitHub", your browser opens a new GitHub issue with that text filled in; you review it and decide whether to post it. Anything you post there is PUBLIC and is handled by GitHub under its own privacy policy, including your GitHub account details. Please do not include personal information. If you give a handle for credit, it may appear in the app's release notes. The alternative "Share the text instead" button hands the same text to whichever app you choose.

## Children

The app is informational and suitable for general audiences. It is not directed at children under 13 and collects no data from anyone.

## Changes and contact

We will update this policy if the app's data practices change, and note the date above. Questions: rchac005@gmail.com.

---
Rene Chacon · ucsdmiami2020.skr · rchac005@gmail.com · https://ucsdmiami2020.github.io/seeker-depin-legal/
