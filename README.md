# Lecture 01: Leveraging NAIRR for Research

**NAIRR Workshop Series 2026** — Oakland University & Worcester Polytechnic Institute

This session introduces NAIRR (National AI Research Resource) and Jetstream2, with hands-on exercises comparing local vs. cloud compute performance.

## Slides
- [01 Lecture](slides/01_Lecture.pdf) — What is NAIRR, Jetstream2, and why it matters
- [02 Setup](slides/02_Setup.pdf) — Connecting to Jetstream2, Jupyter crashcourse
- [03 Exercises](slides/03_Exercises.pdf) — Exercise overviews and timing framework

## Notebooks
| # | Notebook | Topic |
|---|----------|-------|
| 00 | [Jupyter Crashcourse](hands_on/00_Jupyter_Crashcourse.ipynb) | Jupyter basics, Python refresher |
| 01 | [NAIRR Models & HuggingFace](hands_on/01_NAIRR_Models_and_HuggingFace.ipynb) | NASA sentence transformer, semantic search |
| 02 | [Bulk Data Processing](hands_on/02_Bulk_Data_Processing.ipynb) | 500K-row dataset, sklearn, grid search |
| 03 | [NAIRR Open Datasets](hands_on/03_NAIRR_Open_Datasets.ipynb) | AG News, TF-IDF, text classification |

## Local Setup

```bash
git clone https://github.com/MattyTheBoi/NAIRR_Intro.git
cd NAIRR_Intro
python -m venv nairr-workshop
```

Activate:
- **Windows:** `nairr-workshop\Scripts\activate`
- **macOS/Linux:** `source nairr-workshop/bin/activate`

```bash
pip install -r requirements.txt
```

Open in VS Code, select the **nairr-workshop** kernel, and run.
