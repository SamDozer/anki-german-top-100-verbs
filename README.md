# Top 100 German Verbs: an Anki deck with conjugations, examples, and natural audio

An Anki deck of the 100 most common German verbs, for A1–B1 learners.
Each verb has its conjugations, an everyday example sentence, a short grammar tip, and audio from a natural-sounding voice.

It is a full rework of the "Top 100 German Verbs" shared deck from AnkiWeb.
That deck had only the verb, a one-line meaning, and robotic TTS. The verb list and its order come from it; everything else is new.

## What each note has

| Field | Example (*helfen*) |
|---|---|
| Verb + audio | **helfen** 🔊 |
| Meaning | to help |
| Präsens | ich helfe · du hilfst · er hilft · ihr helft |
| Präteritum | er half |
| Perfekt | er hat geholfen (with **sein** where needed: *er ist gegangen*) |
| Example + audio | *Kannst du mir helfen?* 🔊 (Can you help me?) |
| Tip | takes the **dative** (*mir, dir*) · e→i: du **hilfst** |

The tips cover what A1–A2 learners get wrong most often:
- case and fixed prepositions: *helfen* + dative, *warten **auf***, *sich interessieren **für***
- false friends: *bekommen* ≠ become, *ich will* ≠ I will
- confusable pairs: *kennen / wissen*, *wohnen / leben*, *lernen / studieren*, *stellen / legen*, *sitzen / sich setzen*, *meinen / bedeuten*
- separable verbs and stem-changing verbs
- useful set phrases: *Du fehlst mir* = I miss you, *Es tut mir leid*, *Wie läuft's?*

## Cards (3 per verb)

1. **Deutsch → English**: the verb, with its audio.
2. **English → Deutsch**: the meaning only. No audio plays on this question side, so nothing gives the answer away.
3. **Type the German verb**: type the infinitive yourself.

All conjugations, the example, and the tip are shown on the answer side.
The layout is clean and also works in Anki's night mode.

## Tags for focused drills

Use them with **Tools → Create Filtered Deck** for short extra sessions (keep your daily reviews in the main deck):

| Search | Verbs |
|---|---|
| `tag:verb::perfekt-sein` | 12 verbs whose Perfekt uses **sein** (ist gegangen, ist geblieben, …) |
| `tag:verb::dative` | helfen, folgen, gehören, entsprechen, glauben, fehlen |
| `tag:verb::stem-change` | 21 verbs with a present-tense vowel change (du gibst, er fährt, du liest, …) |
| `tag:verb::separable` | anfangen, ansehen, aussehen, anbieten, vorstellen, darstellen |
| `tag:verb::modal` | können, müssen, dürfen, sollen, wollen, mögen |

## Files

| File | What it is |
|---|---|
| `Top-100-German-Verbs.apkg` | The deck. Import it with **File → Import**. It contains 200 audio clips and no review history. |
| `verbs.tsv` | All content as a tab-separated table, for reading, editing, or reuse. |
| `card_templates.html`, `card_style.css` | The card templates and styling. |

## Audio

The verbs are read by a Microsoft neural German voice (Katja), and the example sentences by a second one (Conrad).
Both were generated with [edge-tts](https://github.com/rany2/edge-tts) at a slightly slower speed for learners.

## Notes

- Präteritum and Perfekt use the *er/sie/es* form, which is enough to derive the others.
- *wir*, *sie* (they) and *Sie* (formal you) always match the infinitive, except for *sein* (*wir sind*).
- If you find a mistake, please open an issue.
