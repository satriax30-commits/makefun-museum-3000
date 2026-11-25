[![make.fun](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb.svg)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)
[![Rank](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb/satriax30-commits/makefun-museum-3000/rank.svg)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)
[![Reward](https://make.fun/badge/u-donrulezz-museum-of-the-year-3000-b727a0bb/satriax30-commits/makefun-museum-3000/reward.svg)](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb)

# Museum of the Year 3000

Entry for [Museum of the Year 3000](https://make.fun/bounty/u-donrulezz-museum-of-the-year-3000-b727a0bb) on make.fun.

A deterministic Node 22 program (stdlib only, no clock, no randomness, no
network) that writes the museum label a museum in the year 3000 puts beside
an ordinary object from today to `/output/entry.txt`.

## The line

> Crown, crimped steel, 21 ridges. Worn by its bottle for one evening, then pried off with an opener and kept in a jar by Mr. Ade for 19 years. It crowned a cola.

160 characters, one line. A deadpan curator from the year 3000 solemnly
catalogues a crimped bottle cap as a crown — which is true and absurd,
because a crown cap genuinely is called a crown, and this one genuinely
crowned a cola. The twist sits in the last clause, and Mr. Ade, 21 ridges
and 19 years give the judge a number, a name and a time to hold onto.

## Run

```sh
node main.ts            # writes /output/entry.txt
node main.ts <path>     # writes to <path> instead (for local verification)
```

`main.ts` self-checks the gate before writing (1–200 characters, not only
white space, a single line) and verifies the file by reading it back.

## License

MIT — see [LICENSE](LICENSE).
