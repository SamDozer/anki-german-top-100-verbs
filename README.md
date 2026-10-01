# Top 100 German Verbs: an Anki deck with conjugations, examples, and natural audio

An Anki deck of the 100 most common German verbs, for A1–B1 learners.
Each verb has its conjugations, an everyday example sentence, a short grammar tip, and audio from a natural-sounding voice.

It is improved from the AnkiWeb shared deck **[Top 100 German Verbs](https://ankiweb.net/shared/info/609348355)**.
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

## One answer per prompt

The English → German and type-the-answer cards show only the English meaning, so every prompt is written to lead to exactly one verb:

| Prompt | Answer |
|---|---|
| to think (about sth: denken an) | denken |
| to believe; to think (= I believe) | glauben |
| to mean (what sb means); to think (opinion) | meinen |
| to find; to find sth good / bad (opinion) | finden |
| to go (on foot) / to run; colloquial: to walk | gehen / laufen |
| to make; to do (everyday) / to do (≠ machen; set phrases) | machen / tun |
| to speak (a language / with sb) / to talk (casual) | sprechen / reden |
| to put (upright) / to lay, to put (flat) / to set; sich setzen = to sit down | stellen / legen / setzen |

Nine verbs also have a short pronunciation tip ("sound: …"): *st / sp* at the start of a word, *z = ts*, *ei* vs *ie* (*schreiben → schrieb*), *w = v*, *v = f*, *ö*, *ü*.

## Tags for focused drills

Use them with **Tools → Create Filtered Deck** for short extra sessions (keep your daily reviews in the main deck):

| Search | Verbs |
|---|---|
| `tag:verb::perfekt-sein` | 12 verbs whose Perfekt uses **sein** (ist gegangen, ist geblieben, …) |
| `tag:verb::dative` | helfen, folgen, gehören, entsprechen, glauben, fehlen |
| `tag:verb::stem-change` | 21 verbs with a present-tense vowel change (du gibst, er fährt, du liest, …) |
| `tag:verb::separable` | anfangen, ansehen, aussehen, anbieten, vorstellen, darstellen |
| `tag:verb::modal` | können, müssen, dürfen, sollen, wollen, mögen |

Level and study tags:

| Tag | Verbs |
|---|---|
| `A1::Goethe` | 62 verbs that are on the Goethe-Zertifikat A1 word list |
| `A1::core` | 78: the A1 verbs plus 16 very common everyday verbs (`level::A2-everyday`: *denken, zeigen, versuchen, verlieren …*) |
| `level::A2-B1` | 22 less urgent verbs (*entsprechen, darstellen, betreffen …*): learn them after the core |
| `A1::confusion` | 44 verbs that belong to an easily confused pair or group |
| `A1::grammar` / `A1::false_friend` / `A1::pronunciation` | 42 / 5 / 9 |

To start with the most useful verbs, use **Tools → Create Filtered Deck** with `deck:"Top 100 German Verbs" tag:A1::core`.

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
