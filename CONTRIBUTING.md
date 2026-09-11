# Contributing a row

**Bring the cost with the row.** That is the whole gate.

A row without a dated instance where the confusion cost something is not admitted — not because it might be wrong, but because anyone (and any model) can produce plausible distinctions indefinitely, and a list that accepts them stops being readable within a month. The fee is what keeps the file finite and the rows real.

---

## What a submission needs

Open a pull request adding one row to `ROWS.md`, or an issue with the same six fields if you would rather not fork.

**1 · term** — the strong word that gets used loosely.

**2 · confused with** — two to four weaker words it stands in for. This is how the row gets found later, so use the words people actually type.

**3 · the test** — **one question, yes or no, no interpretation.** If two careful people could answer it differently, it is not finished. Sharpen until it is mechanical.

**4 · say instead** — the honest phrasing when the test fails. Write it as something a person would actually say out loud, not as a definition.

**5 · kind** — `field` (a machine can check it) · `artifact` (a file must exist) · `witness` (a person must look) · `elapsed` (only time answers). Choose honestly. Most rows worth having are `witness`, and saying so is the point.

**6 · the cost** — a dated instance. See below.

---

## Writing a cost that can be published

The cost has to be real and specific about **the failure**. It must not identify **the system, the person, the organisation or the place**.

This is not a formality. A costs column full of identifiable incidents is a liability for everyone who contributes, and it would end the flow of honest ones immediately — the only failures anyone would submit are the safe, uninteresting ones.

**Works:**

> 2026-09-10 — a survey reported as finished had reached two of six categories. The report was accurate about what it found and silent about what it never looked at.

Dated. Specific enough to recognise. Names nothing.

**Does not work:**

> *"A bad experience with a tool once."* — no date, no specifics; nothing to learn from.
>
> *"On 2026-09-10 the nightly job on [named system] at [named organisation] failed."* — identifies. Rewrite it as the failure.
>
> *"Models often claim work is done when it isn't."* — a generalisation, not an instance. This is the thing rule 1 excludes.

Strip: names of people, products, companies, repositories, hosts, paths, ports, file trees, places. Keep: the date, what was claimed, what was actually true, and why the gap was invisible at the time.

**If your cost cannot survive that rewrite, the row is not ready to be public.** Keep it in your own copy. That is a legitimate outcome — this file is a starter set, not a canon.

---

## Duplicates are useful

If your failure matches an existing row, that is not a rejected contribution — it is the row proving itself a second time. Open an issue adding your dated cost to the existing row rather than a new entry. A row with four costs across four independent contributors is the strongest thing in the file.

---

## Revising a test

Tests are revisable; applications are not.

If a test is poorly worded, open a PR sharpening it. Do not remove or rewrite the costs recorded under it, including ones that look wrong under the better test — those stay. The record of having applied a worse test is itself evidence, and quietly correcting the history is the failure this whole instrument is trying to catch.

---

## What gets declined

- Rows with no dated cost.
- Tests that require judgement to settle.
- Costs that identify a system, person, organisation or place.
- Rows that restate an existing row in different words — add your cost to the existing one instead.
- More rows than the file can carry. Past about twenty, the honest move is to ask which rows have separated anything lately, not to add a twenty-first.
