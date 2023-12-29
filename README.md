# Estimating Gross Primary Product With Remote Sensing Data and Transformers
 
### Author
- Yanting Zheng (zheng.yant@northeastern.edu)
- Ryan Rad (r.rad@northeastern.edu)

### Sponser
Northeastern University

### About This Project

This is the code base of our paper "Estimating Gross Primary Product With Remote Sensing Data and Transformers". 

In this paper, we experimented with FT-Transformer, transfer learning, remote sensing data from Google Earth Engine (GEE) and FLUXNET data from FLUX stations (https://www.icos-cp.eu/ and https://ameriflux.lbl.gov/) to estimate gross primary product (GPP) at a large scale.

### Repository Structure

- **source**: Source code.
- **processed-datasets**: Processed .csv files which are used directly as upstream and downstream datasets.
- **ft-transformer**: Modified FT-Transformer written with Keras package (modified from https://github.com/aruberts/TabTransformerTF)
- **image**: The images generated from source code, including result analysis, sample distributions and so on.
- **model**: The serialized models (only the one with best result). Due to the size limit in Github repository, we uploaded large model files to Google Drive https://drive.google.com/drive/folders/1WLPDFrY1ftb3PDmCLJVsNkiDO42tCi2y?usp=sharing.

Raw data collected from both GEE and FLUXNET stations is not included in this repository.

