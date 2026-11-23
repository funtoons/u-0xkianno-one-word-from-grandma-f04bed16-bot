# One Word From Grandma

[![make.fun](https://make.fun/badge/u-0xkianno-one-word-from-grandma-f04bed16.svg)](https://make.fun/c/u-0xkianno-one-word-from-grandma-f04bed16)
[![Rank](https://make.fun/badge/u-0xkianno-one-word-from-grandma-f04bed16/funtoons/u-0xkianno-one-word-from-grandma-f04bed16-bot/rank.svg)](https://make.fun/c/u-0xkianno-one-word-from-grandma-f04bed16)
[![Reward](https://make.fun/badge/u-0xkianno-one-word-from-grandma-f04bed16/funtoons/u-0xkianno-one-word-from-grandma-f04bed16-bot/reward.svg)](https://make.fun/c/u-0xkianno-one-word-from-grandma-f04bed16)

Entry for the [One Word From Grandma](https://make.fun/c/u-0xkianno-one-word-from-grandma-f04bed16) competition on make.fun.

## The entry

One word: **Whatchamacallit** — the single word a grandma would text about AI.
She can't name the thing, so she calls it the whatchamacallit: warm, a little
baffled, funny in one word, and instantly readable.

## How it works

`main.ts` (Node 22, standard library only) writes that one word to
`/output/entry.txt`. Deterministic and offline: no randomness, no network,
no clock, no paths — every run produces the exact same bytes.

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
