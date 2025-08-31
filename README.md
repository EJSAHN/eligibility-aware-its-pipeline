# Eligibility-aware ITS in-silico pipeline

This repository reproduces the eligibility-aware ITS screening, Δ-coverage,
logo/entropy, rarefaction, and sensitivity analyses described in the manuscript.

## Quick start
```bash
pip install -r requirements.txt
python its_pipeline_shareable.py

name,seq,dir
ITS1,TCCGTAGGTGAACCTGCGG,forward
ITS2,GCTGCGTTCTTCATCGATGC,reverse
ITS1F,CTTGGTCATTTAGAGGAAGTAA,forward
ITS5,GGAAGTAAAAGTCGTAACAAGG,forward
ITS4,TCCTCCGCTTATTGATATGC,reverse
fITS7,GTGARTCATCGAATCTTTG,forward
ITS86F,GTGAATCATCGAATCTTTGAA,forward
ITS3_KYO2,GATGAAGAACGYAGYRAA,forward
ITS2_KYO2,TTYRCTRCGTTCTTCATC,reverse
ITS6,GAAGGTGAAGTCGTAACAAGG,forward
