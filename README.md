# MyDigitalFootprint

MyDigitalFootprint (MDF) is a novel large-scale dataset composed of smartphone embedded sensors data, physical proximity information, and Online Social Networks interactions aimed at supporting multimodal context-recognition and social relationships modeling in mobile environments.
The dataset includes **two months** of measurements and information collected from the personal mobile devices of **31 volunteer users** by following the in-the-wild data collection approach: the data has been collected in the users' natural environment, without limiting their usual behavior.
Existing public datasets generally consist of a limited set of context data, aimed at optimizing specific application domains (human activity recognition is the most common example). On the contrary, our dataset contains a comprehensive set of information describing the user context in the mobile environment.

The complete analysis of the data contained in MDF has been presented in the following pubblication:

[1] [M. G. Campana, and F. Delmastro. **MyDigitalFootprint: An extensive context dataset for pervasive computing applications at the edge.** Pervasive and Mobile Computing, 2021.](https://doi.org/10.1016/j.pmcj.2020.101309)

The full anonymized dataset is contained in the file **MDF.tar.gz**.
Moreover, in order to demonstrate the efficacy of MDF, in [1] we also presented three proof of concept context-aware applications based on different machine learning tasks:
1. a social link prediction algorithm based on physical proximity data,
1. the recognition of daily-life activities based on smartphone-embedded sensors data,
1. a pervasive context-aware recommender system.

For the sake of reproducibility, the data we used to evaluate the proof-of-concept applications are contained in the files **link-prediction.tar.gz**, **context-recognition.tar.gz**, and **cars.tar.gz**, respectively.

To the best of our knowledge, this is the first large-scale dataset containing such heterogeneity of information, representing an invaluable source of data to validate new research and applications in different domains, including mobile and edge computing, human behavior modeling, human mobility, and context-aware recommender systems.
Researchers are encouraged to use MDF to develop and compare methods and algorithms in their research field, by citing [1].

## Download Instructions

MDF has been released as [Git Large File Storage](https://git-lfs.github.com) (LFS) repository.
In order to download the dataset, please follow these steps:

1) Download Git LFS: [https://git-lfs.github.com](https://git-lfs.github.com)
2) Set up Git LFS for your user account by running
   > git lfs install

3) Download MDF by cloning the repository with
   > git lfs clone https://github.com/contextkit/MyDigitalFootprint.git
