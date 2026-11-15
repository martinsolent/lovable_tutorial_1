---
layout: default
title: Prototype a mobile app with Lovable
nav_order: 1
# parent: Your parent page title   # uncomment and edit if this page sits under another page
last_modified_date: 2026-11-15
---

# Prototype a mobile app with Lovable
{: .no_toc }

Build a simple app with Lovable, publish it, and test it on your phone as if it were a real app. No coding, no GitHub, and no app store.
{: .fs-6 .fw-300 }

<details open markdown="block">
  <summary>Contents</summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

## What you will need

- A free Lovable account (lovable.dev)
- A phone with Chrome (Android) or Safari (iPhone)
- An idea for a simple app, ideally three to five screens

{: .note }
Lovable builds **web apps**, not native apps. Your prototype runs in a browser, but a home-screen shortcut makes it feel like an app for testing.

---

## Part 1: Build the app

### Step 1: Sign up

Create a free account at [lovable.dev](https://lovable.dev). The free plan needs no credit card.

The free plan gives you **5 build credits a day, up to 30 a month**. Daily credits expire at the end of each day (00:00 UTC) and do not roll over, so use them as you go.

<!-- SCREENSHOT: Lovable sign-up or home screen -->

### Step 2: Write a clear prompt

Describe the screens, navigation and look, and say that it is for a phone-sized screen. Specific prompts give better first results and use fewer credits.

Example prompt:

```text
Build a mobile-first app called "Closet" for a phone-sized screen (390px wide)
with a bottom tab bar. Use a warm off-white background, one teal accent
colour, rounded cards and a clean sans-serif font. Use sample data so every
screen looks populated.

Four screens:
1. Home: greeting, today's outfit suggestion card, quick stats, recently added items
2. Wardrobe: search bar, category chips, two-column grid of item cards
3. Add Item: photo area, name, category, colour, season, notes, Save button
4. Outfits: Saved and Planner tabs, outfit cards, weekly planner
```

<!-- SCREENSHOT: Prompt typed into the Lovable chat box -->

### Step 3: Check the preview

The **Preview** tab shows your app live. Use the **device toggle** above the preview to switch between Desktop, Tablet and Mobile views. Choose **Mobile**.

<!-- SCREENSHOT: Preview tab with the device toggle set to Mobile -->

### Step 4: Refine with small requests

Make one change per message, for example:

- "Make the item cards rounder."
- "Add a favourite heart to each item."
- "Change the accent colour to dark green."

Small, focused requests in Build mode cost less. Larger or multi-step changes cost more.

{: .tip }
If a change goes wrong, open the **History** toggle next to the project name, find an earlier version and restore it. You can also bookmark versions you like.

### Step 5: Check your credits

Open **Plans & credit usage** (click the credit bar, or go to Settings). It shows:

- **Daily build credits**: your 5 free credits for today
- **Credits left**: any separate balance you have
- **Usage**: how many credits each project has used

<!-- SCREENSHOT: Plans & credit usage page -->

---

## Part 2: Publish

### Step 6: Click Publish

1. Click **Publish** (top right).
2. Choose a **Website URL**. By default your app is published to `your-name.lovable.app`.
3. Confirm.

Publishing from the **Publish** button does not use credits and still works if your credit balance is zero.

<!-- SCREENSHOT: Publish dialog -->

### Step 7: Understand publish versus edit

The live site is a **snapshot** from your last publish. Edits in the editor do not appear on the live site until you publish again.

To update the live site later, click **Publish**, then **Publish changes**. A dot on the Publish button tells you that you have unpublished changes.

{: .note }
Publishing from the chat costs credits. Use the Publish button instead.

### Step 8: You do not need to save

Lovable stores your project in your account and has no save button. Every change creates a version automatically.

You can close the browser and come back later:

1. Go to lovable.dev and sign in.
2. Open your project from the dashboard.
3. Carry on in the chat and preview.

If the preview says **Still building?**, click **Keep building**. Lovable pauses the preview when you are away, and nothing is lost.

---

## Part 3: Put the app on your phone

### Step 9: Open the published URL on your phone

Type the `lovable.app` address into your phone's browser, or send yourself the link.

{: .warning }
For testing, use the **published URL**, not the QR code from the preview. The preview link is for development and may not behave properly as a shortcut.

### Step 10: Add a shortcut to the home screen

**Android (Chrome)**

1. Open the published URL in **Chrome**.
2. Tap the **three-dot menu (⋮)**.
3. Tap **Add to Home screen** (or **Install app**, if it appears).
4. Choose **Create shortcut** (or **Install**) and confirm the name.

**iPhone (Safari)**

1. Open the published URL in **Safari**. Chrome on iOS cannot add home-screen shortcuts.
2. Tap the **Share** button (square with an upward arrow).
3. Scroll down and tap **Add to Home Screen**.
4. Tap **Add**.

<!-- SCREENSHOT: Chrome menu with Add to Home screen -->
<!-- SCREENSHOT: Shortcut confirmation dialog -->

### Step 11: Launch it like an app

Tap the new icon on your home screen. The app opens without the usual browser address bar, so it looks and feels like an app.

<!-- SCREENSHOT: App open full screen on the phone -->

---

## Part 4: Update and test with users

### Step 12: Update after changes

1. Edit the app in Lovable.
2. Click **Publish**, then **Publish changes**.
3. Close the shortcut fully and reopen it. If you still see the old version, reload the page.

You should not need to add the shortcut again.

### Step 13: Share with testers

Give testers the published URL and the shortcut steps from Part 3. By default a published app is visible to anyone with the link. You can change who can view it from the visibility option in the Publish dialog.

---

## Troubleshooting

| Problem | What to try |
|:--------|:------------|
| Daily credits are at 0 | Wait for the reset at 00:00 UTC. Your project and published site are not affected. |
| Live site shows the old version | Click **Publish changes**, then close and reopen the shortcut. |
| No "Add to Home screen" option on iPhone | Open the link in **Safari**, not Chrome. |
| Shortcut opens with a browser bar | Remove the shortcut and add it again from the published URL. |
| Preview says "Still building?" | Click **Keep building**. |
| A change broke the app | Open **History**, then restore an earlier version. |

---

## Good to know

- **Free plan limits:** no custom domain, and the code editor is read-only.
- **It is a website, not a native app:** there is no app store listing and no push notifications.
- **Icon:** without extra setup, the home-screen icon may be generic. That is fine for prototypes.

## Sources

- [Lovable pricing](https://lovable.dev/pricing)
- [Plans and credits](https://docs.lovable.dev/introduction/plans-and-credits)
- [Preview your app](https://docs.lovable.dev/features/projects/preview)
- [Publish your Lovable project](https://docs.lovable.dev/features/publish)
- [Version history](https://docs.lovable.dev/features/projects/history)
