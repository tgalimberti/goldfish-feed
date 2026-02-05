# 🐠 Goldfish Feed

Goldfish Feed is a simple, browser-based activity feed for Twitch streamers who find themselves forgetting who they've thanked when they get lost in the 'Faff' of it all.

## How to use
1. Go to the [Live Link Here](https://tgalimberti.github.io/goldfish-feed) and log in with Twitch.
2. (Optional) Open the settings (⚙️) to connect Streamlabs for donation alerts.
3. Keep the tab open on your second monitor while you stream.
4. New events light up brightly - Left-click an event to fade it out (mark "done"), or Right-click to delete it entirely.

## Features
- **All-in-one feed:** Includes all Twitch events and Streamlabs donations.
- **Customisable:** Choose which events appear, whether they should pop up highlighted, and toggle between "Minimal" or "Full Color" high-contrast modes.
- **Client-side only:** No downloads - runs entirely in-browser.
- **Secure:** Your token never leaves your browser.

## To-do
- [ ] Integrate 3rd-party events:
    - [x] Streamlabs
    - [ ] Streamelements
- [ ] Add test events 

## Limitations
- **Live-only:** Because this is a live feed, it only tracks events that happen while the Goldfish Feed tab is open.
- **Connection Health** Goldfish Feed uses a lightweight browser connection. To confirm you're fully synced while live, just check that the viewercount is visible in the top right.
