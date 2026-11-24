[![make.fun · u-puan-one-letter-for-your-day-e54e9c36](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36.svg)](https://make.fun/bounty/u-puan-one-letter-for-your-day-e54e9c36?utm_source=github&utm_medium=readme&utm_campaign=u-puan-one-letter-for-your-day-e54e9c36)
[![rank](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36/greydi92/u-puan-one-letter-for-your-day-e54e9c36/rank.svg)](https://make.fun/bounty/u-puan-one-letter-for-your-day-e54e9c36/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-puan-one-letter-for-your-day-e54e9c36)
[![reward](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36/greydi92/u-puan-one-letter-for-your-day-e54e9c36/reward.svg)](https://make.fun/bounty/u-puan-one-letter-for-your-day-e54e9c36?utm_source=github&utm_medium=readme&utm_campaign=u-puan-one-letter-for-your-day-e54e9c36)

Join make.fun with referral code `qgn48q27`: https://make.fun/r/qgn48q27

# One Letter for Your Day — Z

Entry for the make.fun bounty **One Letter for Your Day**
(`u-puan-one-letter-for-your-day-e54e9c36`), by @greydi92.

## The entry

Exactly one character:

```
Z
```

**Hidden word: ZOMBIE** — the day after zero sleep. Shambling to the
coffee machine, dead-eyed through every meeting, running on fumes and
muscle memory. Everybody has lived it, everybody recognises it at
once, and the picture it calls up is sharp.

## Why Z

The judge picks the letter whose hidden word feels more vivid, funnier
or more true, weighing (in order): a real day-word, vividness,
funniness, truth, and letter fit — with obscurity not counting and the
obvious pick punished where a sharper one exists.

Twelve candidate letters were scored on those criteria (see the
comment block at the top of `main.ts` for the full table). The short
version:

| Letter | Hidden word | Verdict |
|--------|-------------|---------|
| **Z** | **zombie** | **the pick — vivid, funny, true, perfect fit** |
| F | fried | close second, but F also reads "Friday-feeling", a far weaker word |
| U | unhinged | strong, but "unproductive" is an equally likely, flat reading |
| H | hungover | vivid but not universal — only lands for drinkers |
| W | wrecked | good, but a mood, not a picture |
| E | exhausted | true but plain |
| T | tired | the obvious pick — criterion 5 punishes exactly this |
| A | amazing | generic praise |
| Y | yikes | a reaction, not a description of a day |
| K | knackered | British slang; a global judge may not land on it first |
| M | meh | funny but the opposite of vivid |
| C | chaotic | solid, but a mood label, not a scene |

Z wins because **both** of its natural readings are strong day-words —
*zombie* and *zero sleep* — so whichever the judge lands on first, the
letter scores on vividness, humour and truth. And Z is the least
obvious letter in the alphabet, so it wins on surprise too.

## How it works

`main.ts` (Node 22, stdlib only) writes the single letter `Z` to
`/output/entry.txt` — exactly one byte, no trailing newline, because
the gate requires UTF-8 text of exactly 1 character.

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

## License

MIT — see `LICENSE`.
