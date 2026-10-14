# DejaView Privacy Policy

**Last updated: October 14, 2026**

This policy describes the privacy practices of **DejaView for YouTube™: Auto Resume & Video Progress**, developed by Costin Alexandru Sandu (**SaurusLex**). It covers the extension's current version, 1.0.0.

## Overview

DejaView remembers where you stopped watching a YouTube video so you can continue from that position later. It processes and stores video progress locally in your browser profile. The extension does not send your saved videos, playback progress, or settings to the developer or to an external server.

No DejaView account is required. The extension does not include analytics, advertising, tracking services, or cloud synchronization.

## Information the extension accesses and stores

On supported YouTube video pages, DejaView reads the video identifier, title, current playback position, and duration. For videos eligible for saving, it stores:

- The YouTube video identifier, used to recognize the video and create a link back to it.
- The video title.
- The saved playback position and video duration, in seconds.
- The date and time of the most recent save.

It also stores your preferences, including the saving interval, minimum-duration settings, and identifiers of videos individually included in or excluded from automatic saving.

When you open the dashboard, DejaView uses its YouTube host access to read the URL and title of supported YouTube tabs and identify the current video. If the active tab is not a supported video page, it looks for an open supported YouTube video tab. This information is used to display the current video and communicate with its player. DejaView does not store a general browsing history or save non-YouTube tab metadata.

DejaView does not request access to your Google account, passwords, cookies, email, payment information, or browser history database.

## Purpose and storage

The information is used only to save and restore video playback positions, display and manage saved videos, and apply your settings. Saved video titles and identifiers can reveal viewing interests; they remain in the extension's local storage.

Progress and settings are stored using `chrome.storage.local` in your browser profile. DejaView does not use `chrome.storage.sync` to synchronize them between devices. Local storage is managed by your browser and is subject to access to your device and browser profile.

## Sharing and external services

The extension does not upload, sell, or share saved video information or settings with the developer, advertisers, or other third parties. The developer cannot remotely access these local records. DejaView does not use them for advertising or profiling.

Opening a saved-video link takes you to YouTube through ordinary browser navigation. YouTube, Chrome, and the Chrome Web Store operate under their own privacy policies. The Chrome Web Store may provide the developer with aggregate installation, user-count, and rating statistics; those statistics are separate from DejaView's locally stored playback records.

DejaView's use of user information complies with the [Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/user-data), including its Limited Use requirements. Information is used solely for the extension's disclosed video-progress features.

## Permissions

The current extension declares the following permissions:

| Permission | Access and purpose |
| --- | --- |
| `storage` | Store and retrieve video progress and settings locally. |
| `https://www.youtube.com/*` | Run the playback-saving and restoration script on YouTube pages and read matching YouTube tab URLs and titles to identify the current video or another open supported video tab. |

Messages between the dashboard and the playback script stay within the browser; they are not sent to the developer.

## Retention and deletion

Saved records have no fixed expiry. They remain locally until you delete them, the extension removes them near the end of a video, or the extension is uninstalled. During a save attempt, DejaView removes that video's progress if playback is within the final five seconds of its known duration.

You can delete individual records using the trash button in **Saved Videos**. If automatic saving remains enabled for a video that is still open, a later save may recreate its record. Turn off **Auto-save for this video** to stop new automatic saves for that video; this does not delete an existing record.

Disabling the extension stops it running but leaves its local data in place. Uninstalling it removes its local extension storage, including saved progress, preferences, and per-video settings. Clearing ordinary browsing history or cache does not necessarily clear extension storage.

## Contact and support messages

For privacy questions, contact Costin Alexandru Sandu (SaurusLex) at [costinalex12@gmail.com](mailto:costinalex12@gmail.com).

If you choose to contact the developer, your email address, message, and any information you voluntarily provide will be received through the developer's email service and used to respond to your request. Support correspondence is separate from the extension's local storage; sending an email does not grant the developer access to your saved videos.

## Changes to this policy

This policy will be updated if DejaView's privacy practices change. The date at the top identifies the latest revision.
