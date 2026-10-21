Here is short file about text visualisation of closeness of the text phrases using embeddings and dimension reduction approaches.
For obtaining embeddings I used sentence-transformers as well it is more actual approach in compare with BoW or TF-IDF. Then I make first step of dimension reduction using PCA and then second with UMAP.  
In first attempts I trying to use other features in UMAP like variety, country, price etc. but finally I decided that it will be more interesting for me to use only text embeddings and then  
look to other features like rating, variety on visualisation. Also here prepared double donut plot about countries and varieties of wine.

I used famous dataset about wine from Kaggle:  
https://www.kaggle.com/datasets/zynicide/wine-reviews/versions/2
