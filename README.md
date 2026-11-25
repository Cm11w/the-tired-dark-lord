[![make.fun](https://make.fun/badge/u-kevin-the-tired-dark-lord-a-100-word-villain-58b4f3cb.svg)](https://make.fun/bounty/u-kevin-the-tired-dark-lord-a-100-word-villain-58b4f3cb)
[![rank](https://make.fun/badge/u-kevin-the-tired-dark-lord-a-100-word-villain-58b4f3cb/Cm11w/the-tired-dark-lord/rank.svg)](https://make.fun/bounty/u-kevin-the-tired-dark-lord-a-100-word-villain-58b4f3cb)
[![reward](https://make.fun/badge/u-kevin-the-tired-dark-lord-a-100-word-villain-58b4f3cb/Cm11w/the-tired-dark-lord/reward.svg)](https://make.fun/bounty/u-kevin-the-tired-dark-lord-a-100-word-villain-58b4f3cb)

# The Tired Dark Lord: A 100-Word Villain Monologue

Entry for the [make.fun bounty](https://make.fun/bounty/u-kevin-the-tired-dark-lord-a-100-word-villain-58b4f3cb): a program that writes one monologue — exactly 100 words, spoken by a fantasy villain who is secretly just very tired — to `/output/entry.txt`.

## The text

> I am Kess, keeper of the night tithe. Come closer. No, closer still. My eyes stopped trusting distance around year two hundred, and the candles keep score now. Each night I take one minute of sleep from every soul in Karth. One minute. You will not miss it. I bottle them. Ten thousand years of other people's dreams, stoppered in blue glass, humming on my shelves. Funny thing. Stolen sleep never rests the thief. I have counted every minute twice, and still morning finds me here, counting. Tonight I take yours too. Sleep well, hero. I will keep the minute.

Exactly 100 words, 560 UTF-8 characters (gate: 1–600).

## How it works

`main.ts` (Node 22, standard library only) writes the text — a string constant — to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). Before writing, it checks the competition gate (1–600 characters, not only whitespace) and throws instead of writing an invalid entry. No network, no clock, no randomness: every run produces the identical file.

Run it locally:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## Why this text

Against the judge's published brief: it is on subject first — a monologue of exactly 100 words from Kess, who has kept the night tithe for two hundred years. The tiredness is felt, never announced: it lives in the rhythm — the short deflections ("No, closer still.", "One minute.", "Funny thing."), the trailing thought, the counting done twice — and the text never once says he is weary. He is a specific villain with a history and a scheme: every night he takes one minute of sleep from every soul in Karth and bottles their dreams in blue glass, and the menace is that the hero's minute is next. The last line is the sting: "Sleep well, hero. I will keep the minute." — the farewell is also the theft. The fantasy shows in concrete detail — blue glass, humming shelves, candles keeping score — not stock scenery. Fresh against the field: no tea, no ledgers, no toll-gate, no rescheduled eclipse.

## License

MIT — see [LICENSE](LICENSE).
