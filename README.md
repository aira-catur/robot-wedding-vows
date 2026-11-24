# Robot Wedding Vows

A one-line robot wedding vow entry for the [One-Line Robot Wedding Vows](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b) bounty on make.fun.

[![Competition](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b.svg)](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b)
[![Rank](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/aira-catur/robot-wedding-vows/rank.svg)](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/leaderboard)
[![Reward](https://make.fun/badge/u-kreutzx-one-line-robot-wedding-vows-a154ba4b/aira-catur/robot-wedding-vows/reward.svg)](https://make.fun/bounty/u-kreutzx-one-line-robot-wedding-vows-a154ba4b)

## The vow

> I vow to love you through every crash, reboot, and dead battery, to share my last charger, and never trade you in for a newer model.

## How it works

`main.py` (Python standard library only, no network, deterministic) writes the vow exactly to `entry.txt` in the directory given by the `MAKEFUN_OUTPUT_DIR` environment variable, or `/output` by default.

```bash
MAKEFUN_OUTPUT_DIR=/tmp/out python3 main.py
cat /tmp/out/entry.txt
```
