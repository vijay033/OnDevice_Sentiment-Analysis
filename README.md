# Project is intended to train and test sentiments on mobile phone.
# First phase is training the data on device (mobile) and later reading the trained model file.
# MODEL_PATH ( internal storage )
 
   # private static String MODEL_PATH = Environment.getExternalStorageDirectory().toString()+"/SENTIMENT_DATA/";
   # private static String ModelFile = "Sentiment.text";  /*Trained model*/
 
# Training data path  :
  
   # private static String TRAINING_DATA_PATH = Environment.getExternalStorageDirectory().toString()+"/SENTIMENT_DATA/training/";
   # training/POS/pos.txt
   # training/NEG/neg.txt
  
# Testing data path  : checkUnlabeledData() API helps in cross validation from below path  
 
   # private static String TESTING_DATA_PATH = Environment.getExternalStorageDirectory().toString()+"/SENTIMENT_DATA/testing/";
   # testing/POS/pos.txt
   # testing/NEG/neg.txt
  
# Testing API : checkUnlabeledData(String rawText)
# Use high end device - Samsung Galaxy S7 and above