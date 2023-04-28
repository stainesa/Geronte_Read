# Geronte_Read
## Read SAS style text files from eCRF

For work on the evaluation of an RCT (not the analysis) we have received data in an exotic format 

Each data table is a directory, with consists of six text files, five representing the data
structure, labels of values and variables, types of variables and so on, and one representing the
data. These are not and will not be available, but enough data on the strucutures, and short
excerpts are given here to make some sense of the files.
The data file, part of which is included, is 100% fake data.

## The goal is :-
1) Read the structure files one at a time into R (done, but to be checked further)
2) Combine these in some intelligible way (done, but to be checked further)
3) Read the data file using the combined structure file (done, , but to be checked further)
4) Label the variables in the file, and the values of those variables (partly done)
