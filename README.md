# ReID Risk Dialogue Data

🪪 About | 🏷️ Description | 🗃️ Usage | 🔗 Citation

This repository contains the dataset for the paper: [Early Detection of Re-identification Risk in Multi-Turn Dialogues via Entity-Aware Evidence Accumulation](https://doi.org/10.3390/app) (Applied Sciences, 2026)

## About

This dataset provides synthetic multi-turn dialogue records for evaluating re-identification risk detection in dialogue systems. Each record contains ordered speaker turns with an oracle onset label indicating the turn at which accumulated entity mentions first enable speaker re-identification.

## Dataset Description

### Files

| File | Records | Format |
|------|---------|--------|
| `woz_synthetic.jsonl` | 200 | UTF-8 JSON Lines |
| `woz_stress.jsonl` | 300 | UTF-8 JSON Lines |

### Record Structure

Each line is a JSON object representing one dialogue with:
- Ordered speaker turns
- Oracle onset label (`t_oracle_onset`)

### Data Characteristics

- Fully synthetic dialogue text generated from domain-specific templates with fictitious PII profiles.
- **No real personal data** are included.
- Structural scaffolds (dialogue length and speaker-alternation patterns) were derived from publicly available MultiWOZ and SpokenWOZ, but **no original utterance text** is included or redistributed.

## Usage

This dataset can be used for the following purposes:

1. Evaluating dialogue-level re-identification risk detection models.
2. Benchmarking entity-aware evidence accumulation methods.
3. Stress-testing onset detection under adversarial mutation conditions.

## Citation

If you use this dataset for your research, please cite the following paper.

> Title: Early Detection of Re-identification Risk in Multi-Turn Dialogues via Entity-Aware Evidence Accumulation
> Journal: Applied Sciences (MDPI)

```bibtex
@article{lee2026reid,
  title   = {Early Detection of Re-identification Risk in Multi-Turn Dialogues
             via Entity-Aware Evidence Accumulation},
  journal = {Applied Sciences},
  author  = {Lee, Yeongseop and Park, Seungun and Son, Yunsik},
  year    = {2026}
}
```

[PLASS Lab, Dongguk University](https://plass.dongguk.edu/)
