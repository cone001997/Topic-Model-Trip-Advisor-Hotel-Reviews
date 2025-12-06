## Create dedicated ML environment:

`conda create -n reviews_hotel python=3.11`

**To activate this environment, use**

`conda activate reviews_hotel`

**To deactivate an active environment, use**

`conda deactivate`

**To install libraries**
## core
`conda install numpy pandas scikit-learn matplotlib seaborn joblib notebook -y`

## NLP
`conda install nltk -y`
`conda install -c conda-forge spacy -y`
`python -m spacy download en_core_web_sm`

## topic modeling
`conda install -c conda-forge gensim -y`
`conda install -c conda-forge pyldavis -y`

## dimensionality reduction
`conda install -c conda-forge umap-learn -y`

## visuals
`conda install -c conda-forge wordcloud -y`