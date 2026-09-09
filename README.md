# LETHE
### *a website that is forgetting itself*

> Bookmark this page. Come back tomorrow.
> It will keep your visits, but it will not keep itself.

---

## Gallery Label

You are standing in the Gallery of the Present, Exhibit No. 09.

At birth, this page held **567 words**. That number counts everything with a scheduled death: the collection and the signage alike.

The forgetting happens in two movements. First the collection falls, about five words a day, each midnight taking a few more, the words due that day going hour by hour, so even two visits on the same day will not match exactly. The signage waits its turn. Only when the last essay word is gone does the room begin taking its own walls, in reading order, a few words a day. The last word of all is Offer. After it goes, there is only the void.

- **Day 0**, nearly whole. A few small gaps, like missing teeth. You will lean in.
- **Day 30**, the pretty adjectives are going. The sentences limp beautifully.
- **Day 90**, half the building is air. What remains hits harder.
- **Day 177, March 5 2027**, the collection is gone. An empty room with good lighting. You are the exhibit now.
- **Days 178 to 206**, the walls come down. The title, the labels, the instructions. Read them while you can.
- **Day 207, April 4 2027**, one word left. It goes today. Afterwards, the void.

There is no backup. There is no vault copy. When the last noun goes, the grammar will keep bowing at the door out of habit, and then it will sit down too.

Come back and stand in it. I think emptiness, arranged with care, can still hold you.

---

## How to Stand In It

**To visit:**

Open the gallery. Read slow. Let the sentences leave a temperature on you and go.

**To deploy your own instance to GitHub Pages:**

1. Push this repository to GitHub.
2. Go to *Settings*, then *Pages*.
3. Under *Build and deployment*, choose *Deploy from a branch*, branch `main`, folder `/ (root)`.
4. Wait a minute. Your forgetting will begin at the address GitHub gives you.

There is no build step. There are no dependencies. The piece is a single `index.html` plus a small `favicon.svg`. It runs from `file://` too, though like most haunted things, it prefers to be visited properly.

There is only one state to visit: the page as it really is, on this day. There are no other versions to flip through. What is gone is gone.

---

## Rituals for the Visitor

Please do not try to memorize what you read here. That would be like carrying river water home in a sieve to save the river.

Instead:

1. **Cup a fresh gap.** Rest your cursor on a gap where a word used to live. If it is still warm, the word will come back for about a second. Words stay warm for about a week. After that they go cold, and no hovering will bring them back. That part is not interactive. That part is just loss. Press **R** at any time and the gallery will tell you how many memories you have held against the river.

2. **Listen.** Press *hum of the gallery* in the lower corner. The building drones softly at 55 Hz. As forgetting advances, the hum stutters. Past the halfway point, it barely holds together. That sound is a burden being set down one syllable at a time.

3. **Leave an offering.** At the foot of the gallery is a small altar. Leave one sentence. It will live in *your* copy of the gallery for seven days, with its remaining time written beneath it, paling as it dissolves. Then the river takes it too. No one else can see it. It is only for you.

4. **Read the caretaker's note.** At the very bottom, in small type: bulb temperature, humidity, moths on the frame, letters swept that day. It is different every visit. Almost nobody notices it changing. You will be among the few who check.

5. **Press L.** On any quiet evening, press **L** and one of the recently taken will be spoken aloud. Only the warm ones answer. The old ones stay dark.

---

## The Mechanics of Forgetting (Caretaker's Appendix)

For those who lift the frames to look at the wiring:

- **The lottery is a ranking, in two movements.** Every essay word is hashed, ordered by its hash, and dealt evenly across days 0 to 177. About two or three per day. Then every signage word, in reading order, is dealt across days 178 to 206. Offer is pinned as the last word, day 207, alone. The order is identical for every visitor, so we forget together.
- **The clock is the real clock.** The day is `floor((now minus GENESIS) / 86400000)`, where `GENESIS` is the dawn of Sept 9 2026. Words due today go by their hour, so the room moves even between midnights. There is only ever today. The page has no other states to visit. The header always names the final date: April 4 2027. Past it, the page hides everything, instruments and all, and leaves the void.
- **Warmth is a window.** Gone words less than seven days taken still answer your hand. Older ones are permanently dark. Fading words are the ones due within two days. They shimmer first.
- **The count covers the collection and the signage.** Essay prose, labels, the ritual text, the prompt in the offering box, the footer hint, the hum button, and Offer itself. Left out, on purpose: the instruments. The numbers, the dates, the docent lines that narrate the current state, your offerings (which dissolve on their own seven day schedule), and passing toasts. If the fuel gauge dissolved, you could not watch the forgetting. At the end, the void takes the instruments too, so every word goes in the end.
- **Memory is local.** Visit counts, first visit date, and offerings live in `localStorage`. The page forgets, but it keeps your ticket stubs.
- **Dust is unrepeatable.** The motes, the bold mote, the bulb Kelvin, the breathing tempo of the title. Reseeded every load. No two visits share the same air.
- **Motion respects grief.** `prefers-reduced-motion` stills the dust, the grain, and the flicker. Forgetting continues. It simply does so quietly.

---

## Colophon

*LETHE* is named for the river in the Greek underworld. The dead drank from it so they could return to the world unburdened. No memories. No ghosts. To start over, they had to agree to stop being themselves for a while.

I loved that story so much it hurt. Then I looked at what we built instead. Machines that keep everything. Every photo. Every receipt. Every version of you that you begged to outgrow.

This small building swims upstream.

*Text, design, and decay, original to this exhibit.*
*Set in Cormorant Garamond with fallback to Palatino and Georgia, for when the network, too, begins to forget.*
*Dust rendered on canvas. Grain rendered in SVG. Hum rendered at 55 Hz, while it lasts.*

Tomorrow there will be fewer words and the same amount of meaning. A winter tree has fewer leaves and the same amount of tree.

Until then. You were here. This was now. It was enough. It is already, mercifully, starting to go.

*The Caretaker*
