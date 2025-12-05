# TODO – Bibliometric Pipeline

## Phase 1 – Repository structure and boilerplate

- [ ] Create directories:
  - config/
  - config/queries/
  - data/raw/
  - data/processed/
  - data/results/
  - figs/
  - src/
  - notebooks/

- [ ] Add base files:
  - README.md
  - TODO.md
  - CHANGELOG.md
  - main.py (minimal)
  - example query YAML

## Phase 2 – Data acquisition

- [ ] Implement `query_scopus.py`
  - [ ] Load YAML config
  - [ ] Search Scopus (API)
  - [ ] Alternative: load CSV from `data/raw/`
  - [ ] Export raw DataFrame to CSV

## Phase 3 – Cleaning & Transformation

- [ ] Implement `clean_transform.py`
  - [ ] Filter by year
  - [ ] Normalize country names
  - [ ] Mark LATAM affiliation
  - [ ] Filter by language and document type

- [ ] Save processed output

## Phase 4 – Indicators

- [ ] Implement `indicators.py`
  - [ ] yearly_production
  - [ ] country_production
  - [ ] journal_production
  - [ ] keyword frequency (optional)
  - [ ] export tables to `data/results/`

## Phase 5 – Figures

- [ ] Implement `visualizations.py`
  - [ ] plot_yearly_production
  - [ ] plot_top_countries
  - [ ] plot_top_journals
  - [ ] save PNG to `figs/`

## Phase 6 – ML extensions (future)

- [ ] Build corpus of titles + abstracts + keywords
- [ ] TF-IDF vectorization
- [ ] KMeans clustering
- [ ] Embeddings + similarity search
- [ ] Optional classifier (relevant / not relevant)

---

## DONE (will be populated later)

- [ ] Initial commit
