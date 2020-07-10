# Feature Extraction: Code to extract features using k-mer descriptor

The frequency of neighboring bases k (k-mer) may contain statistical information to distinguish biological sequences. The k-mer is denoted in this work by **fkmer = ci/sk**, where **ci** denotes number of patterns and **sk (L - K + 1)** the total of the segments **k** along of the sequence with size **L**. This code generates a data set (CSV) with the k-mers counting.


## Authors

* Robson Parmezan Bonidia

* **Correspondence:** robservidor@gmail.com


## List of files

 - **README:** Documentation;

 - **findKmers.py** Main File - Python.

 - **testOne.fasta** Example.

## Dependencies

- Python(>=3.5)
- NumPy 
- Itertools
- Biopython


## Installing our tool

```sh
$ git clone https://github.com/Bonidia/kmerSchemaPython.git kmerSchema
```

## Usange and Examples


```sh
Access folder: $ cd kmerSchema
 
To run the tool (Example): $ python3.5 -i input -o output -l label -k 2


Where:

-i = Input - Fasta format file, e.g., test.fasta

-o = output - CSV format file, e.g., test.csv

-l = Label - Dataset Label, e.g., lncRNA, mRNA, sncRNA

-k = kmer - Range of k-mer, E.g., 1-mer (1) or 2-mer (1, 2)
```

## About

If you use this code in a scientific publication, we would appreciate citations to the following paper:

Bonidia, R. P., de Leon Ferreira, A. C. P., Paschoal, A. R., & Sanches, D. S. (2019, October). Selecting the Most Relevant Features for the Identification of Long Non-Coding RNAs in Plants. In 2019 8th Brazilian Conference on Intelligent Systems (BRACIS) (pp. 539-544). IEEE.

## References

A. Li, J. Zhang, and Z. Zhou. Plek: a tool for predicting long non-coding rnas and messenger rnas based on an improved k-mer scheme. BMC bioinformatics, 15(1):311, 2014.
