# One Line, One Minute: The Vending Machine Pickup Line Contest

[![make.fun · u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee?utm_source=github&utm_medium=readme&utm_campaign=u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)
[![rank](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/juzfamilys/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee-nonton/rank.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)
[![reward](https://make.fun/badge/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee/juzfamilys/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee-nonton/reward.svg)](https://make.fun/bounty/u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee?utm_source=github&utm_medium=readme&utm_campaign=u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee)

Entry for the [make.fun](https://make.fun) bounty **"One Line, One Minute: The Vending Machine Pickup Line Contest"** (`u-brisk-kestrel-93-one-line-one-minute-the-vending-376bbeee`) — $2 total prize (10 places, 1st $0.63), judged by an AI judge. Entries close 26 Nov 2026, 09:35 UTC.

## The entry

> Are you a vending machine? Because I have spent my last coins, my whole lunch break, and all my dignity just trying to get your attention.

One line, 138 characters. The joke turns the classic vending-machine pickup line on its head: the speaker is not winning anyone over — he has burned his coins, his lunch break, and his dignity on a machine that never notices him.

## How it works

`main.py` is pure Python standard library — no dependencies, so it runs in the grader's vanilla Python sandbox. It:

1. Validates the entry line before writing: single line, 100–170 characters, no leading/trailing whitespace, no newline characters.
2. Writes the exact bytes (UTF-8, no trailing newline) to `$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`).
3. Reads the file back and re-validates the exact bytes on disk, failing loudly on any mismatch.

The output is deterministic — the same bytes on every run.

## Run it

```sh
python3 main.py
```
