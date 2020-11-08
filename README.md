# 🚀Ovarian-Cancer-Subtypes-Identification💻

🧠Deep Learning-based✔️ Ovarian Cancer🙅🏻‍♀️  Subtypes Identification using Multi-Omics Data✅


![Author](https://img.shields.io/badge/author-garimasingh128-orange)
![Author](https://img.shields.io/badge/author-mrinal41298-orange)
![License](https://img.shields.io/badge/license-MIT-brightgreen)
![Platform](https://img.shields.io/badge/platform-Visual%20Studio%20Code-blue)
![Maintained](https://img.shields.io/maintenance/yes/2020)

## 🚀Contributor Details:💻
- Garima Singh (1806143)
- Mrinal (1806149)

# 🚀Paper Details💻

## Published:✨ 
24 August 2020

## Authors:✨
- Long-Yi Guo
- Ai-Hua Wu, 
- Yong-xia Wang, 
- Li-ping Zhang, 
- Hua Chai  
- Xue-Fang Liang

## Institutions:✨
- Second School of Clinical Medicine, Guangzhou University of Chinese Medicine, Guangzhou, 510020, China
- Center for Reproductive Medicine, Guangdong Hospital of Traditional Chinese Medicine, Guangzhou, 510120, China
 
 ```
 PMID: 32863885
 PMCID: PMC7447574
 DOI: 10.1186/s13040-020-00222-x
 ```
 
## Model implemented by us👣
The model used by us is a logistic regression classification model which uses K-means clustering techniques. We have chosen to align with the paper specifications and techniques as closely as possible but changed certain values to improve accuracy score. 
The multi-omics data of patients are inputted into the Denoising Autoencoder for generating z. With the help of generated z, the patients are clustered using k-means. The optimal number of clusters was determined using silhouette score. In the model, we tested the k from [2, 8] and we finally used k=2 as it had the highest silhouette score. 
After obtaining the labels clustered by k-means, we built a light-weighted mRNA model for reducing the number of genes needed to identify cancer subtypes by using a logistic regression algorithm.

## Code walk-through👣
This is the python code for denoising autoencoders (DAE)🚀 and the k-means using the reconstructed features. The silhouette scores and Davies Bouldin scores (DBI) were used to evaluate the clustering performances.

## Sources👣
- https://jovian.ai/garimasingh128/deep-learning-based-ovarian-cancer-subtypes-identification-using-multi-omics-data
- https://colab.research.google.com/drive/1_ruztGS5i1h9ugO28h_foaK_0Sczsq_H?usp=sharing
- https://colab.research.google.com/drive/1dj2WfGTwTJYjATTJXxSUNyGZuRD2FW5O?usp=sharing

## Conclusion👣
- We designed a novel deep learning-based framework for ovarian cancer subtype identification, and a logistic regression method was used to build the light-weighted classification model.
- Compared to identifying subtypes using single omics data, the multi-omics data analysis can utilize more information. Hence, we proposed a model which in turn would help to robustly identify ovarian cancer subtypes.
- Ovarian cancer ranks 5th in cancer death among women. It has a high mortality rate. Also the risk of getting ovarian cancer is quite high. So, identifying molecular subtypes of ovarian cancer is important. 

🚀 It is important to know more about the ovarian cancer heterogeneity between different patients for choosing different treatment programs and predicting clinical outcomes. In this study we proposed a novel deep learning framework for integrating multi-omics data with denoising autoencoders for identifying the ovarian cancer subtypes. Two subtypes from the molecular level were identified in ovarian cancer, and the results show our proposed method is competitive and reliable. The method comparison results indicated our method out-performed than the traditional and deep learning-based methods. More importantly, the classification model was proved by three independent test datasets collected from GEO. All the p-values less than 0.05 show that the differences between the classified cancer subgroups are significant.
```
By combining the results in DEG and WGCNA analysis, we selected 34 target genes related to ovarian cancer. And using these 34 identified genes, 19 KEGG pathways were enriched including PI3K-Akt signaling pathway and human papillomavirus infection pathway. The literature review shows 19 (56%) biomarkers and 8(42.1%) KEGG pathways identified based on the classification subtypes have been proved to be associated with ovarian cancer.
```
## References👣
- https://biodatamining.biomedcentral.com/articles/10.1186/s13040-020-00222-x
- https://linkinghub.elsevier.com/retrieve/pii/S0090825810002623
- https://clincancerres.aacrjournals.org/content/14/16/5198

### Availability of data and materials👣
All the data analyzed during the current study are available in the TCGA and GEO datasets.
  
## 🔆 Tech Stack
The project is created using Python in Jupyter lab.

## 🚀 Steps to setup development environment
1.  Clone the repo
 ```bash
 git clone github.com/your_usernameOvarian-Cancer-Subtypes-Identification.git
 ```
 2. Open the folder in your favorite code editor and start adding modifications.

 ## 💻 Development guidelines

1.  Put all the code you want to in necessary folders.
    
3.  Push all the code to your own branch. Once you are sure it is working, merge it with the `dev`  branch. Let's maintain only the stable and released versions on the  `master`  branch.
    
4.  Write a kick-ass, readable, and clean code.

## 📝 Learning Resources

Read these articles to get a quick grab on Git and Github:

### 📝 Resources to learn Git and Github: 📝 
- https://try.github.io/
- https://docs.github.com/en/github/getting-started-with-github/git-and-github-learning-resources
- https://guides.github.com/activities/hello-world/

`Feel free to create issues to suggest and add functionalities and features.`


## 💻 System Requirements
-  Google Chrome
-  Git
-  Code Editor (Jupyter preferrably)
-  Python

## 🏆 Contributing

Please read  [CONTRIBUTING.md](CONTRIBUTING.md)  for information on how to contribute to Ovarian-Cancer-Subtypes-Identification.

##  💼 Code of Conduct

We want to facilitate a healthy and constructive community behavior by adopting and enforcing our code of conduct.

Please adhere towards our [code-of-conduct.md](code-of-conduct.md).

## 👬 Owner

<a href="https://github.com/garimasingh128"><img src="https://avatars3.githubusercontent.com/u/44302373?s=460&u=efaafa72f4d83d40b66fc68258d14cebbf1d7de0&v=4" width="100px;" alt=""/><br /><sub><b>Garima Singh</b></sub></a><br/>
<a href="https://github.com/mrinal41298"><img src="https://avatars3.githubusercontent.com/u/55679963?s=460&u=66c9d1ec2ce9183bb517311a4f5ff32286e4df72&v=4" width="100px;" alt=""/><br /><sub><b>Mrinal Kumar</b></sub></a><br />


[![built with love](https://forthebadge.com/images/badges/built-with-love.svg)](https://github.com/garimasingh128)

## ❤️ Thanks to our awesome contributors.



