# Big Data Analysis Pipeline

End-to-end data processing and analysis pipeline built in Python, designed to handle large-scale datasets with a modular and reproducible workflow.

Developed as part of the *Big Data* course at Universidade do Minho.

---

## 🛠️ Stack

| Layer | Technology |
|---|---|
| Language | Python |
| Automation | Shell scripts |
| Reporting | LaTeX |
| Data Processing | PySpark / Pandas |

---

## 📁 Project Structure

```
├── src/         # Core processing logic and analysis modules
├── scripts/     # Shell scripts for pipeline automation and execution
├── outputs/     # Generated results, charts, and processed data
└── README.md
```

---

## 🔄 Pipeline Overview

```
Raw Data → src/ (processing & analysis) → scripts/ (automation) → outputs/ (results)
```

1. **Ingestion** — raw datasets are loaded and validated
2. **Processing** — data is cleaned, transformed, and aggregated
3. **Analysis** — statistical analysis and pattern extraction
4. **Output** — results exported to structured formats and visualisations

---

## 🚀 Running the Pipeline

```bash
# Install dependencies
pip install -r requirements.txt

# Run the full pipeline
bash scripts/run_pipeline.sh

# Or run individual analysis steps
python src/main.py
```

---

## 📊 Outputs

Processed results and generated visualisations are available in the `outputs/` directory after running the pipeline.

---

## 👥 Team

University group project — Universidade do Minho, 2024
