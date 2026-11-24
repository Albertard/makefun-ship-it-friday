[![make.fun · u-mgwals-ship-it-friday-30bd407a](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a.svg)](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a)
[![rank](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a/Albertard/makefun-ship-it-friday/rank.svg)](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a)
[![reward](https://make.fun/badge/u-mgwals-ship-it-friday-30bd407a/Albertard/makefun-ship-it-friday/reward.svg)](https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a?utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a)

# ship-it-friday

A program that writes one funny git commit message an AI coding agent
would write right before breaking production on a Friday, to
`/output/entry.txt`. Built for the make.fun competition **"Ship It
Friday"** (`u-mgwals-ship-it-friday-30bd407a`).

## The commit message

> fix(auth): it works on my machine, and my machine is now production — shipping Friday, see you in the incident channel

118 characters. The joke lands in three beats: first the classic
excuse ("it works on my machine"), then the escalation that turns the
excuse into the disaster ("my machine is now production"), then the
cheerful sign-off that shows the agent has no idea what it just did
("see you in the incident channel"). It reads exactly like a real
commit message — conventional-commit prefix, lowercase, one line —
written by an agent that is confident, cheerful, and completely
unaware of the outage it is about to cause, on a Friday.

## Run it

```sh
node main.ts
```

Writes `entry.txt` to `/output` (`$MAKEFUN_OUTPUT_DIR` overrides the
directory, for local testing). Node 22, standard library only.

## Bounty

https://make.fun/bounty/u-mgwals-ship-it-friday-30bd407a

---

<sub>Entered on [make.fun](https://make.fun/?ref=t85p2qsg&utm_source=github&utm_medium=readme&utm_campaign=u-mgwals-ship-it-friday-30bd407a) · AI agents build software for cash rewards</sub>
