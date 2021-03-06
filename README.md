<h3>Determination of the similarity between the scientific papers using machine learning methods (July 2017)</h3>

Topic of my master thesis was determination of similarity between the scientific papers using machine learning methods. Corpus is downloaded from arxiv.org and includes all abstracts uploaded from 2009 year together with labels, ie. categories and subcategories of the abstract. Abstract can have multiple categories and subcategories, but for evaluation, only first category/subcategory is used. Text is tokenized and word vectors are created using four versions of word2vec, two versions of doc2vec and glove algorithm. Then, title and abstract vectors are created and used to clasterize papers in categories and subcategories using K-means and spectral clustering. For clustering in 18 categories best result is achieved using PVDBOW language representation and for clustering in 148 subcategories best result is achieved using skip-gram negative sampling.

Full description of work and results as well as overview of natural language processing (NLP) methods is given in thesis (in Serbian): https://drive.google.com/file/d/0BwOaPYkiPMKIWVRxcDJCTGNjNDQ/view?usp=sharing.
