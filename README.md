# Unsupervised Machine Learning Techniques and Pandemics Spread: The Case of COVID-19 - Code and datasets
## Description
This repository contains the code and datasets for the paper Unsupervised Machine Learning Techniques and Pandemics Spread: The Case of COVID-19, accepted at the SBCAS 2020 (20º Simpósio Brasileiro de Computação Aplicada à Saúde) scientific event. Descriptions of the implementation and the dataset are contained in the paper (link: XXX, the link will be inserted once it is available). Currently, there is one Colab code per month (January, February, and March).

The code was developed by Roberto Fray da Silva and Fernando Xavier

Reference of the paper: XXX (reference of the paper)
To cite this repository: XXX (reference of the paper)

## To Do (further research, out of the scope of this paper):
- optimize code for deployment in production (there are several parts of the code that can be improved)
- deploy code for daily clustering
- incorporate new variables (socioeconomic, population density, etc) and more recent data
- automate data collection
- automate map generation
- evaluate other models, both unsupervised and supervised
- evaluate other options of feature engineering

## Credits for the code:
The code was implemented using Google Colab to improve replicability (https://colab.research.google.com/) and was based on the following:
- A demo of K-Means clustering on the handwritten digits data from the scikit-learn tutorial: http://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_digits.html
- K-means Clustering Python Example by Cory Maklin on Medium (2018): https://towardsdatascience.com/machine-learning-algorithms-part-9-k-means-example-in-python-f2ad05ed5203
- SILVA, R.F.; MOSTAÇO, G.M.; XAVIER, F.; SARAIVA, A.M.; CUGNASCA, C.E. Comparison of the k-means and self-organizing maps techniques to label agricultural supply chain data. In: Conference of the European Federation for Information Technology in Agriculture, Food and the Environment (EFITA), 2019, Rhodes, Greece.

The authors would like to thank the authors of the codes for providing them as examples for the use of the libraries and model implementation. 

The authors would also like to thank all the developers that were and are involved on the development of the following Python libraries: 
- Pandas: https://pandas.pydata.org/
- Scikit-Learn: https://scikit-learn.org/
- Matplotlib: https://matplotlib.org/
- NumPy: https://numpy.org/
- Seaborn: https://seaborn.pydata.org/
- SciPy: https://www.scipy.org/
- Geopandas: https://geopandas.org/

## Credits for the dataset:
The authors would like to thank the following institutions/researchers for providing the data collected:
- World Bank: total population, population density and age structure: http://wdi.worldbank.org/table/2.1#
- United Nations Development Programme: HDI: http://hdr.undp.org/en/data#
- World Health Organization COVID-19 Situation Reports, collected from Our World in Data: total number of cases, the total number of deaths, new cases and new deaths: https://www.who.int/emergencies/diseases/novel-coronavirus-2019/situation-reports  and  https://ourworldindata.org/coronavirus-source-data
- Johns Hopkins University CSSE [Dong, Du, Gardner, 2019]: number of recovered patients: https://github.com/CSSEGISandData/COVID-19  and  Dong, E., Du, H., Gardner, L. (2020) "An interactive web-based dashboard to track COVID-19 in real time". The Lancet Infectious Diseases, Correspondence, p.1-2.

## Acknowledgements:
This work was supported by the Coordenação de Aperfeiçoamento de Pessoal de Nível Superior - Brazil (CAPES) - Finance Code 001, Itaú Unibanco S.A. through the Itaú Scholarship Program, at the Centro de Ciência de Dados (C2D), Universidade de São Paulo, Brazil, and also by the National Council for Scientific and Technological Development (CNPq).
