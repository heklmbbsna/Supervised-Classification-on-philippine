# Supervised Classification on philipine: A Dimension Reduction Experiment
 
This project aims to analyze how the major machine learning models respond to dimension reduction & find out an optimal one using a high dimensional dataset called [philipine]( https://www.openml.org/search?type=data&sort=runs&id=41145), from OpenML, an online machine learning platform for sharing and organizing data. As demonstrated by the experimental data analysis section (which you will see later on), this dataset contains 308 numerical features & one binary class without any missing value. This character makes the dataset a perfect platform for some high dimensional data analysis experiments.

Dimension reduction is a vast topic and there are still many ongoing researches under this field. In this project, however, two dimension reduction techniques are used & assessed: Principle Component Analysis (PCA) and Uniform Manifold Approximation and Projection (UMAP). Introduced in 2018, UMAP is an advanced tool for dimension reduction & visualization similar to scikit learn's t-SNE with better performances in general. You can refer to [this link](https://umap-learn.readthedocs.io/#:~:text=Uniform%20Manifold%20Approximation%20and%20Projection%20(UMAP)%20is%20a%20dimension%20reduction,three%20assumptions%20about%20the%20data) for more information about how UMAP works & how to use its API. In this project, the major usage scenario of UMAP is also covered.

This project is not only an initial exploration of machine learning & dimensionality reduction methods, but also a personal learning process for me. As a beginner in the field of data science, I may have many mistakes, as well as potential improvements. I would be grateful if you could point them out.

For more details about the project, please refer to the jupyter notebooks.
