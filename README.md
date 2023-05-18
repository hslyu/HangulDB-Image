# HAN
Korean handwriting dataset parsed from the [HangulDB](https://github.com/callee2006/HangulDB).

# Datasets
This repo contains PE92, SERI95, and HanDB.
* PE92 contains 2350 classes, each with 100 samples
* SERI95 contains 520 classes, each with 1000 samples
* HANDB merges SERI95 and PE92.

__Architecture__
Three datasets have the same structure:

`<dataset_name>/<label>/<sample_index>.jpg`

__warning__
PE92 contains some mislabeled samples at the last few samples for each class.

# Verification
`parser.ipynb` parses a hgu1 file to several jpg files.
You can test whether it correctly parse the original dataset using `parser.ipynb`.
