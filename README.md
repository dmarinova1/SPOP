# SPOP
Software Engineering 1
- 
This SPOP (Small Propriety Original Program) is a dog breed classifier using the K-Nearest-Neghbor Classifier.Linear Regression is also deployed to compare the accuracy score against that of k-NN. The program is given a dataset in csv format, containing obedience,lifespan in years, body length in inches, neck size in inches, low and high values for both height and weight, 3 dog sizes (small, medium, big) and dog breeds (small dogs: french bulldog, chihuahua, pomeranian, poodle; medium-dogs: siberian husky, dalmatian, boxer and big dogs: great dane, saint bernard, mastiff)
- Note: the obedience column contains percentage data signifying the ability of the dog to obey first command. The data was gathered from: https://en.m.wikipedia.org/wiki/The_Intelligence_of_Dogs#cite_ref-ReferenceA_18-0 
- Note: the lifespan data gathered from the wikipedia page of each canine

data on dog breeds' weight and height collected from American Kennel Club, link: https://www.petplace.com/article/dogs/pet-care/american-kennel-club-akc-breeds-by-size/ 


SPOP is written in Python. 

The open-source distribution Anaconda will simplify the package management and deployment of our machine learning applications and data processing. The Jupyter Notebook, delivered by Anaconda, will be the application of choice to create, edit and display the output of the Python script.

To significantly reduce the complexity of the program, Scikit-learn library will be deployed to provide the tools for the machine learning and classification modeling.
documentation scikit-learn helped build this SPOP program providing details on modules, methods, parameters specification:
https://scikit-learn.org/stable/documentation.html 

- SPOPv#.ipynb is the jupyter notebook containing the code of the SPOP-PROG.
- data-breed.csv is the dataset.
- SPOP_v0_35_colab.ipynb is the Google Colab notebook that can be used to run the code outside the Anaconda Distribution environment.

- Note: naming conventions of the ipynb file: since the SPOP is created incrementaly, the version of the program is indicated as version 'v' followed by a number.

