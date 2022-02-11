# MIP_Estatal
Input/Output sector analysis at the state level in Mexico. Part of the "Strategic actions to promote a sustainable recovery Post-COVID" project within the ExpertODS initiative of the Sustainable Development Solutions Network (SDSN - Mexico).

## Description
Jupyter notebook to perform basic Input/Output analyses at the state-level in Mexico. The notebook can be accessed through Google Colab.

## Functionality
The script reads the file MIP_Estatales_d_pb_ixi_2008.xlsx in the user home directory of the Colab session (or current directory at local machine), iterates over data within each sheet (one per state) and perfoms basic Leontief input/ouput analyses to classify economic sectors per their potential to induce/amplify economic growth. The output is writen to xlsx files (one per state), including spreadsheets with (1) the I-O matrix, (2) the technical coefficients matrix, (3) Leontief's matrix and (4) a table of results classifying each sector.
