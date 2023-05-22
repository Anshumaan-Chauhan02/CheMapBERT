<h2>
  <p align='center'>
    CheMapBERT
  </p>
</h2>

<h4 align='center'> Project Description </h4> 
In this project, we present a novel approach for ingredient matching in cosmetic products using a knowledge-infused language model. We will fine-tune a large language model that is pretrained on domain-specific corpora in order to generate (or match) the label, i.e intended cosmetic use given a list of cosmetic ingredients. An additional step that we will do is to incorporate an external source of knowledge such as a Knowledge Graph (KG)/list of possible matches into the model. We show how introducing the external knowledge can affect the performance of the model on this downstream task, quantitatively and qualitatively.
<br>

### Technical Skills 
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
<br>

## Tasks
  * Model Domain Training :white_check_mark: 
  * Model Task Specific Training :white_check_mark:
  * External Knowledge Graph Acquisition/Query processing :white_check_mark: - Information Acquisition
  * Conversion of RDFs to different formats 🔴 - Information retreival is not in the form of Knowledge Graphs now, so we won't be adding this part.  
  * Incorporation of additional knowledge into Model :white_check_mark:
  * Experimentations :yellow_circle:

## Notes
  * Will use the SPARQLWrapper library to query DBPedia programmatically without the need to download it to our local system. ❎
  * As DBPedia is not efficient for the filtering out useful information regarding a label that could help the model. Therefore we will be shifting to scaring the data off the net using Beautiful Soup. Incidecoder will be used for this. :white_check_mark:
    
## Dependencies
#### 1) PyTorch
      https://pytorch.org/get-started/locally/
#### 2) TQDM
      pip install tqdm
#### 3) Transformers
      pip install transformers
#### 4) Pandas
      pip install pandas
#### 5) Numpy
      pip install numpy
#### 6) Requests
      pip install requests
#### 7) BeautifulSoup
      pip install beautifulsoup4

## Datasets
### Domain Specific (Pre-training)
  * Amazon Product Dataset
        https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/
### Task Specific (Fine tuning) 
  * Cosmetic Product
        https://www.kaggle.com/datasets/kingabzpro/cosmetics-datasets
  * Sephora Dataset 
        https://www.kaggle.com/datasets/raghadalharbi/all-products-available-on-sephora-website
## Files
* BERT_Domain_Training.ipynb:
* BERT_Classification_Task_Training.ipynb:
* BERT_Task_Training.ipynb:
* CheMapBERT.ipynb:
* External_Knowledge_Retrieval.ipynb:
* Label_Merging_591.xlsx:

## How to Run
1)
2)

## Future Works:
* Try to use other Faster models (less parameters) - such as DistilBERT and Larger Models - such as RoBERTa
* Query to filter information into various types: Filter down the information provided through external knowledge by using FAISS or ElasticSearch
* Merging of Labels in order to have more samples for each class/ Introduce more datasets in fine-tuning

<br><br><br>
![Anurag’s github stats](https://github-readme-stats.vercel.app/api?username=Anshumaan-Chauhan02)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Anshumaan-Chauhan02&layout=compact)
