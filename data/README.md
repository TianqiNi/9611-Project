# Data

The images are not in this repo. Download them from
[Brain Tumor MRI on Kaggle](https://www.kaggle.com/datasets/deeppythonist/brain-tumor-mri-dataset)
and place the extracted folders like this:

```text
data/train/glioma/      data/test/glioma/
data/train/meningioma/  data/test/meningioma/
data/train/notumor/     data/test/notumor/
data/train/pituitary/   data/test/pituitary/
```

Our copy has 7,153 JPGs: 5,723 in `train/` and 1,430 in `test/`.

`splits.csv` is the frozen split. It lists each image kept after duplicate removal, with its label and split. Don't delete it: the notebook reloads it so every run and every later model uses the same images.
