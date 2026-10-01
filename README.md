# A Testable Local Semantic Layer

An engineering-led research book about building a cheap, local, testable
semantic layer while Python retains policy, provenance, history and authority.

First draft: research as of **2026-10-01**.

Read the book: <https://d3banjan.github.io/system1-research-book/>.

This repository is a generated, privacy-reviewed publication projection. Its
Markdown sources are not an independently edited second manuscript. The
author's private research wiki remains canonical; corrections are made there,
exported, reviewed and rendered again. Private inputs and raw model reasoning
are not published.

## Build

The first release used the official **Quarto 1.10.18** CLI:

```sh
quarto render
```

Execution is disabled. Rendering does not rerun inference, training, notebooks
or the research experiments. Quarto is a standalone publishing CLI, not a
Python package; a uv-managed Python/Jupyter environment is optional for other
computational projects and unnecessary for this static book.

GitHub Pages serves the committed `docs/` artifact from `main`. Local visual,
navigation, privacy and evidence-link checks precede each publication push.
`provenance.json` records accepted source hashes and asset transformations.

The numerical results are scoped diagnostics, not deployment certification.
Candidate model annotations are proxy references, not human gold. No task
fine-tuning has started. Future experiments remain explicitly deferred.
