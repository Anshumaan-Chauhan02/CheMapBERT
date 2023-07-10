<h2>
  <p align='center'>
    CheMapBERT
  </p>
</h2>

<h4 align='center'> Project Description </h4> 
In this project, we present a novel approach for ingredient matching in cosmetic products using a knowledge-infused language model. We fine-tuned a large language model that is pretrained on domain-specific corpora in order to generate (or match) the label, i.e intended cosmetic use given a list of cosmetic ingredients. An additional step that we did is to incorporate an external source of knowledge - list of possible matches into the model. We show how introducing the external knowledge can affect the performance of the model on this downstream task, quantitatively and qualitatively.
<br>

### Technical Skills 
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
<br>
    
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
  * Amazon Product Dataset :
        https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/
### Task Specific (Fine tuning) 
  * Cosmetic Product :
        https://www.kaggle.com/datasets/kingabzpro/cosmetics-datasets
  * Sephora Dataset :
        https://www.kaggle.com/datasets/raghadalharbi/all-products-available-on-sephora-website
## Files
* BERT_Domain_Training.ipynb: Pretraining  of BERT using MLM
* BERT_Classification_Task_Training.ipynb: Fine tuning of BERT Model after Weight Transfer from MLM BERT 
* BERT_Task_Training.ipynb: Downstream Task Finetuning on MLM BERT (Not Recommended)
* CheMapBERT.ipynb: Implementation of BERT fine tuning w/ External Knowledge 
* External_Knowledge_Retrieval.ipynb: Contains code for external knowledge retrieval
* Label_Merging_591.xlsx: Future Work Label Merging (Under Work)

## How to Run
1) Download all the ipynb files from the Repository
2) Download all the datasets using the links provided
3) Run BERT_Domain_Training.ipynb for the pretraining and then store the weights (in the same folder)
4) Run CheMapBERT/BERT_Classification_Task_Training files to fine tune the pretrained model on the downstream task with and without External Knowledge Incorporation

## Future Works:
* Try to use other Faster models (less parameters) - such as DistilBERT and Larger Models - such as RoBERTa
* Query to filter information into various types: Filter down the information provided through external knowledge by using FAISS or ElasticSearch
* Merging of Labels in order to have more samples for each class/ Introduce more datasets in fine-tuning

<br><br><br>
![Anurag’s github stats](https://github-readme-stats.vercel.app/api?username=Anshumaan-Chauhan02)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Anshumaan-Chauhan02&layout=compact)
