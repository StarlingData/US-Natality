# US-Natality

In the form on the CDC's website, birth data are stored in .txt files where rows of data are interrupted by linebreaks, and particular values are accessed by their position in line. Here I have read in the 2021 guide and the dataset, and used this info to convert the data into a more conventional csv format.

I have saved a copy of "UserGuide2021.pdf" from the original publication in this repo. You can use documentation on p. 9-38 to read field, description, values and definitions — these have been preserved in the reformatted dataset. Disregard the 'Position' and 'Length" columns, which are no longer relevant in the csv form.

Note that to preserve leading zeroes, you should read in the data as strings. 

Data Source: https://www.cdc.gov/nchs/data_access/vitalstatsonline.htm

The conversion process is documented in "process" 
