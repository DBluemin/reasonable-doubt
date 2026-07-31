# Reasonable Doubt

**[Open the tool →](https://dbluemin.github.io/reasonable-doubt/)**

A detector reports a student's essay as 98% AI-written. That number is P(flag | AI use). The question facing the person reading it is P(AI use | flag). This tool works out the second one.

Built for university teaching staff and academic integrity officers deciding whether a detector flag is enough to open a formal misconduct case.

## What it does

Seven steps in a fixed order. The detector score stays hidden until step four, so the base rate and the standard of proof are both set before the answer is knowable.

The result is shown as 1,000 submissions rather than a percentage, and the tool asks which published accuracy figures you want to use. At a 12% base rate the same flag is worth 93%, 25% or 18% depending on that choice alone.

## Running it

Open `index.html`. One file, no build, no dependencies, no network calls. It works offline.

## Sources

The figures are drawn from the HEPI/Kortext Student Generative AI Survey 2026, Turnitin's published false positive rates, Weber-Wulff et al. (2023) in the *International Journal for Educational Integrity*, and Liang et al. (2023) in *Patterns*. Full citations are listed in the tool itself.

## Scope

The tool estimates one quantity: the probability that a flagged submission contains undeclared AI text, given a base rate and a stated detector accuracy. It is a reasoning aid for the person deciding whether to open a case. It is not a determination of misconduct, and it does not replace an institution's procedure or a student's right to respond.

Built as coursework. MIT licensed — use it, fork it, argue with the numbers.
