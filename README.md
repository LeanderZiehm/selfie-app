# selfie-app
take pictures over time to you change

The goal is simple:
take **one picture of yourself every day**, from **the same angle**, with **the same framing and lighting**, so over time you can turn those images into a video and actually see changes in your face — pimples, skin health, fat loss/gain, etc.

The hard part isn’t taking the photo.
The hard part is matching **yesterday’s position**.

That’s what this app solves.

---

## The Problem

If you’ve ever tried to do daily face photos, you know this:

* You never stand in the exact same spot
* The angle is always slightly off
* Your head is tilted differently
* The distance from the camera changes
* Lighting looks similar, but not *the same*

Even small differences make the final timelapse look jumpy and useless.

You end up guessing where your face was last time.

---

## The Solution

This app overlays **your last photo** directly on top of the live camera feed.

* The previous image is shown at **30% opacity**
* The live camera is underneath it
* You line your face up until it matches
* Then you take the photo

No guessing.
No memory.
You literally line yourself up with yesterday’s face.

It feels like using a normal camera app — just with a transparent ghost of your last frame.

---

## How It Works

1. Open the app
2. The front camera opens full screen
3. Yesterday’s photo is loaded automatically
4. You adjust your position to match the overlay
5. Tap the shutter
6. Today’s photo is saved and becomes tomorrow’s overlay

That’s it.

There’s no account, no cloud, no syncing, no sharing.

---

## Why a PWA

This is built as a **Progressive Web App** so it:

* Installs on Android like a normal app
* Works offline
* Opens instantly
* Has no app store friction
* Doesn’t need permissions beyond the camera

It’s meant to feel like a native camera app, not a website.

---

## Storage

* Photos are stored **locally on the device**
* Uses IndexedDB (not localStorage)
* Nothing is uploaded anywhere
* You own your data

If you delete the app or clear site data, the photos are gone.

---

## Intended Use

This app is intentionally:

* Single-user
* Minimal
* Focused on consistency, not features

It’s not a social app.
It’s not a skincare app.
It’s a personal tracking tool.

Open → align → shoot → done.

---

## Future Ideas (Maybe)

Not required, but possible later:

* Opacity slider for the overlay
* Toggle overlay on/off
* Face alignment guides (eyes, nose, outline)
* One photo per day enforcement
* Export all images for video creation

None of these are needed for the core idea to work.

---

## Summary

This app exists because **guessing your previous angle doesn’t work**.

Seeing it does.

That’s the whole idea.

---

If you want, next I can:

* Rewrite this even more raw / minimal
* Add a “why I built this” section in first person
* Adjust tone to be more hacker-style or more product-style
