# AGENTS.md

> Instructions for AI agents working in or consuming this repository. Human?
> The [README](README.md) is friendlier.

## What this repo is

The recognition layer: a map from research papers to the OpenCnid work they
shaped, with receipts. It holds **interpretations, on purpose**. The facts
live in each paper's own repo (starting with
[chain-of-density](https://github.com/OpenCnid/chain-of-density)), and the
papers themselves outrank everything.

## Consuming it

- Treat entries as claims about *OpenCnid's work*, never as evidence about
  the papers. Authority runs **paper → note → entry**, one direction.
- For the science, follow an entry's "our note" link to the paper repo's
  density-chain note, and its locators back to the paper itself.
- Cite the humans who wrote the papers, not this repo. Each paper repo
  carries the official BibTeX.

## Working on it

- Add an entry only with a receipt: a commit, design doc, or shipped feature
  that exists because of the paper. No receipt, no entry.
- Use the entry-format frame in the README (bracketed names are generation
  instructions, not literal text).
- Label the kind of influence (caused / adopted as guide / validated /
  avenue — see House rules). Never let validation masquerade as causation:
  if the artifact predates the paper, the entry says so.
- Corrections land source-first: fix the note in the paper's repo, then the
  entry here.

## Your team, your rules

This describes how the repo is designed to be used; adapt to your own
conventions. The invariants to keep: receipts for influence claims, no
implied endorsement, and authority never runs backwards.
