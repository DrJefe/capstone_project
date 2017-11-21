# capstone_project
Capstone Project for Udacity's Machiner Learning Engineer Nanodegree

# About
Project seeks to determine what information provided by hospitals is useful for machine learning algorithms in predicting patient mortality.  Using a database with medical information from over 40,000 patients, the project uses different combinations of patient features in predicting mortality.

# Install
- This project was written in Python 2.7.0.  You can download Python 2.7 using the [Anaconda bundle installer.](https://conda.io/docs/user-guide/tasks/manage-python.html)
- This project uses Psycopg2 to access the PostgreSQL database.  Install information can be found here: http://initd.org/psycopg/docs/install.html

All data has been downloaded from the [Mimic-III website](https://mimic.physionet.org/):

MIMIC-III, a freely accessible critical care database. Johnson AEW, Pollard TJ, Shen L, Lehman L, Feng M, Ghassemi M, Moody B, Szolovits P, Celi LA, and Mark RG. Scientific Data (2016). DOI: 10.1038/sdata.2016.35. Available from: http://www.nature.com/articles/sdata201635

Access can be granted via PhysioNetWorks:

Goldberger AL, Amaral LAN, Glass L, Hausdorff JM, Ivanov PCh, Mark RG, Mietus JE, Moody GB, Peng C-K, Stanley HE. PhysioBank, PhysioToolkit, and PhysioNet: Components of a New Research Resource for Complex Physiologic Signals. Circulation 101(23):e215-e220 [Circulation Electronic Pages; http://circ.ahajournals.org/content/101/23/e215.full]; 2000 (June 13).

Algorithms are compared using an Area Under Curve (AUC) scoring system.  Information on AUC scoring can be found here: http://www.dataschool.io/roc-curves-and-auc-explained/

# License
`capstone-project` is a public domain work.  