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
  * ❗Getting low accuracy after task specific training 
      * Maybe too many labels, and relatively less data - combine some labels into 1 category
      * Either change the number of epochs of training and testing
      * Try to change the parameters such as Optimizer and Loss function
      
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
