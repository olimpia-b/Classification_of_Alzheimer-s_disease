# Classification_of_Alzheimer-s_disease
This project has been published as a book chapter in Soft Computing Techniques and applications: Proceeding of the International Conference on Computing and Communication, IC3 2020. You can read the paper 
[here](https://books.google.co.in/booksid=470LEAAAQBAJ&pg=PA295&lpg=PA295&dq=olimpia+borgohain&source=bl&ots=04adUTrIRv&sig=ACfU3U21ZPn-ChXfFCR9mjhmCgzq2Vr1kQ&hl=en&sa=X&ved=2ahUKEwiTr5GA3Kf4AhVYxDgGHf7ZD5QQ6AF6BAgPEAM#v=onepage&q&f=false).
We have used the OASIS longitudinal dataset from kaggle and modified it. I have uploaded the modified dataset here.

We have used KNN Algorithm  and its variants for classifying Alzheimer's disease, namely: NN, KNN and Weighted KNN.
We have used three distance metrics for comparison, namely
 1. Euclidean distance,

![image](https://user-images.githubusercontent.com/53910343/173231756-7ef5ea00-6c0e-4649-954a-2c9ee4144407.png)

 2. Manhattan distance,
 
 ![image](https://user-images.githubusercontent.com/53910343/173231842-002ad457-6a40-427e-a94a-1e1b2ecc836a.png)
 
 3. Minkowski distance

  ![image](https://user-images.githubusercontent.com/53910343/173231899-844cd080-61f5-4f01-8a23-57d2ffdfe456.png)
  
  As for the features, we have used MMSE, eTIV, nWBV, SES and EDUC. 
  + The Mini Mental State Examination (MMSE) is a 30-point value. It is used to search for dementia and to measure cognitive impairment. A value >= 24 points out normal cognition. Value in between 19 to 23 accounts for mild, 10 to 18 for moderate and =<9 indicates severe. However, MMSE alone is not a strong feature.
  + eTIV(Estimated total intracranial volume)or ICV value is used to assess AD, Mild cognitive impairment. This feature estimates the age-related change in the structure of brain. It points to the approximate volume of the cranial cavity. 
  + EDUC stands for years of education.
  +  SES (socio economic status) values ranges from 1 to 5. 1 being the highest status and 5 being the lowest status. 
  +  nWBV stands for Normalized whole brain volume area.
 
 The classification is done based on CDR (clinical dementia rating) value. CDR is a 5-point value which depicts functionalities of AD and other types of 
dementia. A patient’s level of impairment/dementia is designated by this score.
+ 0 stands for Normal,
+  0.5 for Very Mild, 
+  1 for Mild ,
+  2 for Moderate and
+   3 for Severe

