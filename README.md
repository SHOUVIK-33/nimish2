# From Nimeṣa to Mahākalpa

A single, self-contained web page that presents the Vedic measurement of time — from the
twinkling of an eye to the lifetime of the cosmos — and **proves**, with a live counter, that
**486,000 nimeṣa = 1 ahorātra = 24 hours**.

Built on **Manusmṛti 1.64**, with the variations found across the Purāṇas, the Mahābhārata,
the Sūrya Siddhānta, the Nāṭyaśāstra and the Arthaśāstra.

---

## The proof

Manusmṛti 1.64 gives the ladder:

| Unit | Equals |
|------|--------|
| 1 nimeṣa | a twinkling of the eye ≈ 0.1778 s (8/45 s) |
| 18 nimeṣa | 1 kāṣṭhā (≈ 3.2 s) |
| 30 kāṣṭhā | 1 kalā (96 s) |
| 30 kalā | 1 muhūrta (48 min) |
| 30 muhūrta | 1 ahorātra (24 h) |

Multiply the ratios:

```
18 × 30 × 30 × 30 = 486,000 nimeṣa per ahorātra
```

And therefore:

```
1 nimeṣa = 86,400 s ÷ 486,000 = 0.1778 s
486,000 nimeṣa × 0.1778 s = 86,400 s = 24 hours ✓
```

The page's live counter advances one nimeṣa every 0.1778 seconds and completes exactly at
486,000 — that is the demonstration.

---

## Features

- **Live counter** — one nimeṣa per 0.1778 s, target 4,86,000, with an elapsed timer,
  a progress bar, and unit counters for kāṣṭhā / kalā / muhūrta / ahorātra.
- **Milestone messages** — "1 kāṣṭhā complete", "1 kalā complete", "1 muhūrta complete",
  and a final "ahorātra proven" panel.
- **Speed control** — 1× (the real 24-hour proof) up to 3600× for a quick demo.
- **The Ladder of Time** — a visual ascent from the blink of an eye to the dissolution of Brahmā.
- **Scripture & Verses** — the relevant verses, in Devanagari with transliteration and
  translation, from Manusmṛti, Viṣṇu Purāṇa, Bhāgavata Purāṇa, Sūrya Siddhānta,
  Mahābhārata, Nāṭyaśāstra, Arthaśāstra and Skanda Purāṇa.
- **Where the texts differ** — a comparison of the small-unit ratios across sources.
- **The Master Table** — nimeṣa through Mahākalpa, in human years.

No build step, no dependencies, no framework. Pure HTML, CSS and JavaScript in one file.

---

## How to run

Just open the file in any browser:

1. Double-click `nimesha_to_mahakalpa.html`, or
2. Right-click → *Open with* → your browser.

That's it. Nothing to install.

> **Note on timing:** at **1×** the counter finishes in exactly 24 hours — that is the actual
> proof. Use **3600×** to watch the full cycle complete in about 24 seconds.
> Progress is held in memory, so reloading the page restarts from zero.

---

## Hosting on GitHub Pages

1. Create a new **public** repository on GitHub.
2. Upload `nimesha_to_mahakalpa.html` and rename it to **`index.html`** (so it loads at the
   repository's root URL).
3. Go to **Settings → Pages**.
4. Under *Build and deployment*, set **Source: Deploy from a branch**,
   **Branch: main**, **Folder: / (root)** → **Save**.
5. In a minute or two the site is live at:

   ```
   https://<your-username>.github.io/<repo-name>/
   ```

If you keep the original filename instead of `index.html`, the page will be served at
`https://<your-username>.github.io/<repo-name>/nimesha_to_mahakalpa.html`.

---

## Files

```
nimesha_to_mahakalpa.html   The entire site (self-contained; HTML + CSS + JS)
README.md                   This file
```

---

## Sources

- **Manusmṛti** 1.64–1.80 (Ganganath Jha translation)
- **Viṣṇu Purāṇa** 1.3 (H. H. Wilson translation)
- **Śrīmad Bhāgavatam** 3.11.6–3.11.8
- **Sūrya Siddhānta** 1.10–1.12 (Ebenezer Burgess translation)
- **Mahābhārata**, Śānti Parva 12.231
- **Nāṭyaśāstra** / Kohala, *Tālalakṣaṇa*
- **Arthaśāstra** 2.20
- **Skanda Purāṇa**, Prabhāsa Khaṇḍa 19

---

## A note on accuracy

The small sub-second units vary by tradition — depending on the source, a nimeṣa works out to
roughly 0.09 s, 0.18 s or 0.53 s. The large cycles (Mahāyuga → Kalpa → Mahākalpa) are consistent
across the Purāṇas.

For the total number of nimeṣa in one **Mahākalpa**, using the Manusmṛti chain
(486,000 nimeṣa/day × 360 days/year × 311,040,000,000,000 years):

```
≈ 5.442 × 10²² nimeṣa   (about 54.4 sextillion twinklings of the eye)
```

A commonly circulated figure of "5.6369 × 10¹⁹ nimeṣa (56.3 quintillion)" does not match this
chain — it corresponds to only about 322 billion years, roughly a thousand times too small.

---

## License

Free to use, study and share. The underlying texts are in the public domain.
