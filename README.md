<h2>
  <p align='center'>
    Project591
  </p>
</h2>

<h4 align='center'> Project Description </h4> 
In this research paper, we present a novel approach for ingredient matching in cosmetic products using a knowledge-infused language model. We will fine-tune a large language model that is pretrained on generic corpora in order to generate (or match) the label, i.e intended cosmetic use given a list of cosmetic ingredients. An additional step that we will do is to incorporate an external source of knowledge such as a \emph{Knowledge Graph} (KG) into the model. The idea of knowledge graph is that it will additionally explore and introduce the relations between any two entities, i.e cosmetic ingredients to the model. We show how introducing the KG can affect the performance of the model on this downstream task, quantitatively and qualitatively.
<br>


## Tasks
  * Model Domain Training :white_check_mark: 
  * Model Task Specific Training :white_check_mark:
  * External Knowledge Graph Acquisition/Query processing :white_check_mark: - Information Acquisition
  * Query to filter information into various types :yellow_circle:
  * Conversion of RDFs to different formats 🔴 - Information retreival is not in the form of Knowledge Graphs now, so we won't be adding this part.  
  * Incorporation of additional knowledge into Model :yellow_circle:
  * Experimentations :yellow_circle:

## Notes
  * Will use the SPARQLWrapper library to query DBPedia programmatically without the need to download it to our local system. ❎
  * As DBPedia is not efficient for the filtering out useful information regarding a label that could help the model. Therefore we will be shifting to scaring the data off the net using Beautiful Soup. Incidecoder will be used for this. :white_check_mark:
      
## Datasets
### Domain Specific (Pre-training)
  * Amazon Product Dataset
        https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/
### Task Specific (Fine tuning) 
  * Cosmetic Product
        https://www.kaggle.com/datasets/kingabzpro/cosmetics-datasets
  * Sephora Dataset 
        https://www.kaggle.com/datasets/raghadalharbi/all-products-available-on-sephora-website
    
## Future Works:
* Try to use other Faster models (less parameters) - such as DistilBERT and Larger Models - such as RoBERTa
* Introduce more datasets in fine-tuning

<br><br><br>
![Anurag’s github stats](https://github-readme-stats.vercel.app/api?username=Anshumaan-Chauhan02)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=Anshumaan-Chauhan02&layout=compact)
