# ReID Risk Dialogue Data

🪪 About | 🏷️ Description | 🗃️ Usage

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

[PLASS Lab, Dongguk University](https://plass.dongguk.edu/)
