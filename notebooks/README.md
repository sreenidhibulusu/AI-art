# Notebooks

This folder contains the project's Jupyter notebooks.

## Notebook summary

- `generative_art.ipynb` — assorted generative-art examples (turtle, PIL, matplotlib, pygame, cairo). Good for small demos and visuals.
- `generative_1.ipynb` — creates images from numpy arrays and saves outputs (uses numpy, Pillow and matplotlib).
- `nft_ai_art_.ipynb` — neural-style-transfer example using TensorFlow / Keras and VGG16 (content/style blending). May require substantial compute and exact library versions.
- `nft_sample_1.ipynb` — another style-transfer/sample notebook (similar dependencies to `nft_ai_art_.ipynb`).
- `INDEX.ipynb` — small index notebook to list and open notebooks.

## How to run

1. From project root, ensure dependencies are installed (see `requirements.txt`).
2. Start Jupyter and open the desired notebook.

## Notes

- Filenames were normalized to remove spaces and special characters. If you prefer different names, rename the files and update references inside notebooks.
- Some notebooks reference images by filename (for example `sky2.jpeg`, `sky3.png`). Ensure `assets/images/` contains those image files or update the referenced names.

