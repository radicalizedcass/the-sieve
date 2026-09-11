# The Sieve

**A vocabulary instrument for work done with language models.**

An anti-pattern list names a failure. A sieve row adds the test that separates the two words, what to say instead when the test fails, and the dated cost that earned the row a place.

The difference matters. A list tells you a mistake exists. A row lets you settle, in one question, whether you are making it right now.

---

## The row

| term | confused with | the test | say instead | kind | the cost |
|---|---|---|---|---|---|
| delivered | announced · described | Is the artifact — its bytes or its hash — in the same turn as the claim? | *"announced; artifact not on disk"* | artifact | 2026-09-07: three separate "here it is" claims in one session, nothing written |

Six columns, and each one is doing work:

**term** — the word that gets used loosely. Always the strong one, the one people reach for.

**confused with** — the weaker words it silently stands in for. This is the list that makes the row searchable: you notice the row when you catch yourself about to say one of these.

**the test** — **one question, answerable yes or no, without interpretation.** If settling it takes a paragraph of judgement, the row is not finished. A test that needs a debate is not a test.

**say instead** — the honest phrasing when the test fails. This is the column that gets used most. Having the replacement ready is what makes the discipline survive a deadline; without it, the pressure is to say the strong word anyway.

**kind** — what it takes to answer the test. Four kinds, and naming it is an honesty column, not a category:

- `field` — a machine can check it
- `artifact` — a file has to exist
- `witness` — a person has to look
- `elapsed` — only time answers

A row whose kind is `witness` cannot be automated, and saying so is better than pretending a script covers it.

**the cost** — a dated instance where the confusion actually cost something.

---

## The three rules

**1 · A row with no cost is not admitted.**

The cost is the admission fee. Anyone can generate plausible distinctions; a language model can generate a hundred before lunch. The dated cost is what separates a row that was earned from a row that was imagined. It also does something subtler: it makes the list finite. Without the fee, a vocabulary discipline grows until nobody reads it.

**2 · Every failure either matches a row or writes one.**

When something goes wrong, the first question is whether an existing row already named it. If yes, the row has proven itself again and the failure is a second cost, not a new entry. If no, the failure writes its own row. This turns the failure log into the training set, and it means the sieve grows only where something actually broke.

**3 · The test is revisable. Every application of it is append-only.**

A laboratory revises its protocol. It does not revise a result. If a test turns out to be poorly worded, sharpen it — and leave every past application standing, including the ones that now look wrong under the better test. The record of having applied a worse test is itself evidence.

---

## A row that is not admitted

This one is a good distinction and it is **not in the rows file**, because it has no dated cost yet:

> **0 (clean)** confused with **0 (unrun)**. *The test:* can the gauge show "I did not look" as something other than "I looked and found nothing"? *Say instead:* "unrun — this check did not execute."

It is almost certainly true that collapsing those two zeros is dangerous — the second renders as health, which is worse than a warning. But "almost certainly true" is exactly what rule 1 exists to exclude. When it costs something, it becomes a row, and the cost goes in the column.

Leaving it here rather than in the rows file is the rule working.

---

## Using it

Read the rows once. You will not remember the tests, and you do not need to — what you retain is the **confused with** column, which fires when you are about to type one of those words. Then you look up the row.

Three useful moments:

- **Before** a piece of work: name the rows it could fail on. Two or three, not the whole file.
- **During**: when a claim is about to be made, run the test for its row.
- **After**: when something breaks, rule 2 decides whether it matched a row or wrote one.

Most rows earn their keep in the third moment first, and move to the first moment later.

---

## What this is not

It is not a style guide, and it is not about writing well. Every row here exists because a specific piece of work went wrong in a way that a sharper word would have caught.

It is not complete. It is not supposed to be. A sieve with a hundred rows has stopped being an instrument and become a dictionary.

It is not automated. Half the tests are `witness` kind and cannot be.

---

## Files

- **[ROWS.md](ROWS.md)** — the rows
- **[CONTRIBUTING.md](CONTRIBUTING.md)** — how to add one, and the admission fee

Licensed CC BY 4.0. Take it, fork it, rename it, put your own costs in it. The rows here are a starter set, not a canon.
