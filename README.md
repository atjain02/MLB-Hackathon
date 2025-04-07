# MLB-Hackathon

- **MLB_Hackathon_Final_Code.ipynb**  
  The main notebook containing all steps for data preprocessing, feature extraction, model training, and prediction.

- **sequence.fasta**  
  FASTA file which contains the wild-type protein sequence

- **train.csv**  
  Training dataset with columns for `mutant` and `DMS_score`

- **test.csv**  
  Test dataset with columns for `mutant` (no DMS scores)

## How to use

1. **Clone the Repo**  

2. **Install Depdencies**
   Install Python3.7+ and the required libraries
   You should be able to run 'pip install torch esm scikit-learn xgboost pandas numpy'

3. **Run Code**
   Step 2 can actually be skipped if the recommended way of running this code in Google Collab is used. Otherwise you can run the code using any preferred python notebook runner such as Jupyter. Run 'MLB_Hackathon_Final_Code.ipynb'. 
