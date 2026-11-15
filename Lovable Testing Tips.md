


```
Build a mobile-first wardrobe organization app called "Closet" as a responsive web app, designed for a phone-sized screen (390px wide) with a persistent bottom tab bar for navigation. Use a clean, modern look: soft neutral background (warm off-white), one accent colour (deep teal), rounded cards, generous spacing, and a clear sans-serif font. Use sample data throughout so every screen looks populated from the start.

The app has exactly four screens:

1. HOME (Dashboard)
- Greeting header and today's date
- "Today's outfit suggestion" card showing a top, bottom and shoes as small image tiles, with a "Wear this" button and a "Shuffle" button
- Quick stats row: total items, outfits saved, items not worn in 30+ days
- "Recently added" horizontal scroll of 5 item cards

2. WARDROBE (Browse items)
- Search bar at the top
- Horizontally scrollable category chips: All, Tops, Bottoms, Dresses, Outerwear, Shoes, Accessories
- Two-column grid of item cards, each showing a photo placeholder, item name, colour dot and a favourite heart toggle
- Floating "+" button that opens the Add Item screen
- Tapping a card opens a bottom sheet with item details (category, colour, season, times worn, "Mark as worn" button)

3. ADD ITEM (Form)
- Photo upload area with a camera icon (placeholder is fine)
- Fields: item name, category dropdown, colour picker (swatches), season selector (Spring, Summer, Autumn, Winter, All-year), brand (optional), notes
- "Save item" button that adds the item to the Wardrobe grid and shows a confirmation toast
- Basic validation: name and category are required

4. OUTFITS (Saved looks)
- Segmented control at the top: "Saved" and "Planner"
- Saved: list of outfit cards, each showing the combined item thumbnails, outfit name and occasion tag (Work, Casual, Evening, Gym)
- Planner: a simple weekly view (Mon–Sun) where each day shows an assigned outfit or an "Add outfit" button
- "Create outfit" button that lets the user pick items from their wardrobe

Navigation: bottom tab bar with four icons and labels (Home, Wardrobe, Add, Outfits). Highlight the active tab in the accent colour. The Add Item screen is the third tab.

Technical notes: use React with Tailwind and shadcn/ui components, store all data in local state (no backend or login needed yet), and make sure touch targets are at least 44px and text meets accessible contrast.

```

A few tips for testing it on Lovable:

- **Build in stages if the first result is messy.** If it struggles, paste only the Home and Wardrobe sections first, then follow up with “Now add the Add Item screen” and so on. Smaller prompts often give cleaner results.
- **Follow-up prompts work well for polish.** Try “make the cards feel more premium” or “add a dark mode toggle”.
- **Add persistence later.** Once you’re happy with the screens, ask it to connect Supabase so items actually save between sessions.

I can also write a shorter version, or a “level 2” follow-up prompt that adds features like outfit suggestions by weather or a “declutter” view.