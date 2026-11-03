# Very Vocab

Flashcards + quiz in a single static `index.html` (RU/EN UI, works on mobile). Pick a word set from the title:

- **Very → Stronger** — replace “very + adjective” with one stronger word (50 pairs).
- **Superlative** — superlative forms of 53 adjectives (big → the biggest, beautiful → the most beautiful, good → the best).
  The card front shows the adjective and an example with a gap; the back shows the superlative, the comparative, the translation and the full example.
  The quiz asks only for the correct form: wrong options are typical mistakes (the bigest, the most big, the bigger…). No letter sections.
- **B1 Preliminary** — Cambridge B1 Preliminary vocabulary list, pp. 8–10 (“by …” – “cyclist”, 294 entries), English → Russian.
  Each card shows the part of speech and an example sentence; the back shows the translation of the word and of the sentence.
  Letter sections (All / B / C …) are built automatically from the first letter of each word.

Fonts: Unbounded (titles and the words being learned) and Manrope (interface), loaded from Google Fonts with a system-font fallback.

Progress (“Got it”) is stored per word set in `localStorage`; “Start over” resets only the current letter section.

To add words, extend the `B1` block in `index.html`, one line per entry:

```
word|part of speech|Russian|English example|Russian translation of the example
```

Several examples go in one field separated by ` · ` (the same count in both example fields).
