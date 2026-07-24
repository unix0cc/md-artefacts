# md-artefacts

Plain-text boot/failure proof logs for the sun4v MD/hv-config emulation
test matrix in [unix0cc/md](https://github.com/unix0cc/md)
(`docs/index.html`).

Deliberately a separate repo, not a subdirectory of `md`: cloning `md`
never pulls this content down. Each PASS/FAIL cell in the matrix links
here directly, e.g.:

    https://unix0cc.github.io/md-artefacts/<build-slug>__<os-slug>.txt

## Naming convention

`<build-slug>__<os-slug>.txt`, matching the row (build) and column (OS
image) labels in the matrix, e.g. `snv_134-256__snv_134-ai-iso.txt` for
the `snv_134/256` build tested against the `snv_134 ai ISO` column.

## Publishing

GitHub Pages, source: `main` branch, `/ (root)`. Any `.txt` file added
here becomes reachable at `https://unix0cc.github.io/md-artefacts/<file>`
once Pages finishes building.
