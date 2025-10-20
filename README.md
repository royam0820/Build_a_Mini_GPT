# Build a Mini-GPT — Teaching Kit

- Notebooks in `notebooks/` (charLM, TinyGPT, fine-tune)
- Dataset in `dataset/alice.txt`
- Slides in `slides/Build_a_Mini_GPT.pptx` (dark minimalist)
- MIT License in `LICENSE`

## Quick Start (Colab)
1) GPU on. 2) Run 01_charLM. 3) Run 02_tinyGPT. 4) Optional: 03_finetune_bonus.

## Session 1 Script (6 lines)
- Token = smallest unit; next-token prediction.
- Show `alice.txt` and char vocab.
- Train Bigram (2000 steps) → loss down.
- Generate text → wow moment.
- Temperature sweep: 0.7 / 1.0 / 1.3.
- Homework: Pick your favorite sample and explain why.
