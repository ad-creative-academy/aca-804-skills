# Swipe file: references for the static sprint

The concept matrix comes first. The swipe file comes after: once a row has its ad type, this folder supplies a reference for the **structure**. Research to inspire, not to copy. Curate it by hand. That is the strategist's eye at work.

## How it's organized
By three things, so the sprint can match a reference to a row:
- **Ad type** (the static ad types in `02-language/ad-types.md`): bold claim, key benefits, us vs them, before and after, polished review, native review, split screen, grid swap, price breakdown, text message, notes app, search, post-its, promo, problem vs solution, news/media, lifestyle, infographic.
- **Awareness level:** unaware, problem aware, solution aware, product aware, most aware.
- **Point of view:** brand voice, customer voice, expert voice.

## What to save
Save a reference when you can name its building blocks: what the headline does, what the visual does, where the proof sits, where the offer sits. If you can't reverse engineer it, it won't help the sprint.

Aim for at least one reference per ad type you use, across more than one point of view. Five versions of one layout count as one reference.

A long-running ad is worth studying. It is a signal, never proof. "Just because an ad is running doesn't mean it's working."

## Where references come from
1. **Your own winners first.** Your best past statics are the most on-brand references you have.
2. **Your competitor and trend research.** The monthly habit from the research module: Meta Ad Library, TikTok Creative Center, Google Ads Transparency Center, Foreplay. Tag these as structure references.
3. **Outside your category.** A brand that talks to the same persona in another category often has the freshest structure.

## Structure
```
swipe-file/
  images/S01.png, S02.png, ...
  references.json
```

One entry per reference. `references.json` ships with three example entries. Replace them with your own.

```json
{
  "id": "S01",
  "file": "images/S01.png",
  "ad_type": "key benefits",
  "awareness_levels": ["problem aware", "solution aware"],
  "point_of_view": "brand",
  "best_for": "showing three benefits at once",
  "copy_slots": {"headline": "max 7 words", "callouts": "3 x max 4 words"},
  "notes": "product centered. Works with any bottle or stick shape"
}
```

To add a reference, drop the image in `images/` and ask the agent to add its entry. To remove one, delete both and note why in `../corrections-log.md`.
