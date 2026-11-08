# APOST for macOS

APOST helps one user manage a local video library and schedule videos for one TikTok account using TikTok's official APIs. TikTok authorization, permissions, and publishing remain subject to TikTok's terms and policies.

## Download and install

Download the latest Apple Silicon installer from [GitHub Releases](https://github.com/maksimstahiv03-del/apost-macos/releases/latest). Open the DMG and drag **APOST** to **Applications**.

The first build is unsigned and not notarized by Apple. macOS may block its first launch. Do not bypass that warning unless you trust the publisher. A Developer ID certificate and Apple notarization are needed for a normal verified install; they are not configured yet.

## Updates

In APOST, open **Settings → App updates → Check for updates**. The app checks the public GitHub Releases API and opens the release page when a newer version exists. Download the new DMG and replace APOST in Applications. Your local data remains in Application Support.

## TikTok credentials

The installer does not contain TikTok credentials. APOST requires the Client Key and Client Secret for a TikTok Developer app that you control. See [TikTok setup instructions](https://github.com/maksimstahiv03-del/apost-macos/blob/main/TIKTOK_SETUP.md).

APOST is not affiliated with or endorsed by TikTok.
