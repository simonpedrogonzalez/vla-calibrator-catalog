# VLA Calibrator Catalog

Parsed list of VLA calibrators from [https://science.nrao.edu/facilities/vla/docs/manuals/observing/callist](https://science.nrao.edu/facilities/vla/docs/manuals/observing/callist) to make the calibrator information easier to inspect and use.

For issues or corrections, please open an issue in this repository. You can also reach me at `simon.pedro.g@gmail.com`.

## Files

- [`calibrators_original.txt`](./calibrators_original.txt)
  Original text from NRAO VLA calibrator reference.

- [`calibrators.txt`](./calibrators.txt)
  Cleaned / formatted version of the original calibrator text.

- [`calibrators.json`](./calibrators.json)
  Structured catalog in JSON format (one object per calibrator).

- [`calibrator_bands.csv`](./calibrator_bands.csv)
  Tabular catalog in CSV format (one row per source-band entry).

- [`known_issues.csv`](./known_issues.csv)
  Validation issues identified in the original calibrator list.
