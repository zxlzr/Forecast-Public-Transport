The sampletrain_*.txt and sampletest.txt are sample files of train and test separated by ",". 



In the passengers's boarding choice folder,  the files have 213 columns. sampletrain_change.txt and sampletrain_changeless.txt are sample train data of unfixed bus line passengers  and fixed bus line passengers. The 1st and 2nd are Card_id and Line_name. The 3rd is Label. After that are the features.

 The 4-33th columns are features of passenger. 
 The 34-63th columns are features of bus. 
 The 64-93th columns are features of time. 
 The 94-123th columns are features of weather. 
 The 124-153th columns are features of issued. 
 The 154-183th columns are features of card. 
 The 184-213th columns are features of semantic user behaviour. 

In the passenger flow folder, the files have 245  columns. sampletrain_freq.txt and sampletrain_random.txt are sample train data of frequent passengers and random passengers. The 1st,2nd,3rd are Line_name, Date, Hour. The 4th is the total passenger number(passenger flow). After that are the features.

 The 5-14th columns are one-hot encoding of  weather conditions.  
 The 15-245th columns are one-hot encoding of  semantic user behaviours. 



