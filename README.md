# 702-stress-detection
NLP 702 stress detection project
Our implementation of the NLP 702 research project.
The file Data Scraping.ipynb contains code to scrape from Reddit,
The file bert_embeddings.ipynb contains the data to generate embeddings for the data scrapped from Reddit, 
The file clustering.ipynb contains code to perform unsupervised clustering on the data scraped from Reddit,
The file thresholding.ipynb contains code to assign new labels to the Reddit dataset, 
The file bert_emotions_ft.ipynb contains code to pretrain bert on GoEmotions dataset, 
The file dreddit_ft.ipynb contains code to fine-tune the pretrained model on dreaddit dataset, 
The file dreddit_ft_corrected.ipynb contains code to fine-tune the pretrained model on combined dreaddit + our scrapped dataset. 
