# OncoSexome

### Fisher’s exact test to Identify Sex-biased Adverse Responses (AR)

We adopted Fisher et al.'s [(PMID: 38167211)](https://pubmed.ncbi.nlm.nih.gov/38167211/) methods and performed Fisher’s exact test on the FDA Adverse Event Reporting System (FAERS) database to identify sex-biased ARs for 207 FDA approved anti-cancer drugs with available data.
The data inclusion criteria were: 
- 30 cases of the drug-adverse event pair in at least one sex.
- 50 cases of drug-adverse event pair across both sexes.
- 1000 cases for a drug across all four groups.
- More than five adverse events in both sexes.

Please find ``SDR_AR.rmd`` for detailed R codes.
