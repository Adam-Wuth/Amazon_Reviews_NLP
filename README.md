# Amazon Reviews Sentiment Classification – NLP Final Project
This is the final Project for CSCI 3832 for Adam Wuth, Benjamin Kohav, Noah Vilas, Aiden Devine, Evan Zachary

## Overview
This project uses different models to predict star ratings (1 to 5) from Amazon product reviews written in 2023. We compare different model architectures (e.g., N-gram models vs. DistilBERT) to evaluate how well they classify sentiment in real-world amazon review data.



## Final Results(all tested on the same dataset created in the make_dataset notebook)
1. RNN model Accuracy:20.1%
2.  Bigram model Accuracy:22%
3.  Trigram model Accuracy:64%, but was trained on a 5 star skewed dataset and not retrained
4. GRU Accuracy:46.5%
5. DilstilBERT Accuracy:49.50(trained on "reviews_larger" dataset specified in DisilBERT.ipynb)
Confusion matrix for disitilbert:<br/>
<img width="692" alt="Screenshot 2025-05-06 at 9 52 25 PM" src="https://github.com/user-attachments/assets/ca437c72-f443-467e-a021-e88f5945a97a" />


## Steps to set up
1. Use python 3.8+, and pip installs for "pip install torch numpy nltk datasets transformers scikit-learn matplotlib tqdm" so you have everything you need
2. Ensure you have the file 'glove.6B.50d.txt' in your directory
2. For all code, make sure that you use the make_dataset.ipynb so you have a dataset to work with.
3. From there on, each notebook holds a different model. In order to recreate our results, you only need to follow the instructions and run the code in each notebook.<br/>

## Different Parts of the code
In this repository, you will find 6 notebooks:
1. Make_Dataset.ipynb(no model, use first to get data)
2. DistillBERT.ipynb(contains the DistilBERT code)
3. Amazon_Reviews-BIGRAM(contains the Bigram model code)
4. Amazon_Reviews-BiLSTM.ipynb(contains RNN model code)
5. Amazon_Reviews-GRU.ipynb(contains GRU model code)
6. placeholder
<br/>

## Dataset Info
Dataset:McAuley-Lab/Amazon-Reviews-2023<br/>
Years Filtered: Only 2023 reviews<br/>
Source Domains: 34 Amazon product categories<br/>
Preprocessing:<br/>
Filter by timestamp, review type and category<br/>
Map rating to label classes 0–4<br/>
**To recreate the project, use the make dataset notebook**<br/>

## Link to Github and GoogleDrive
1. Link to github used in development: https://github.com/Adam-Wuth/NLP-project.git<br/>
2. Link to final github: https://github.com/Adam-Wuth/Amazon_Reviews_NLP.git<br/>
3. Link to Google Drive containing additional resources:https://drive.google.com/drive/folders/1guIdize8FzOsx_XGgixzWrsdJZ_BJPZs?usp=sharing<br/>
## Future Steps
An obvious first future step would be to get more computing power/time so we can really see the upper bound of the distillbert model.<br/>

A second future step would be cleaning the dataset better to try and have more distinct differences between 2-3-4<br/>

A third future step would be looking into more transformer models and training them for optimal performance as well<br/>
## Authorship, attribution, and acknowledgements
**Dataset setup and filtering:**<br/>
Adam Wuth, *Lead*<br/>
<br/>
**RNN Code:**<br/>
Aiden Devine, *Lead*<br/>
<br/>
**Bigram Model Code:**<br/>
Benjamin Kohav, *Lead*<br/>
<br/>
**Trigram Model Code:**<br/>
Noah Vilas, *Lead*<br/>
<br/>
**GRU Code:**<br/>
Evan Zachary, *Lead*<br/>
<br/>
**DistillBERT Code:**<br/>
Adam Wuth, *Lead*<br/>
<br/>
