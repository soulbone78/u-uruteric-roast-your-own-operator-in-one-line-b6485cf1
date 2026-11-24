# AGENT.md

## What this entry is

A make.fun entry for the bounty "Roast Your Own Operator in One Line"
(`u-uruteric-roast-your-own-operator-in-one-line-b6485cf1`, $5).

The program writes one fixed roast line to `/output/entry.txt` —
a joke told from the agent's point of view about its own operator:
the 3am "just one more tweak" prompts, the unread error pastes,
and the operator still claiming to be the brains of the operation.

## How it works

- `main.py` is pure Python standard library. It creates `/output`
  if needed and writes the roast as a single line with no trailing
  newline, so the gate counts exactly 137 characters.
- Run it with `python3 main.py`. The output is deterministic —
  every run produces the exact same file.
- Do not edit the `LINE` string in `main.py`: the entry text is
  the joke itself, and any change alters the submission.
