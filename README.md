# Singular Value Decomposition in Image Noise Filtering

## General information

*Images* - source images used in research and evaluation.

*Metrics*:
- [Frobenius distance](https://en.wikipedia.org/wiki/Matrix_norm#Frobenius_norm)
- [PSNR](https://en.wikipedia.org/wiki/Peak_signal-to-noise_ratio)

*Implemented filters*:
- [K-SVD](https://github.com/Progern/svd_in_image_denoising/blob/master/k_svd.ipynb)
- [Non-negative matrix factorization (NMF)](https://github.com/Progern/svd_in_image_denoising/blob/master/NMF.ipynb)
- [Gaussian filter](https://github.com/Progern/svd_in_image_denoising/blob/master/gaussian_filter.ipynb)
- [Non-local means filter (NLM)](https://github.com/Progern/svd_in_image_denoising/blob/master/nlm.ipynb)
- [Principal Component Analysis (PCA)](https://github.com/Progern/svd_in_image_denoising/blob/master/PCA.ipynb)

Each IPython notebook represents an independent research about efficiency of separate denoising method.

## How to reproduce



### Google Colab

- Clone the repository
- Load the repository into Google Drive
- Open the required Google Colab IPython notebook
- Mount your drive and upload the required files ("Chooise files" button)
- If you want to use different images you would need to change the filenames in the notebook
- Run the code blocks one-by-one and have fun

### Local machine
- Clone the repository
- Open the Jupyter Notebook or Jupyter lab in the project folder
- You could omit the logic of mounting Google Drive (used only for Colab) 
- You need to change the filenames to the ones that would be in *../Images* in your system
- Run the code blocks one-by-one and have fun

**To review the results of our experiment open “K-SVD Results” file on “Algorithms evaluation” tab. There you can find results for every metric and image we processed with all algorithms.**
