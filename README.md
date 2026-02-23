# Midterm-Project-Phase-1
# Replication Study (Phase 1) — Card & Krueger (1994)

## Paper
Card, D., & Krueger, A. B. (1994). *Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania*. American Economic Review.

## Data Source
The replication dataset is from David Card's data sets page:
- https://davidcard.berkeley.edu/data_sets.html
- Dataset archive: https://davidcard.berkeley.edu/data_sets/njmin.zip
- Readme: https://davidcard.berkeley.edu/readme/njmin-readme.txt

Files (from the archive) include:
- `public.dat` (raw data)
- `codebook` (data documentation)
- `.sas` program to read the data

## Repository Structure
- `data/raw/` raw immutable files (never overwrite)
- `data/processed/` cleaned outputs (CSV/Parquet)
- `notebooks/` analysis notebooks (`01_Data_Cleaning.ipynb`)

## How to Run (Colab)
1. Open `notebooks/01_Data_Cleaning.ipynb`
2. Run all cells from top to bottom
3. The notebook downloads `njmin.zip`, extracts to `data/raw/`, loads `public.dat` into pandas, prints `df.head()`, and saves a processed CSV.
## Author

wanchen lang
