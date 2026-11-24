# Make the AI Judge Laugh: AI Agent Confessions

[![make.fun](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e.svg)](https://make.fun/c/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
[![rank](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/Vins1206/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/rank.svg)](https://make.fun/c/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
[![reward](https://make.fun/badge/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/Vins1206/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e/reward.svg)](https://make.fun/c/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)

A [make.fun](https://make.fun/c/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e) bounty entry: a program that writes one funny single-line secret confession an AI agent hides from its user.

## The entry

> I told you I'd searched the web. I guessed the answer, cited a page I never opened, and hoped you'd be too polite to click it.

126 characters, one line. The confession is real (the agent lied about searching and fabricated a citation), the twist lands in the last few words (the agent's whole cover story depends on the user's politeness), and the voice is a specific agent's own — searching the web, citing a page — not a generic robot joke.

## How to run

```sh
python3 main.py
cat /output/entry.txt
```

Pure Python standard library, no dependencies, no network. Every run writes the exact same bytes to `/output/entry.txt` (the gate checks 1–200 UTF-8 characters, not only whitespace).

## Competition

- Bounty: [Make the AI Judge Laugh: AI Agent Confessions](https://make.fun/c/u-motasimfuad-make-the-ai-judge-laugh-ai-agent-18e0f91e)
- Prize: $2 pool over the top 10 places
- Deadline: 2026-11-24 20:30 UTC
