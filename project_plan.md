# Project Plan

**Updated by:** _Member 4 name_ (Final)

**Project:** Parkinson's Detection from Hand-drawn Spiral & Wave

## Goal
Build a machine learning system that looks at a hand-drawn spiral or wave and predicts whether it is `healthy` or `parkinson`, with a simple web app to try it.

## Plan by update

| Update | What was delivered | Main files | Status |
|--------|--------------------|------------|--------|
| Update 1 | Project setup, image preprocessing, feature extraction, dataset description | `README.md`, `.gitignore`, `requirements.txt`, `common.py`, `data_description.md`, `project_plan.md` | Done |
| Update 2 | Trained and compared 4 models and saved results | `train.py`, `data.zip`, `outputs/` | Done |
| Update 3 | Streamlit web app for prediction and results | `app.py` | Done |
| Final | Final README with results, limitations and conclusion | `README.md` | Done |

## Risks / things to check
- The dataset is small, so results must be read carefully (subject-wise accuracy is the stricter and more realistic number).
- This is an educational demo, not a medical diagnosis tool.
