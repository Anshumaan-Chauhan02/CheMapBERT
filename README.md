<h2>
  <p align='center'>
    Project591
  </p>
</h2>

## Tasks
  * Model Domain Training :white_check_mark: 
  * Model Task Specific Training :white_check_mark:
  * External Knowledge Graph Acquisition/Query processing :yellow_circle: 
  * Conversion of RDFs to different formats 🔴 - Information retreival is not in the form of Knowledge Graphs now, so we won't be adding this part.  
  * Incorporation of additional knowledge into Model
  * Experimentations

## Notes
  * Will use the SPARQLWrapper library to query DBPedia programmatically without the need to download it to our local system. ❎
  * As DBPedia is not efficient for the filtering out useful information regarding a label that could help the model. Therefore we will be shifting to scaring the data off the net using Beautiful Soup. Incidecoder will be used for this. 
      
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
