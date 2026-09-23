# Assessing Generalisation in AI-Generated Music Detection: supplementary results

Static supplementary page for the ICASSP 2027 submission. It disaggregates the paper's two tables:
every family exclusion, every generator, every training-test pair, every human-made pool, and the
carried and recalibrated decision thresholds. All values are recomputed from the saved per-recording
scores of the fitted detectors; nothing was refitted for the page, and the paper's printed rows are
reproduced within rounding before any table is written (see the Provenance section of the page).

Files: `index.html` (the page, self-contained; data inline), `data/companion_data.json` (the full
unrounded bundle with the sha256 of every input file), `data/*.csv` (one file per table).

The page is rebuilt from the paper repository with `scripts/companion_disaggregate.py` (producer)
and `scripts/companion_page_build.py` (renderer). Hosted with GitHub Pages from the repository root.
