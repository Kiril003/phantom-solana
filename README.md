<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/img/mark-dark.svg">
    <img alt="Nightpost" src="docs/img/mark-light.svg" width="48">
  </picture>
  <br><b>Nightpost</b>
</p>

<p align="center">
  <img src="docs/img/banner.jpg" alt="Everything a phone is for, joined into one space: people in circles, moments for one circle, the wallet on Solana and your own look, on four phones running build 17." width="100%">
</p>

<p align="center">
  <a href="https://youtu.be/HMCDmwgEBbk"><b>Demo (2:19)</b></a> ·
  <a href="https://youtu.be/adhv_zvUgwE"><b>Pitch (1:54)</b></a> ·
  <a href="docs/nightpost-deck.pdf"><b>Deck (PDF)</b></a> ·
  <a href="https://github.com/Kiril003/phantom-solana/raw/main/nightpost.apk"><b>Android APK</b></a> ·
  <a href="https://phantom-os.dev"><b>Website</b></a>
</p>

<p align="center">
  <img alt="Build 17" src="https://img.shields.io/badge/build-17-F2A93B?style=flat-square&labelColor=0B0907">
  <img alt="Solana devnet" src="https://img.shields.io/badge/Solana-devnet-14F195?style=flat-square&labelColor=0B0907">
  <img alt="Android 10+" src="https://img.shields.io/badge/Android-10%2B-E9D2A6?style=flat-square&labelColor=0B0907">
  <img alt="8,301 tests" src="https://img.shields.io/badge/tests-8%2C301-E9D2A6?style=flat-square&labelColor=0B0907">
</p>

---

## Everything your phone is for, joined

You talk, share, sort people into circles, find places, plan the evening and pay. Today each of those jobs lives in a different app, and you carry the context between them by hand.

**Nightpost keeps them in one space**, with an assistant across it. A plan with friends goes from "let's meet" to a settled bill in one chat: the place, who's in, the split by dish and each person's payment on Solana.

## On the phone, build 17

<table>
  <tr>
    <td align="center" valign="top" width="33%"><img src="docs/img/screens/today.jpg" alt="Today: Moments row, circle tabs and conversations." width="230"><br><sub><b>Today</b><br>Moments, circles, conversations</sub></td>
    <td align="center" valign="top" width="33%"><img src="docs/img/screens/chat.jpg" alt="A chat with a photo, a voice note and a reaction." width="230"><br><sub><b>Talk and share</b><br>Photos, voice notes, calls</sub></td>
    <td align="center" valign="top" width="33%"><img src="docs/img/screens/moment.jpg" alt="New moment with the audience picker: only me, chosen people, circles, all contacts." width="230"><br><sub><b>Moments</b><br>You choose who sees each one</sub></td>
  </tr>
  <tr>
    <td align="center" valign="top" width="33%"><img src="docs/img/screens/plan.jpg" alt="Group chat with a meetup card: place, time, I'm in, maybe, I'm out, and a bill card below." width="230"><br><sub><b>Plan it in the chat</b><br>Place, time, who's in</sub></td>
    <td align="center" valign="top" width="33%"><img src="docs/img/screens/split.jpg" alt="Bill split by dish: each person ticks what they had and pays their share in USDC." width="230"><br><sub><b>Split by what you had</b><br>Pay your share in USDC</sub></td>
    <td align="center" valign="top" width="33%"><img src="docs/img/screens/assistant.jpg" alt="Assistant draft: send 5 USDC to Daniel, confirmed only with a fingerprint." width="230"><br><sub><b>Ask once, you confirm</b><br>The assistant drafts, your fingerprint sends</sub></td>
  </tr>
  <tr>
    <td align="center" valign="top" width="33%"><img src="docs/img/screens/wallet.jpg" alt="Wallet with USDC, EURC and SOL cards, marked Test." width="230"><br><sub><b>Wallet</b><br>USDC, EURC and SOL, test funds</sub></td>
    <td align="center" valign="top" width="33%"><img src="docs/img/screens/look.jpg" alt="Appearance: theme, accent colour and a wallpaper for each chat." width="230"><br><sub><b>Make it yours</b><br>Theme, accent, wallpaper per chat</sub></td>
    <td align="center" valign="top" width="33%"><img src="docs/img/screens/place.jpg" alt="A place page with hours and menu, run by the place itself." width="230"><br><sub><b>Places</b><br>Pages run by their owners</sub></td>
  </tr>
