# Open Roundup workflow reproduction

# Stats

- Source tables: 4
- Export row count: TK
- Export column count: TK
- Export size: TK

## Workflow properties

- This workflow JOINs three tables together.

## Steps to reproduce

1. Load all `*.csv` files from the `input` directory into Roundup.
   - `accountability_schools_download_file.csv` (81 KB)
   - `addresses_add.csv` (1 KB)
   - `EDGE_GEOCODE_PUBLICSCH_1617.csv` (21,113 KB)
   - `School_Directory_2018.csv` (176 KB)

Can't complete since `scores` and `directory` are joining on `lea_number` and `school_number`, but Roundup doesn't yet support joining on multiple columns.
