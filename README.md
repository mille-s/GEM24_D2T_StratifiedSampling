# GEM24_D2T_utils.ipynb

The notebook currently contains 10 parts.

## 1. D2T data selection (stratified sampling)

This is the code used to select the input/output pairs for the GEM 2024 shared task. It was adapted from the WebNLG'23 code. Thanks to Liam Cripwell, Rudali Huidrom and Michela Lorandi for making their versions of the code available.

1- Run the first 2 cells (*Prepare repo*)

2- Set Parameters: (i) subtask, (ii) dataset, (iii) seed.

3- Drag and drop an input file in the xml format in the *testdata* folder.

4- Select the *Sampling parameters* from the dropdown menu: (i) stratify_categorie, (ii) number_samples, (iii) exclude_size.

5- Run 7 cells of *Create csv file with sampling info* block to generate a CSV file with the sampling info and.

## 2. HTML tables

This is the code used to generate tables corresponding to the selected inputs for the human evaluation interface. If run immediately after the *D2T data selection* block, the tables for the corresponding dataset will be created.

It contains two cells to download the CSV and HTML files.

## 3. Create individual files for sampled system outputs

This is the code used to select the sampled system outputs from the original submission files. It requires a CSV file as created in *D2T data selection* above, and one or more files whose texts are aligned with the inputs used to generate the CSV (one text per line, each line corresponds to one input).

It contains a cell to download the text files.


## 4.


## 5.


## 6.


## 7.


## 8.


## 9.


## 10.


