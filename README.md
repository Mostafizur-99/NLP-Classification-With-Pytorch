## NLP-Classification-With-Pytorch

Text Classification (or Text Categorization, Document Classification) is the process of analyzing natural language texts and labeling them with a predefined set of categories in order to make it easier to manage them.

# Type use cause are
 
 This repository focuses on classification of German texts using state-of-the-art deep learning models.

 # Dataset
 Here We will be using the Ten Thousand German Newspaper Article Dataset (10kGNAD). It contains 10,273 German-language news articles, which are categorized into 9 topics. The source of the news articles is the One Million Posts Corpus which mainly focuses on user comments posted on the Austrian newspaper website DER STANDARD. But it also includes the original news arcticles along with some meta data. Fortunately, all articles have been extracted, cleaned and prepared for text classification in the 10kGNAD respository on Github.

# Artical Dataset used to from the repository
[Artical Dataset](https://github.com/tblock/10kGNAD.git)

# Model used
- Bert Based.
- Distil Bert Based.

# Model Training

- Language Model (LM) Training
    - use pre-tained LM-baseline,Distilbert,Robert
    - language-specific vs. multi-language - the latter ones are larger
- Domain Adaption of Language Model
    - refine LM with task specific data (optional)
- Downstream task training
    - class imbalance - do nothing, oversampling, class weights
    - class imbalance - do nothing, oversampling, class weights
    -model head config
- Model Trainigng
    - Batch size
    - learning rate
    -iterations/steps
- Cross validation
