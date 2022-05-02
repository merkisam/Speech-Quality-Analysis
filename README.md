# Speech-Quality-Analysis
#This file was built to analyse the output result files of https://github.com/merkisam/test-web-speech-api-de

#The following steps are applyed:
#1. Import of required libaries
#2. Creation of the comparsion List called (comparison)
#3. Loading of file list in dataPath (data)
#4. Creating of the resultArray for inserting the anaylsis result
#5. Iteration over each file
#5.1 Extraction of paramter: gender/age/isProvidedDictionary
#5.2 Enumeration over words in line
#5.2.1 Calculation of diffrent string distances and increasing count when over a certain treshold
#6. Insertion of result into Panda Dataframe and conversion to numeric values
#7. Separation of dataset by gender/age and isProvidedDictionary
#8. Combination of separated data sets
#9. Visualization of result
