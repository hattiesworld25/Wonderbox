# WonderBox — Feature Notes
Saved 2026-10-24, at Hattie's request. Everything below lives in this WonderBox folder.

## Why the name works (notes Hattie pasted in)
- "Wonder" captures the magic of fairytales, dinosaurs, and bedtime stories.
- "Box" gives a nostalgic, retro nod to the old-school television set while staying modern enough for a digital app.
- It implies that inside this little digital box, there's a whole universe of curated surprises waiting for kids.

## App
- wonderbox.html — the app itself (a re-skin of the Popcorn build).
- 5 sections, each also a live channel that loops all day: Regular Kids, Fairytales, Storybook, DinoWorld, Nighttime Lullabies.
- 15 demo titles (3 per section). Sample videos are placeholders until Hattie swaps in her own episodes, stories, and songs.
- Ads: demo banner + 5-second demo break before a show (AdMob only in the Android/iOS store build).
- Subscription: WonderBox Premium, $4.99/mo demo — local switch only; real money needs Google Play / App Store billing.

## Features Hattie approved and added 2026-10-24 ("Add all of them")
1. **Parental Gate** — a simple math question must be answered before the Premium / subscription screens open, so toddlers can't tap into them by accident. Restore Purchase is gated too.
2. **Clear reward earn** — the button now says "Earn 2h ad-free" and opens a sheet explaining the deal: watch one short sponsored clip all the way through, then Claim to get 2 hours with no ads. (Demo clip waits 5 seconds.)
3. **Audio-only Sleep Mode for lullabies** — a "🌙 Sleep mode" button in the player dims the screen to near-black while the sound keeps playing; "Tap to wake" brings the picture back.
4. **Sleep Timer** — a "⏱ Timer" button in the player cycles Off → 15 → 30 → 60 minutes; when it runs out, the show stops and the app says goodnight.
5. **Favorites / "My Favorites" quick-pin** — every title has a ☆ Favorite button; favorites get a star and appear in their own "⭐ My Favorites" section at the top. Saved on the device.
6. **Offline mini-downloads (Premium)** — every title has a "⬇ Save offline" button. Premium subscribers can save titles; non-subscribers are sent to the (parent-gated) Premium screen. In this demo the save is marked on the device only — in the store build the file is actually cached for car rides and flights.
