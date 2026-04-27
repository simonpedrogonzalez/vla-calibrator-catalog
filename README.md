# VLA Calibrator Catalog

This repository packages a parsed list of VLA calibrators from the NRAO VLA calibrator reference pages:

- Official list of VLA calibrators: [https://science.nrao.edu/facilities/vla/docs/manuals/observing/callist](https://science.nrao.edu/facilities/vla/docs/manuals/observing/callist)
- VLA calibrator manual: [https://science.nrao.edu/facilities/vla/docs/manuals/cal](https://science.nrao.edu/facilities/vla/docs/manuals/cal)

This was created to make the calibrator information easier to inspect, validate, and reuse in downstream analysis workflows.

Support: `simon.pedro.g@gmail.com`

## Files

- `calibrators_original.txt`
  Original source text snapshot from the NRAO VLA calibrator reference/listing above, kept for provenance against the original calibrator material.

- `calibrators.txt`
  Cleaned version of the original calibrator text, with formatting fixes applied so it can be parsed more reliably.

- `calibrators.json`
  Parsed structured catalog in JSON format, with one source object per calibrator and nested per-band entries.

- `calibrator_bands.csv`
  Flattened tabular version of `calibrators.json`, with one row per source-band entry.

- `known_issues.csv`
  Known validation or review issues identified while checking the parsed catalog output.
