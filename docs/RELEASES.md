# Releases plan

Nightpost ships as a signed Android build from [phantom-os.dev/download](https://phantom-os.dev/download). This repository holds words and pictures only, so the release page here points to that build instead of storing it.

## APK to attach

| | |
|---|---|
| Build | 15 (versionName `0.1.0-tier1+bdad8fee`), the build published on the website |
| File | `phantom-0.1.0-b15.apk` (arm64-v8a, about 80 MB) |
| SHA-256 | `38e76c2823dfda3e253f8833b495783665171f27f01b7eeb2bc8d8b76e224ba2` |
| Signing certificate SHA-256 | `d249e0fb73743d219047fc18ece1eaffdf193892f1c859a6b7af46cd98be4357` |
| Network | Solana devnet, no real money |

Source of the hash: the build-15 release log (arm64 file). Before the release is created, re-check it against the checksum shown at phantom-os.dev/download. If the website has moved to build 18 by then, use that build and its checksum instead.

## Steps

1. Create release `v0.1.0-b15` (or the newer build) as a pre-release.
2. Attach the APK and a `SHA256SUMS.txt` with the line above.
3. Notes: three sentences, plain words, devnet stated first.
4. Video link: added later, once the film is public. Until then the release notes say "film coming".
