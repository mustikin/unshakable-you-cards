# Unshakable You Cards

A lightweight, no-backend quote card generator for social media — built on the **5-Step Identity Reset Framework** from *Unshakable You*.

**No API keys. No login. No internet required after first load.**

---

## What it does

Generate shareable quote images (PNG) instantly:
- 37 pre-written quotes across 5 pillars (See It, Name It, Shape It, Live It, Protect It)
- 3 export formats: Square (1:1), Portrait (4:5), Story (9:16)
- Auto-generated captions with hashtags — copy & paste to IG, TikTok, Threads, X
- No-repeat rotation — cycles through all quotes before repeating
- Built-in quote counter so you know what you've seen

---

## Quick start

1. **Online:** Open in your browser → [GitHub Pages URL will go here once enabled]
2. **Offline:** Download repo, open `index.html` locally
3. Pick a pillar (or All Pillars)
4. Click **Generate**
5. Download PNG + copy caption
6. Post

---

## Files

```
unshakable-you-cards/
├── index.html      ← the app (all UI + logic here)
├── quotes.json     ← all 37 quotes + captions
└── README.md       ← this file
```

Both `index.html` and `quotes.json` must be in the same folder.

---

## Customising quotes

Open `quotes.json` and add or edit entries:

```json
{
  "pillar": "See It",
  "quote": "Your quote text here.",
  "caption": "Caption text with context and call-to-action. #Hashtag1 #Hashtag2 #UnshakableYou"
}
```

**Pillar must be exactly one of:**
- `See It`
- `Name It`
- `Shape It`
- `Live It`
- `Protect It`

Save, commit, and your new quotes load instantly.

---

## Framework at a glance

| Pillar | Focus |
|--------|-------|
| **See It** | Honest self-awareness. Stop denying the truth. |
| **Name It** | Call out the pattern. Unnamed things control you. |
| **Shape It** | Cast votes for Next Me. Small actions, stacked. |
| **Live It** | Never Zero. Consistency through the hard days. |
| **Protect It** | Guard your energy. Know your Lifters. Use boundaries. |

**Core vocabulary:**
- **Old Me / Next Me** — Who you were / who you're becoming
- **Cast a Vote** — Every small choice moves you forward
- **Never Zero** — At least one small win every day
- **Slip vs Spiral** — One bad moment vs. letting it spiral
- **Lifters** — People who energise you
- **The Departure Matrix** — Does this align with Next Me?
- **The 3-Step Reset** — Quick recovery after a slip

---

## Deploying to GitHub Pages

1. Go to your repo → **Settings → Pages**
2. Source: `main` branch, `/ (root)`
3. Save
4. Your site goes live at `https://yourusername.github.io/unshakable-you-cards`

---

## About Unshakable You

*A personal development book for everyday people in Southeast Asia.*

**Author:** A.B. Mustikin  
**Website:** [mustik.in](https://mustik.in/unshakable)  
**Book:** Amazon (ASIN: B0G3PXRS9Y) | Singapore signed copies at mustik.in

---

*Fellow traveller. A few steps ahead. Never a guru.*
