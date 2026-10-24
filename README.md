# POSsteg
Code and data for POSsteg, a linguistic steganography method that hides messages in LLM-generated text by controlling the part-of-speech (POS) tags of generated words.
## Repository structure

- `notebooks/POSsteg.ipynb` – the method (encoding and decoding), generation of the stego/cover corpus and the message-length experiment
- `notebooks/analysis/` – analyses reported in the paper (text quality, steganalysis, capacity, message length)
- `results/generated_corpus.jsonl` – corpus of 272 stego–cover text pairs used in the paper
- `results/length_experiment_results.jsonl` – results of the message-length experiment
