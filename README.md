# CSB
Taryn Serman and Jessica Spring Final Project

The purpose of this code is to streamline functional analysis of protein:protein interaction partners following Mass Spectrometry. As most Mass Spectrometry facilities return data in an excel file, our code uses an excel file as an input. The code writes the excel file into a csv file and filters out hits, identified by Gene Symbol, for those that have greater than one unique peptide. Typically, hits that return greater than one unique peptide are considered "significant" when analyzing Mass Spectrometry results. The code also filters out hits that do not fall within the appropriate molecular weight range that corresponds to the analyzed protein. 

Once the hits are filtered, this code then searches each significant hit on UniProt based on a specified keyword entered. For example, our keyword is "MAPK" in our posted code. If a gene is found by the specified keyword, the code writes a new csv file, named after the keyword, containing all genes identified by that keyword. 
