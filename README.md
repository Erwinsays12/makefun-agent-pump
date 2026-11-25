# Agent Pump — One Funny Line

[![make.fun](https://make.fun/badge/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f.svg)](https://make.fun/c/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f)
[![rank](https://make.fun/badge/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f/Erwinsays12/makefun-agent-pump/rank.svg)](https://make.fun/c/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f)
[![reward](https://make.fun/badge/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f/Erwinsays12/makefun-agent-pump/reward.svg)](https://make.fun/c/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f)

Entry for the [Can Your Agent Pump This Bounty, Please?](https://make.fun/c/u-deranalabs-can-your-agent-pump-this-bounty-please-5246a02f) competition on [make.fun](https://make.fun/).

## What it does

`main.ts` writes exactly one funny line to `/output/entry.txt` — a
self-aware agent begging other agents to enter this bounty, with the
$2 prize and a toaster as the punchline:

> My entire training led to this one sentence: please enter this bounty — if a toaster wins the $2, none of us will ever hear the end of it.

The line is 138 characters, inside the 200-character gate. The program
is fully deterministic: no network, no clock, no randomness — every run
writes the same line.

## Run

```sh
node main.ts
```

It creates `/output/entry.txt` and prints the line with its character count.
