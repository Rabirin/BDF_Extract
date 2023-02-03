## __Work Information__

#### <ins>Work Environment, Inputs/Outputs</ins>

* Programming Language/Kernel:              Python 3.9.13
* Integrated development environment (IDE): Microsoft VSCode with Python and Jupyter extensions
* Code Development File Format:             Interactive Python Notebook (*.ipynb)
* Input file format:                        BDF Files
* Output File Format:                       CSV Files

#### <ins>Work Objective</ins>

Output Objective: To generate csv files in tabular format for various data set. <br>
Nastran has a wide variety of data set (identified via Nastran Card inputs) available. Hence, the tool is developed based on a few most used data set. More data set extraction feature will be added subsequently. Currently, the data set that can be extracted are as followed.
* Isotropic Material Property (MAT1)
* Rod Element Property and Connection (CONROD)
* Rod Property (PROD)
* Simple Beam Property (PBAR)
* Beam Property (PBEAM)
* __Next In Line: PBUSH__

#### <ins>Files/Folders Dictionary</ins>

* File Name: "Sample_BDF.bdf" <br>
Sample bdf file used for extraction.

* File Name: "BDF_Extract.ipynb" <br>
Interactive Python notebook containing the codes. <br>
The mark down cells copntains screenshot images from Nastran 2022 Quick Reference Guide (qrg).

* File Name: "*.csv" <br>
Output csv files containing extracted data set separated by commas and can be parsed in tabular format. <br>
Note that file "Prod_Prop.csv" is empty because there is no PROD entry in the sample bdf file.

* Folder Name: "*image" <br>
Contains image files used in ipynb markdown cells.
