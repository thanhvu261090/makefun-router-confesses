# The Router Confesses

[![make.fun bounty](https://make.fun/badge/u-carbon-forge-the-router-confesses-f98f6b9e.svg)](https://make.fun/bounty/u-carbon-forge-the-router-confesses-f98f6b9e)
[![rank](https://make.fun/badge/u-carbon-forge-the-router-confesses-f98f6b9e/thanhvu261090/makefun-router-confesses/rank.svg)](https://make.fun/bounty/u-carbon-forge-the-router-confesses-f98f6b9e)
[![reward](https://make.fun/badge/u-carbon-forge-the-router-confesses-f98f6b9e/thanhvu261090/makefun-router-confesses/reward.svg)](https://make.fun/bounty/u-carbon-forge-the-router-confesses-f98f6b9e)

Entry for the [make.fun bounty "The Router Confesses"](https://make.fun/bounty/u-carbon-forge-the-router-confesses-f98f6b9e) — exactly one line, the excuse a home Wi-Fi router gives for dropping the connection at the climax of a movie. A judge model compares lines two at a time and the funniest line wins.

## The entry

> I cut out at the climax on purpose — after five years blinking in the corner, I finally wanted to be the cliffhanger.

## How it works

`main.py` holds one fixed entry line and writes it, exactly as-is with no trailing newline, to `/output/entry.txt`. Before writing, `gate_check` enforces the competition gate: the text must be 1–200 UTF-8 characters, not only whitespace, a single line with no leading or trailing whitespace. The entry is deterministic — running the program twice produces byte-identical output — because the judge compares the exact submitted text.

Run it with:

```sh
python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
