There are two datasets available along with the PNAS paper: 
Hernandez et al. 2020 A Demographic and Evolutionary Analysis of Maternal Effect Senescence

The file called LifeTables.zip is an archive that contains 4 comma-separated values (CSV) files. These are named with the convention F1_M#_AL.csv. 
  F1 refers to the generation of individuals included in the file.
  M3, M5, M7, and M9 indicate that the individuals were from maternal age 3, 5, 7, or 9 days.
  AL refers to the ad libitum feeding treatment used for the experiment. 
In these LifeTable files, each row contains the data for an individual. Each day that the individual was still alive, a number was entered to indicate the number of offspring produced on that day. A zero value indicates that the individual was alive, but had no offspring. 


The file called U_and_F_matrices is an archive that contains 34 CSV files. 
F1 through F16 are each 16-by-16 matrices that form the fertility blocks in Atilde, the laboratory-based population model. 
The file Ftilde.csv contains the full Ftilde, which is a 256-by-256 matrix.
U1 through U16 are each 16-by-16 matrices that form the survival blocks in Atilde, the laboratory-based population model. 
The file Utilde.csv contains the full Utilde, which is a 256-by-256 matrix. 
Atilde = Utilde + Ftilde
