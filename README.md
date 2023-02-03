## __BDF Extract__

#### <ins>Introduction</ins>

In the field of finite element model (FEM), various information from just the model itself are extracted for further analysis purposes under some cases. One example is obtaining element dimensions by measuring the distances between the nodes associated to the element. Another example is where a person wishes to obtain a list of materials or element properties used from the model. It is possible to do achieve these in Patran (A pre/post processor of FEM), but some requires a few clicks to just show one set of data and Patran may not always return all required data in nice tabular format.

#### <ins>BDF File</ins>

The model inside Patran can be exported into a bdf file which can be subsequently submitted to Nastran (FEM solver) for solving. The bdf file itself is actually nothing but text in certain format readable and understood by Nastran. The bdf file can be opened and viewed by any text editor and modified as necessary. The bdf file contains all information about the model in text only.

Fortunately, with the model represented in text only makes things easier, where a custom built parser would be able to identify and extract the relevant data from the bdf file. The extracted data can then be arranged in a nice tabular format and outputted to a separate file.

#### <ins>Work Goal</ins>

This project/work aims to create tools/codes in Python to automate extraction of data from the bdf file. For the time being, set of codes are placed in each cell which perform a specific data extraction so users can run whichever cell necessary to extract the desired data. When converting the codes into Python executable in the future, each set of codes may be converted into separate executable files.

#### <ins>Further Readings</ins>

Refer to file "Work_Information.md" for more details. <br>
Refer to the various csv files for the ouput files.
