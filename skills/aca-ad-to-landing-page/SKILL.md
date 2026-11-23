---
name: aca-ad-to-landing-page
description: Turns a winning, persona-led ad into a matching landing page so the page after the click keeps the same promise, persona, proof and offer (congruency). Writes the page outline and copy from the Creative OS, stops for approval, then builds a single HTML page or a build prompt for a site builder. Use when someone says "make a landing page from this ad", "persona landing page", "the page doesn't match the ad", or runs /aca-ad-to-landing-page.
---

# After the click: a page that keeps the promise (Course 804, lesson 6.2)

The ad makes a promise to one persona. The landing page has to keep it. That is congruency. In the creative levers by symptom, a low conversion rate points here first: check congruency with the landing page before you blame the ad.

## Inputs
- The winning ad (file or link) and its row in `06-pipeline/creative-pipeline.md`: why we call it a winner, under the rules in `02-language/how-we-read-the-ad-account.md`.
- From the Creative OS: `01-brand/` (offers, pricing, voice, do's and don'ts), `03-research/audience/customer-voice.md`, `04-concepts/personas.md`.
- The current product page URL, if there is one.

If the ad isn't a winner under the team's rules (retargeting only, or small spend), say so and ask whether to go on.

## Step 1: Read the ad
Write down the persona, angle, awareness level, the promise in the ad's own words, the proof used and the offer. That is the page brief.

## Step 2: Congruency check on the current page
If a page exists, compare it with the ad:

| Element | In the ad | On the page | Match? |
|---|---|---|---|
| Promise (headline) | | | |
| Persona and their words | | | |
| Proof | | | |
| Offer and price | | | |
| Visual world | | | |
| CTA | | | |

Show the gaps. Sometimes a few fixes to the current page are enough. Say so if that's the case.

## Step 3: Page outline (match the ad, then go deeper)
1. **Hero:** a headline that echoes the ad's promise almost word for word, a subhead for the persona, a product image in the same visual world, one CTA.
2. **The problem, in their words:** two or three verbatim customer lines for this persona, with source IDs.
3. **How it works, or why it's different:** three points at most.
4. **Proof:** reviews from this persona (with source IDs) and numbers the brand can stand behind.
5. **Objections as FAQ:** the top objections from customer voice, answered plainly.
6. **Offer:** the same offer as the ad. If the ad had no offer, don't add a discount.
7. **Final CTA.**

**Stop. Show the outline and copy, and wait for approval before building.**

## Step 4: Build
Choose with the user:
- **Single HTML page:** self-contained and mobile-first, with brand colors and fonts from `01-brand/`. Save to `05-production/landing-pages/<persona>-<angle>.html`.
- **Site builder:** write a complete build prompt (sections, copy, colors, images). Send it through the builder's connector only if the user asks.

## Checks before hand-off
- The hero promise matches the ad. The offer matches the ad.
- On a phone, the headline and CTA are visible without scrolling.
- Every review and number is real and sourced. Claims follow the do's and don'ts in the mission control file.
- No giant images slowing the page.
- Hemingway grade 5 or lower.

## Hand-off
Note the page in the concept's row in `06-pipeline/creative-pipeline.md`, with the hypothesis: what we expect the matching page to change.

**Agents prepare. People approve.** Never publish, change a live site or switch an ad's destination URL. A person does that.

## Corrections log
- (empty)
