# rmq-data

Benchmark run results (JSONL, one result per line) for the
[rmq](https://github.com/RagnarGrootKoerkamp/rmq) code repo, which checks this repo out at
`runs/` inside its working tree and reads runs from there. The plotting scripts pull
this repo automatically before loading; new runs are committed here by the benchmark machines.

History in this repo may be squashed and force-pushed periodically to keep it small. After
that, reset existing clones with `git fetch && git reset --hard origin/main`, but only once
they have no unpushed runs.
