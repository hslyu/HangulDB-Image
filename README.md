# HAN
Korean handwriting dataset parsed from the [HangulDB](https://github.com/callee2006/HangulDB).

# Samples

Each image has different width and height. 
For the consistency with the original, I intentionally preserve the property.
## b0a1
![b0a1/1.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b0a1/1.jpg)
![b0a1/2.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b0a1/2.jpg)
![b0a1/3.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b0a1/3.jpg)
![b0a1/4.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b0a1/4.jpg)
![b0a1/5.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b0a1/5.jpg)
![b0a1/6.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b0a1/6.jpg)
![b0a1/7.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b0a1/7.jpg)
## bad0
![bad0/1.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/bad0/1.jpg)
![bad0/2.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/bad0/2.jpg)
![bad0/3.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/bad0/3.jpg)
![bad0/4.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/bad0/4.jpg)
![bad0/5.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/bad0/5.jpg)
![bad0/6.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/bad0/6.jpg)
![bad0/7.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/bad0/7.jpg)
## ba88
![b8aa/1.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b8aa/1.jpg)
![b8aa/2.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b8aa/2.jpg)
![b8aa/3.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b8aa/3.jpg)
![b8aa/4.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b8aa/4.jpg)
![b8aa/5.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b8aa/5.jpg)
![b8aa/6.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b8aa/6.jpg)
![b8aa/7.jpg](https://github.com/hslyu/HAN/blob/main/HanDB_test/b8aa/7.jpg)

# Datasets
This repo contains PE92, SERI95, and HanDB.
* PE92 contains __2350 classes__, each with __100 samples__.
* SERI95 contains __520 classes__, each with __1000 samples__.
* HANDB merges SERI95 and PE92. That is, __520 classes__ have __1100 samples__ and the others (__1820 classes__) have __100 samples__.

__Architecture__

Three datasets have the same structure:

`<dataset_name>/<label>/<sample_index>.jpg`

__warning__

PE92 contains some mislabeled samples at the last few samples for each class.

# Verification
`parser.ipynb` parses a hgu1 file to several jpg files.
You can test whether it correctly parse the original dataset using `parser.ipynb`.
