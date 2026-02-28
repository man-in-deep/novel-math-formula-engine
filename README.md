# Novel Math Formula Engine

This project is a Flask-based system that continuously generates **novel candidate mathematical formulas**
across advanced domains such as functional analysis, operator theory, quantum mathematics,
spectral graph theory, and cryptographic mathematics.

## Core Features

- Sequential topic rotation (every 15 minutes)
- AI-generated candidate formulas with full derivation and explanation
- SQLite-based local storage (no external DB required)
- Continuous background generation
- Web dashboard to view created formulas
- Internal novelty guarantee (no duplicate formulas)

## Models Used

- DeepSeek-Math-7B (quantized, CPU)
- Qwen2-1.5B-Instruct (quantized, CPU)

Models are stored locally and are NOT tracked by git.

## Database

- Uses SQLite (built into Python)
- Database file is auto-created at runtime
- No manual database setup required

## Folder Notes

- `models/` contains quantized AI models (ignored by git)
- `db/` contains the auto-generated SQLite database
- `logs/` contains runtime logs

## Disclaimer

All generated formulas are **candidate research constructs**.
They are mathematically reasoned under stated assumptions but are not guaranteed to be
globally novel or formally proven without human verification.

---

© 2026 Novel Math Engine
