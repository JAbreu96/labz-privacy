---
title: LABZ Privacy Policy
---


**Last updated: 30 July 2026**

LABZ (Cypher Companion) is a practice app for street dancers. This policy explains what the app does with your data. The short version: **there is no account, no advertising, and no tracking across apps or websites.** Almost everything stays on your phone.

---

## What stays on your device

These never leave your phone unless you export or share them yourself:

- **Practice history** — labs, active time, streaks, weekly goals, milestones
- **Goals and daily/weekly focus** you write
- **Journal notes and mood tags** from post-session recaps
- **Directive sets** you create
- **Imported songs**, their tempo analysis, waveforms and cue points
- **Video recordings** — saved to your own Photos library. LABZ never uploads them.

You can remove all of it by deleting the app.

---

## What is sent off your device

### 1. Diagnostics and crash reports

LABZ uses **[Sentry](https://sentry.io/privacy/)** to find out when the app breaks. Sent automatically when an error occurs:

- Error type and where in the app it happened
- Device model, iOS version, app version and build
- Free disk space, low-power and thermal state
- Which permissions you've granted (camera, microphone, media, notifications)
- A short trail of recent app events (screens opened, features used)

**Deliberately excluded:** song titles, goal text, journal notes, your name, email, IP-based identifiers, and any credentials. Where a song needs to be referenced in a log, it's reduced to a one-way hash so the same track can be recognised without recording what it is.

### 2. Feedback you choose to send

When you tap the feedback button and press **Send**, LABZ transmits what you typed, the screen you were on, the device summary above, and — if you leave the toggle on — the recent activity log. The sheet shows you this before anything is sent, and it only happens when you press Send.

### 3. Tempo lookups

When LABZ looks up a song's tempo, it sends the **track title and artist** to:

- **[Deezer](https://www.deezer.com/legal/personal-datas)** (`api.deezer.com`)
- **[GetSongBPM](https://getsongbpm.com/)** (`api.getsong.co`)

No identifier of you is attached. Results are cached on your device so the same song isn't looked up twice.

### 4. Spotify (only if you connect it)

If you connect Spotify, LABZ uses Spotify's own login and reads **only your currently playing track** to detect its tempo. LABZ cannot see your playlists, library, or listening history, and cannot control playback. Your Spotify session token is stored in the iOS Keychain on your device. Disconnect at any time. See [Spotify's privacy policy](https://www.spotify.com/legal/privacy-policy/).

### 5. Apple Music

Reading your currently playing track from Apple Music happens **entirely on your device**. Nothing is transmitted.

---

## Permissions and why they're asked for

| Permission | Used for | Optional? |
|---|---|---|
| **Microphone** | Detecting the tempo of music playing in the room | Yes — you can tap the tempo instead |
| **Camera** | Showing yourself on screen and recording practice | Yes |
| **Photos** | Saving your recordings to your library | Only if you record |
| **Media & Apple Music** | Reading the currently playing track's tempo | Yes |
| **Notifications** | Practice reminders you schedule | Yes |

Every one is optional. Declining any of them leaves the rest of the app working — the related feature simply stays off. Audio from the microphone is analysed in real time for tempo only; it is never recorded, stored, or transmitted.

---

## Children

LABZ is not directed at children under 13 and does not knowingly collect their information.

## Data retention

Diagnostic and crash data is retained by Sentry for **30 days** and then deleted. On-device data stays until you delete it or remove the app.

## Your choices

- Turn off the activity log in the feedback sheet before sending
- Revoke any permission in **iOS Settings → LABZ**
- Disconnect Spotify in the app
- Delete the app to remove all local data
- To request deletion of a diagnostic report or feedback you sent, email the address below with the approximate date and device model

## Changes

Material changes will be reflected here with a new "last updated" date.

## Contact

Questions, or a request to delete something you sent: **ajoelcrist@gmail.com**
