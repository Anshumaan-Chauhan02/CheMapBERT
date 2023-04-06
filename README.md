<h2>
  <p align='center'>
    Project591
  </p>
</h2>

## Tasks
  * Model Domain Training :white_check_mark: 
  * Model Task Specific Training :white_check_mark:
  * External Knowledge Graph Acquisition/Query processing :yellow_circle: 
  * Conversion of RDFs to different formats :yellow_circle: 
  * Incorporation of additional knowledge into Model
  * Experimentations

## Notes
  * DBPedia -  Will use the SPARQLWrapper library to query DBPedia programmatically without the need to download it to our local system.
      
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
