# NFT Vision Hack — AI-generated NFT demos

This repository contains example Jupyter notebooks and image assets used to demonstrate simple generative-art and neural-style-transfer techniques for the "NFT Vision Hack" hackathon.

## Current status

- Notebooks and images that were originally in the project root have been moved into `notebooks/` and `assets/images/` respectively.
- Filenames have been normalized (lowercased, spaces -> underscores, removed many special characters). See "Notes" below.

## Repository layout

- `notebooks/` — the project's Jupyter notebooks and an index. See `notebooks/README.md` for a short summary.
- `assets/images/` — example images referenced by the notebooks.
- `requirements.txt` — Python packages used by the notebooks.
- `.gitignore` — ignored files.

## Quick start

1. Create and activate a Python virtual environment (recommended):

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

2. Open the notebooks with Jupyter Lab/Notebook from the project root:

```bash
jupyter lab
```

3. Use `notebooks/INDEX.ipynb` as the starting point.

## Notes and caveats

- Filename normalization: files were renamed to remove spaces and special characters. If a notebook references an image by an old name, update the reference in that notebook. Many references were updated, but please verify before running a notebook.
- Name collision: two images normalized to the same filename (`nen!!.png` and `nen!.png` → `nen.png`). One of the originals was overwritten during the normalization step. If you need both originals, restore them from a backup or provide the files and I can re-run normalization with unique suffixes.
- Heavy dependencies: some notebooks use TensorFlow/Keras and VGG models — these require more disk space and compute. Use a conda environment if you encounter platform-specific install issues on macOS.

## Contributing

If you want a different organization (for example, to keep filenames unchanged), tell me which naming rules you prefer and I will revert or re-run the normalization accordingly.

---

Original screenshots and notes (preserved below):

ABOUT THE PROJECT 

<img width="933" alt="Screenshot 2022-07-11 at 2 51 51 PM" src="https://user-images.githubusercontent.com/50836877/178232247-499d4da1-d74a-4b83-83cf-e13d0f0e07be.png">

<img width="929" alt="Screenshot 2022-07-11 at 2 52 15 PM" src="https://user-images.githubusercontent.com/50836877/178232372-7b58e923-a81d-4444-ba8c-01557ffe5c2d.png">

<img width="928" alt="Screenshot 2022-07-11 at 2 52 35 PM" src="https://user-images.githubusercontent.com/50836877/178232465-5229c97b-ec39-418b-8642-8d3ac3a5ff73.png">
