# WikiSQL-Dataset-Configuration

The dataset is generated from the WikiSQL database by applying some set of production rules for the cases of each of cell, row or column or table summary.
The process is split into two parts, viz the input variable generation and the output variable generation.

Cell data is encoded as col:data;
Row Representation: col:data;col:data;
Column data is encoded as col:data;data;….more data;
Table data is encoded as col:data;; where ; marks the end of a cell data and the other ; marks the end of a row 
