# SoNaR_corpus_formatted
SoNaR1 corpus formatted for thesis use

To recreate a run:  
step 1: run data_format.py > mid2.out  
step 2: run SoNaR_neatlyv2.py > SoNaR1_totalv2.out  
step 3: run divide.py  

(easier to just take the copy of the dataset you need)

This dataset contains:  
1. all occurences of PER and MISC label as main cat  
2. all occurences of the other categories that are labeled with a subcategory  

(Please don't push to this directory)  
 training data = training.txt  
 test data = test.txt  
 full version = SoNaR1_totalv2.txt
