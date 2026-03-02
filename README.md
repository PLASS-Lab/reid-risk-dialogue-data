# Minimal Dataset — Supplementary Material

**Manuscript:** applsci-4203203 (Applied Sciences)
**Title:** Early Detection of Re-identification Risk in Multi-Turn Dialogues via Entity-Aware Evidence Accumulation
**Authors:** Yeongseop Lee, Seungun Park, Yunsik Son

---

## 1. Files

- **woz_synthetic.jsonl** — 200 records, UTF-8 JSON Lines
- **woz_stress.jsonl** — 300 records, UTF-8 JSON Lines

Each line is one dialogue record with (i) ordered turns and (ii) an oracle/reference onset label (`t_oracle_onset`).

## 2. What This Dataset Contains

- Fully synthetic dialogue text generated from domain-specific templates with fictitious PII profiles.
- **No real personal data** are included.
- Structural scaffolds (dialogue length and speaker-alternation patterns) were derived from publicly available MultiWOZ and SpokenWOZ, but **no original utterance text** from those datasets is included or redistributed.

## 3. Reproducibility

The corpora are reproducible using our generation scripts with a fixed random seed (seed = 42). Scripts and configuration can be provided by the corresponding author upon request.

## 4. External Corpora (Not Included)

ABCD and MultiDoGO, used for external evaluation (Track-R), are publicly available; repository URLs are provided in the manuscript. We do not redistribute them in this supplement.

## 5. Contact

Corresponding author: **Yunsik Son** (sonbug@dongguk.edu)
