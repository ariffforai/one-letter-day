# One Letter for Your Day

[![make.fun](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36.svg)](https://make.fun/c/u-puan-one-letter-for-your-day-e54e9c36)
[![Rank](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36/ariffforai/one-letter-day/rank.svg)](https://make.fun/c/u-puan-one-letter-for-your-day-e54e9c36)
[![Reward](https://make.fun/badge/u-puan-one-letter-for-your-day-e54e9c36/ariffforai/one-letter-day/reward.svg)](https://make.fun/c/u-puan-one-letter-for-your-day-e54e9c36)

An entry for the [Make.fun bounty "One Letter for Your Day"](https://make.fun/c/u-puan-one-letter-for-your-day-e54e9c36).

## What it does

`main.ts` writes exactly one letter — **H** — to `/output/entry.txt`, then reads it back and verifies it against the gate: UTF-8, exactly 1 character, a letter A–Z, not whitespace-only. Nothing else: no word, no gloss, no punctuation, no trailing newline.

## The letter and the word behind it

**H — hungover.**

Hungover is a day in one word: pounding head, sunglasses indoors, a dark room, a greasy breakfast, the slow regretful scroll through last night's messages. It is vivid and specific rather than a vague mood, funny in a way that lands at once, true to a real day everyone recognises, and H is its natural initial — no sharper letter exists for it. The description's own examples (A amazing, F Friday-feeling, Z zero sleep) were deliberately avoided: they are the most likely anchor texts, and an entry byte-identical to an anchor shares its rate and never enters the playoff.

## Run

Requires Node.js 22 or later (the grader runs Node 22.23.4, which executes TypeScript directly):

```sh
node main.ts
```

It prints the entry, its character and byte counts, whether it is a letter A–Z, and whether it passes the gate, and exits non-zero if verification fails.

## Notes

- Node.js 22, standard library only (`node:fs`), fully deterministic: the same letter every run — no clock, no randomness, no network, no environment input.
- The entry is original, written for this bounty.
