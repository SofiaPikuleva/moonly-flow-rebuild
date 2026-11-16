# Growth Audit — Moonly

**Live:** https://sofiapikuleva.github.io/moonly-flow-rebuild/
(prototype view: https://sofiapikuleva.github.io/moonly-flow-rebuild/?view=proto)

Moonly runs three big promises on Meta: a Soulmate Reading, a personal astrologer and daily tarot. All three open the same hello.moonly.app page, and the web paywall reads “Your Daily Guide to Self-Discovery” to everyone. This audit has two views: an overview with five ranked ideas, and a clickable prototype with one first launch per ad, built in Moonly’s own design at Moonly’s App Store prices.

## The five ideas

| # | Idea | Where | Expected effect |
|:-:|:--|:--|:--|
| 1 | Name their goal in the Plus headline | Plus | CR +15–20% |
| 2 | Open each ad’s install on that ad’s promise | Goal | CR +5–15% |
| 3 | Make the loader read their answers back | Loader | CR +10–15% |
| 4 | Put your proof next to the price | Plus | CR +10–15% |
| 5 | Pre-select yearly and show what it saves | Plus | ARPU +10–15% |

Impact ranges are Adapty’s expected effect from teardowns and A/B tests across subscription apps, not measured lift for Moonly.

## What it is built from

- Your web quiz at moonly.app/start, taken on 16 November 2026, with artwork from your own CDN. Your iOS onboarding and in-app paywall were not recorded; where they differ, the web quiz is what is shown.
- The US App Store listing on 16 November 2026: ★ 4.6 from 31K ratings, and the In-App Purchases list ($59.99 Annual Pro Subscription, $9.99 Monthly Subscription).
- 10M users and Editors’ Choice from your App Store screenshots and moonly.app.
- Your ads from the Meta Ad Library (advertiser Moonly, @moonlyapp), active on 16 November 2026.
- “Save 50%”: $59.99 against twelve months at $9.99 ($119.88). “$5.00 a month” is $59.99 ÷ 12.

## Run it locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

Prepared by Adapty · [Book a demo](https://calendly.com/d/cty4-37z-zqj)
