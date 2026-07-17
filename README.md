# inspired-by

*The map from the research we admire to the things we built because of it.*

> **The recognition layer.** Every entry names a paper, the OpenCnid repo or
> feature it shaped, and why — with receipts. If we can't point at a commit, a
> design doc, or a shipped feature that exists because of a paper, the paper
> doesn't get an entry. Admiration is free; entries are earned.

**This repo holds interpretations, on purpose.** The facts live next door in
[densities](https://github.com/OpenCnid/densities), our chain-of-density
notes collection, and the papers themselves outrank everything. Authority runs
one direction — **paper → note → entry** — so nothing here is ever evidence for
anything except what *we* did about it.

## Entry format

Bracketed names are generation instructions, not literal text; write each entry
into this frame.

```markdown
## {Paper_Title} — {Lab_Or_First_Author_And_Year}

- **paper:** {Canonical_Link_With_Pinned_Version}
- **our note:** {Link_Into_The_Densities_Repo}
- **what it shaped:** {OpenCnid_Repo_Or_Feature_Link}
- **the receipt:** {Commit_PR_Design_Doc_Or_Shipped_Feature_That_Exists_Because_Of_It}

{Two_To_Four_Sentences_On_What_The_Paper_Changed_In_Our_Work_Specific_And_Grateful_Without_Hype}
```

## House rules

- **Receipts or it didn't happen.** An influence claim links to the artifact it
  influenced. "This shaped our thinking" with nothing attached is a tweet, not
  an entry.
- **No implied endorsement.** Being inspired by a lab's work does not mean that
  lab knows we exist, let alone approves of what we built with it. We say this
  once here so no entry has to.
- **Their science, our reading.** If an entry misstates a finding, the fix goes
  in source-first: correct the note in densities, then the entry here. Open an
  issue; corrections are the fastest PRs we merge.
- **Gratitude, not marketing.** Entries say what changed in our work, not how
  great we are for having read a paper.

## The entries

## From Sparse to Dense: GPT-4 Summarization with Chain of Density Prompting — Adams et al., 2023

- **paper:** [arXiv:2309.04269](https://arxiv.org/abs/2309.04269) (pinned v1, 2023-09-08) · [published version](https://aclanthology.org/2023.newsum-1.7/)
- **our note:** [densities / 2023-chain-of-density](https://github.com/OpenCnid/densities/blob/main/notes/columbia-salesforce/2023-chain-of-density/cod.md)
- **what it shaped:** [densities](https://github.com/OpenCnid/densities) — the entire repo
- **the receipt:** [METHOD.md](https://github.com/OpenCnid/densities/blob/main/METHOD.md) and the five-tier structure of every note in the collection

This paper is why densities exists and why it looks the way it does. Its
fixed-length constraint became the engine of our note format — without it,
"add detail" makes summaries longer, never denser. Its human-preference result
(median preferred step three, not five) is why we keep every tier instead of
shipping only the densest, and its low annotator agreement (Fleiss' κ = 0.112)
is why the reader, not the writer, picks the tier. We adapted rather than
adopted: ~150-word tiers instead of ~70, entities broadened to ablations and
limitations, and a locator citation on every claim.

## License

[CC BY 4.0](LICENSE.md) © OpenCnid Labs.
