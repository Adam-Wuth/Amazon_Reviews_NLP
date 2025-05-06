# 📦 Amazon Reviews Sentiment Classification – NLP Final Project
This is the final Project for CSCI 3832 for Adam Wuth, Benjamin Kohav, Noah Vilas, Aiden Devine, Evan Zachary

## Overview
This project uses different models to predict star ratings (1 to 5) from Amazon product reviews written in 2023. We compare different model architectures (e.g., N-gram models vs. DistilBERT) to evaluate how well they classify sentiment in real-world amazon review data.



## Final Results(all tested on the same dataset created in the make_dataset notebook)
1. RNN model Accuracy:20.1%
2.  Bigram model Accuracy:22%
3.  Trigram model Accuracy:placeholder
4. GRU Accuracy:46.5%
5. DilstillBERT Accuracy:
## Different Parts of the code
In this repository, you will find 6 notebooks:
1. Make_Dataset.ipynb
2. DistillBERT.ipynb
3. placeholder
4. placeholder
5. placeholder
6. placeholder
<br/>
Each notebook holds a different model. In order to recreate our results, you only need to follow the instructions and run the code in each notebook.<br/>
<br/>
## Test
Dataset:McAuley-Lab/Amazon-Reviews-2023<br/>
Years Filtered: Only 2023 reviews<br/>
Source Domains: 34 Amazon product categories<br/>
Preprocessing:<br/>
Filter by timestamp, review type and category<br/>
Map rating to label classes 0–4<br/>
Split:80% training, 20% validation<br/>
**To recreate the project, use the make dataset notebook**<br/>

## Link to Github and GoogleDrive
1. Link to github used in development: https://github.com/Adam-Wuth/NLP-project.git<br/>
2. Link to final github: https://github.com/Adam-Wuth/Amazon_Reviews_NLP.git<br/>
3. Link to Google Drive containing additional resources:https://drive.google.com/drive/folders/1guIdize8FzOsx_XGgixzWrsdJZ_BJPZs?usp=sharing<br/>

## Authorship, attribution, and acknowledgements
**Dataset setup and filtering:**<br/>
Adam Wuth, *Lead*<br/>
<br/>
**RNN Code:**<br/>
Aiden Devine, *Lead*
Adam Wuth, *Contributer*<br/>
<br/>
**Bigram Model Code:**<br/>
Benjamin Kohav, *Lead*<br/>
<br/>
**Trigram Model Code:**<br/>
placeholder, *Lead*<br/>
<br/>
**GRU Code:**<br/>
placeholder, *Lead*<br/>
<br/>
**DistillBERT Code:**<br/>
Adam Wuth, *Lead*<br/>
<br/>
