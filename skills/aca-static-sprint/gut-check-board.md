# The gut check board

The human instinct gut check belongs to the strategist. The board makes it fast. Build one HTML page (or an artifact, if the tool supports it).

## Layout
- A grid of cards, 4 across on desktop, 1 across on mobile.
- Each card shows: the generated ad, a toggle to show the **reference** next to it, the matrix row, the hypothesis in one line, the ad type, the point of view, the headline and its source ID, and the QA tag (pass / fix / fail) with its reason.
- On each card: **Keep** and **Cut** buttons, a notes box for this ad, and an **"always"** checkbox. Ticked means "apply this note to every future run".
- At the top: filters (QA tag, persona, ad type, iteration or new) and a counter of kept ads.
- A **Copy results** button that copies a plain-text summary to paste back into the chat: kept IDs, cut IDs, and every note marked "this ad" or "always".

## After the gut check
When the strategist pastes the results:
1. Confirm the keep and cut lists.
2. Regenerate any "this ad" fixes they asked for, and run QA on them again.
3. Write every "always" note to `corrections-log.md` with today's date. Say which ones you wrote.
4. Move to variations.

Fails stay visible on the board, marked. The strategist decides what to do with them.
