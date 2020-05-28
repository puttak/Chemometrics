# Chemometric Methods

Chemometric methods consist of a group of statistical models (regression and classification) that are applied to material-characterization data to gain useful insights such as finding adulterants in foods and checking the quality of pharmaceuticals. Materials/chemicals are often characterized by spectroscopy techniques (FTIR and mid-IR) which consist of a series of radiation intensities emitted at specific wavelengths. These radiations indicate the different type of chemical moieties/groups present in the material, and thus the whole spectrum is a characteristic (type) of the material being measured. In other words, these spectrums provide information to differentiate (or classify) the different type of materials. 

Similar to the other statistical analysis, the chemometric analysis also begins with exploratory data analysis (EDA) using unsupervised methods (clustering etc.) to identify different groups in the data. In particular to spectroscopy data, the intensities measured at different wavelengths are highly correlated and so the one-to-one mapping between spectrum and material-type is quite difficult. Hence, the most fundamental step in EDA is to use dimensionality-reduction techniques, primarily principal component analysis (PCA) to map the set of raw variables (intensities at different wavelengths) into a set of latent variables (linear combination of intensities at different wavelength) that help distinguishing different materials better. Once the EDA is performed, the next natural step is to use the information from the response variables as well, i.e., employing supervised learning methods both for regression as well as classification tasks. The most common methods for regression in chemometric analysis is partial least square (PLS) regression, while the classification is typically done using discriminants methods such as linear discriminant analysis (LDA) or PLS-DA.   



# Examples
Below are the some of the examples of chemometric analysis

- Coffee Variants: Spectrum of two types of coffee, Arabica and Robusta, are measured by  Downey *et al.* (*J. Agric. Food. Chem.* 1997, 45, 4357-4361). Using LDA, K-nearest neighbors (KNN) clustering, and neighborhood component analysis (NCA), the two variants of coffee are differentiated. 
- More coming soon.