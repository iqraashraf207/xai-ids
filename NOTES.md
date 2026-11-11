# Project notes

- Forked from MohammadThabetHassan/xai-ids (credit the original authors in the final README).
- Env: Python 3.11.9, venv, requirements installed, ART 1.20.1 working.
- 2026-11-12 smoke test (run_pipeline.py --sample-size 5000 --skip-explain) used SYNTHETIC data. Accuracy 0.69 (LR), 0.76 (RF), 0.74 (XGB). Not a real baseline.
- Repo already has an adversarial module (src/evaluation/adversarial.py, --adversarial flag). Read it before adding anything.
- TODO: get real CIC-IDS-2017 data, record real baseline, then design the experiment.
