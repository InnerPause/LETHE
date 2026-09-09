[README.md](https://github.com/user-attachments/files/31984766/README.md)
# LETHE
### *a website that is forgetting itself*

> Bookmark this page. Come back tomorrow.
> It will remember you — but it will no longer remember itself in quite the same way.

---

## Gallery Label

You are standing in the Gallery of the Present, Exhibit No. 09.

At birth, this page held **1,100 words**. We counted them the way a nurse counts fingers.

Each word was assigned, by lottery, a day on which it will be unmade. Not censored, not deleted in anger — simply loosened, the way frost loosens a stone from a wall. Each midnight, the river takes a few more.

- **Day 0** — nearly whole. A few small gaps, like missing teeth. You will lean in.
- **Day 30** — the adjectives begin to go. The sentences limp beautifully.
- **Day 90** — half the building is air. What remains hits harder.
- **Day 177** — an empty room with good lighting. You are the exhibit now.

There is no backup. There is no vault copy. When the last noun goes, the grammar will keep bowing to guests for a while out of politeness, and then it too will sit down.

In roughly six months this gallery will be empty. Come back and stand in it. Emptiness, arranged with care, is a kind of sentence.

---

## How to Stand In It

**To visit:**

Open the gallery. Read slowly enough that the words leave a temperature on you, then let them go.

**To deploy your own instance to GitHub Pages:**

1. Push this repository to GitHub.
2. Go to *Settings → Pages*.
3. Under *Build and deployment*, choose *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. Wait a minute. Your forgetting will begin at the address GitHub gives you.

There is no build step. There are no dependencies. The piece is a single `index.html` — one room, one river, one caretaker. It runs from `file://` too, though like most haunted things, it prefers to be visited properly.

**To time-travel** (for the impatient, the curious, the grieving):

- `?day=0` — birth. Everything remembered.
- `?day=1` — tomorrow. Notice what is already gone.
- `?day=60` — late autumn of the mind.
- `?day=177` — the end. A lit room and your own breathing.

Share these links like postcards from the future: *"see what it looks like in 60 days."*

---

## Rituals for the Visitor

Do not try to memorize what you read here. That would be like carrying river water in a sieve to save the river.

Instead:

1. **Cup a vanished word.** Rest your cursor on any gap where a word used to live, the way you would cup a firefly. The word will briefly remember itself for you — one and a quarter seconds. It will not stay. Nothing you hold here stays. Press **R** at any time and the gallery will tell you how many memories you have held against the river.

2. **Listen.** Press *hum of the gallery* in the lower corner. The building drones softly at 55 Hz. As forgetting advances, the hum stutters. Past the halfway point, it barely holds together. This is not a bug. This is the sound of a burden being set down one syllable at a time.

3. **Leave an offering.** At the foot of the gallery is a small altar. Leave one sentence. It will live in *your* copy of the gallery for seven days — then it too will be swept away. Everything you love here is on loan.

4. **Read the caretaker's note.** At the very bottom, in small type: bulb temperature, humidity, moths asleep on the frame, letters swept that day. It is different every visit. Almost nobody notices it changing. You will be among the few who check.

5. **Press L.** On any quiet evening, press **L** and one of the taken will be spoken aloud — a single word, returned briefly from the water.

---

## The Mechanics of Forgetting (Caretaker's Appendix)

For those who lift the frames to look at the wiring:

- **The lottery is deterministic.** Each word index `i` draws `hash(i) → doomDay` uniformly across 0–177. Every visitor on the same calendar day sees the same absence. We forget together, or not at all.
- **The clock is the wall clock.** Day count is `floor((now − GENESIS) / 86400000)`, where `GENESIS` is the dawn the piece was born. No server. No database. Entropy, synchronized by sunrise.
- **Fading is a threshold.** Words within two days of their doom shimmer (`fading`); words past it become gaps (`gone`), preserved in layout, revealed only while held.
- **Memory is local.** Visit counts, first-visit date, and offerings live in `localStorage` — the page forgets, but it keeps your ticket stubs.
- **Dust is unrepeatable.** The motes, the bold mote, the bulb Kelvin, the breathing tempo of the title — re-seeded every load. No two visits share the same air.
- **Motion respects grief.** `prefers-reduced-motion` stills the dust, the grain, and the flicker. Forgetting continues; it simply does so quietly.

---

## Colophon

*LETHE* is named for the river in the Greek underworld from which the dead drank to unburden themselves before returning to the world. No memories, no ghosts. To begin again, they had to agree to disappear to themselves first.

We found the idea so beautiful we built our machines to do the opposite: to drink nothing, to keep everything, to never let a single photograph blur.

This small building swims upstream.

*Text, design, and decay — original to this exhibit.*
*Set in Cormorant Garamond with fallback to Palatino and Georgia, for when the network, too, begins to forget.*
*Dust rendered on canvas. Grain rendered in SVG. Hum rendered at 55 Hz, while it lasts.*

Tomorrow there will be fewer words and the same amount of meaning, the way a winter tree has fewer leaves and the same amount of tree.

Until then: you were here. This was now. It was enough, and it is already, mercifully, beginning to go.

*— The Caretaker*
