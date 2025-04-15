# Toxic-language-detection

The project goal is to detect toxic language. The dataset used in this project is English language. The dataset contains a lot of garbage values, there are a lot of rows that doesn't contain any texts. The first step was to clean the dataset and then use proper pre-processing steps. All the characters were converted to lowercase , extra white spaces were removed. Then stemming was applied.

For this project both traditional machine learning models (DT,RF,SVM, KNN), deep learning models (RNN,CNN, LSTM, Feed Forward Neural Network) and pre-trained transformer models (GPT,BERT) were deplyoed. 

The tradtional models performed bettter. Because the vectorization technique for English language has improved a lot. So, traditional machine learning models are good enough for small tasks like this 