</table>

<sub>Frames from the demo, recorded on a test phone running build 17. Test contacts and an invented place; money is Solana devnet test funds.</sub>

## What is built, and what is next

| | Build 17, on the phone today | Next |
|---|---|---|
| **Talk** | Chats without a phone number, groups up to 32, photos, voice notes, calls | Group calls from the group header |
| **People** | Circles: close, friends, work, study, in your own order | |
| **Moments** | Share with one circle, chosen people or everyone | |
| **Map** | Friends who chose to share, on-device routes | Places in every city |
| **Plans** | Meetup card in the group: place, time, I'm in, on my way | |
| **Money** | Pay a person in the chat, split a bill by dish; USDC, EURC and SOL; your fingerprint sends | Mainnet after an independent audit |
| **Assistant** | Drafts a payment from one sentence; only your fingerprint sends it | |
| **Places** | Pages run by their owners, with hours and menu | |
| **Your look** | Theme, accent and a wallpaper for each chat | |

## Why Solana

Money between people is small, frequent and social. It needs a transfer that settles in seconds, costs a fraction of a cent and is signed on the phone.

| | How Nightpost uses it | Status |
|---|---|---|
| **USDC and EURC** | People pay in dollars or euros, not a coin whose price moves while they pay. | Built, devnet |
| **TransferChecked + Memo** | Each share of a bill is its own transfer, and the bill id travels in an SPL Memo (`nightpost-bill:v1:<id>`), so the chain shows who paid their part. | Built, devnet |
| **Keys on the phone** | Built-in wallet with keys in the Android Keystore. On Seeker: Mobile Wallet Adapter and Seed Vault. | Built |
| **Seeker Genesis Token and SKR** | Read-only: a Seeker badge and the SKR stake tier on the profile. SKR exists only on mainnet. | Built, read-only |
| **Fee payer** | The server pays the network fee, so friends never need SOL. | Built and tested, not switched on yet |
| **Solana dApp Store** | Publisher KYC is done; the listing is next. | Next |

## How to verify

- **Install it.** [nightpost.apk](https://github.com/Kiril003/phantom-solana/raw/main/nightpost.apk), build 17, Android 10+, Solana devnet. Checksums in [docs/RELEASES.md](docs/RELEASES.md).
- **Check the chain.** [A 25 USDC bill share sent from the chat](https://explorer.solana.com/tx/RkJ9GoQ5jSyvF86BjHWmaVZ38NRkk6Tb9brBHsgP72F69YaG6crDJR27VEKL7Xe3s5zZ257VQbWY2mfsfQQP8wC?cluster=devnet): create the token account, `transferChecked`, and the Memo with the bill id. [A 0.05 SOL transfer](https://explorer.solana.com/tx/43L7ov5KPG4MNcsduLKyo9fU41wCjAU76pLMHEoXr5j5kJvhc8BZ2KsgMV5uGSjkL5hg7dDkijoPiXSK7vy8fayN?cluster=devnet).
- **Read the code.** The source is in a private repository shared with the hackathon judges.

## Architecture

<p align="center">
  <img src="docs/architecture.png" alt="Architecture: the native Android app, the web messenger shipped inside it, a relay server, and the wallet settling money on Solana devnet." width="100%">
  <br><sub>Messages go phone to phone, end to end; the relay passes only sealed envelopes it can't read.</sub>
</p>

**Stack:** Kotlin and Jetpack Compose; a React and TypeScript messenger inside the app; WebRTC for calls; MapLibre and OpenStreetMap; Python FastAPI on Fly.io; Solana SPL Token, Memo, Mobile Wallet Adapter, Seed Vault.

## Licence

© 2026 Kyrylo Myloserdov. **All rights reserved.** This repository holds words, pictures, the pitch deck and the Android build for evaluation. No licence is granted to use them ([LICENSE](LICENSE)). The code is private.
