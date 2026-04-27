# VLA Calibrator Catalog

Parsed list of VLA calibrators from [https://science.nrao.edu/facilities/vla/docs/manuals/observing/callist](https://science.nrao.edu/facilities/vla/docs/manuals/observing/callist) to make the calibrator information easier to inspect and use.

For repository issues or corrections, please open an issue in this GitHub repository.

For questions or direct contact, reach me at `simon.pedro.g@gmail.com`.

## Files

- [`calibrators_original.txt`](./calibrators_original.txt)
  Original source text snapshot from the NRAO VLA calibrator reference/listing above, kept for provenance against the original calibrator material.

- [`calibrators.txt`](./calibrators.txt)
  Cleaned version of the original calibrator text, with formatting fixes applied so it can be parsed more reliably.

- [`calibrators.json`](./calibrators.json)
  Parsed structured catalog in JSON format, with one source object per calibrator and nested per-band entries.

- [`calibrator_bands.csv`](./calibrator_bands.csv)
  Flattened tabular version of `calibrators.json`, with one row per source-band entry.

- [`known_issues.csv`](./known_issues.csv)
  Known validation or review issues identified while checking the parsed catalog output.
