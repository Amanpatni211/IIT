
Data -> Information 
After Training a model we can extract Patterns and useful info from it.
Before we input a dataset to the model , we do Pre Processing and make data ready for the model.
there are different methods and philosophies to achieve it; and they need math to back them up.

Assumption: 
In the course Data Ingestion and Data Validation (including EDA) has been achieved.
The Current State is Version of Data which is raw data in usable format. 
Now Feature Engineering means to operate and append features so as to achieve best model performance.
What all can be done in feature engineering?
Broadly speaking 3 things are done:
	Data Cleaning
	Data Transformation
	Data Reduction
Various methods exist for all 3 steps and are used as required for the particular case.
![[Pasted image 20240711185248.png]]
The Figure gives an idea as what are the different actions performed for achieving the Header.
<I assume that in this module only Math required has to be taught in general for various actions here>
Math is needed essentially in Data Reduction step.

All the methods in figure has its need and options to achieve them.
No need for a different mathematics section for Data Cleaning and Data Transformation.
For Data Reduction, 

For PCA
	we need to use Linear Algebra (EigenValues, Basis and Basis Change, Projections), Constraint optimization, Gaussian Distributions. 

For T-sne 
	this link<https://tivadardanka.com/blog/how-tsne-works>
It is a blog on math of T sne

Feature Engineering

1. Numerical Data
    
    - Polynomial features
    - Interaction terms
    - Log transformations
2. Categorical Data
    
    - Target encoding
    - Feature hashing
    - Grouping rare categories
3. Time Series Data
    
    - Lag features
    - Rolling statistics (moving average, moving standard deviation)
    - Fourier transform for frequency domain features
4. Image Data
    
    - Feature extraction (e.g., edge detection using filters)
    - Convolutional Neural Network (CNN) features
    - Data augmentation (rotation, flipping, cropping)

There are other Data types like Audio Signals , Textual Data etc having their own ways of feature Engineering. NLP Feature Engineering is a big topic in itself.

