# Bravissimo 🇮🇹

A single-page game for learning Italian, built to be opened and used with no setup.

**Play it:** https://jaylaantaylor-boop.github.io/bravissimo/

## What's in it

- **Seven regions** of lessons — Roma, Firenze, Napoli, Venezia, Milano, Sicilia, Sardegna — covering about 1,300 words and 420 sentences, from greetings through the subjunctive.
- **Real recordings.** Every word, sentence, story and dialect phrase is voiced by a studio voice rather than a robotic browser one. 2,175 clips in total.
- **Eight dialects**, including **Noiese**, the dialect of Noepoli in the Val Sarmento, Basilicata — an archaic corner of the Italian language where "tomorrow" is still *crai*, straight from the Latin *cras*.
- **A family notebook** for recording the words your own relatives use, in their own voice. It stays in your browser and is never uploaded.
- **Shadowing studio**, graded **stories** with tap-to-translate, a full **verb conjugator** covering nine tenses, grammar drills, and spaced repetition that brings weak words back before you forget them.

## How it's built

Plain HTML, CSS and JavaScript in one file. No framework, no build step, no server. Progress is saved in your browser's local storage, with a copy-and-paste backup code for moving between devices.

| File | What it is |
| --- | --- |
| `index.html` | The whole app |
| `audio-0.js` … `audio-3.js` | The recordings, loaded in the background after the page appears |

## A note on the Noepoli dialect

Very little of it has ever been written down. Entries are tagged by how well attested they are: 🏠 documented in Noepoli itself, 🏔️ from the same valley, 📜 a Lucanian proverb. The real authority is always the family at the table.
