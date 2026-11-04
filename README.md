# ECE 9611 Project - Brain Tumour MRI (Group 3)

Tianqi Ni, Yuchen Zhao

We classify an MRI image as glioma, meningioma, pituitary tumour or no tumour. All of the work is in `ECE9611_Project_Group03.ipynb`.

**Data:** dataset #9, [Brain Tumor MRI on Kaggle](https://www.kaggle.com/datasets/deeppythonist/brain-tumor-mri-dataset). See `data/README.md` for where to put the files.

## Run

Use Python 3.12 and run from the repo folder:

```bash
pip install -r requirements.txt
```

```bash
jupyter nbconvert --to notebook --execute --inplace ECE9611_Project_Group03.ipynb
```

It takes about 20 seconds on an 8-core Mac with no GPU.

## Phase 1 status

- **Done:** data audit, removal of 556 duplicate copies, frozen split (3,903 / 1,301 / 1,393 in `data/splits.csv`), exploratory figures and preprocessing. The test set is not evaluated.
- **Next:** cross-validation, baselines, comparison table and conclusion.

**Commit:** add hash before submitting.

Used Claude Code for help with the code and write-up.
