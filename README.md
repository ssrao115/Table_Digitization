# **1. Table Digitization Architecture**
This is the overview of table digitization process from a data science perspective

![Alt text](docs/table_summary.jpg?raw=true "The Table Digitization - A DATA SCIENCE PERSPECTIVE")

**A. Graph Model - A DATA SCIENCE PERSPECTIVE**

![Alt text](docs/graph_model.jpg?raw=true "The Graph Model - A DATA SCIENCE PERSPECTIVE")

**A. Header Detection - A DATA SCIENCE PERSPECTIVE**

Header detection is consist of ensamble of two approach:-
1. Vision Method
2. NLP method
![Alt text](docs/header_detection.jpg?raw=true "The Header detection - A DATA SCIENCE PERSPECTIVE")

**a). Vision Method - A DATA SCIENCE PERSPECTIVE**

![Alt text](docs/vision_header.jpg?raw=true "The Vision Method - A DATA SCIENCE PERSPECTIVE")

**b). NLP Method - A DATA SCIENCE PERSPECTIVE**

![Alt text](docs/nlp_header.jpg?raw=true "The NLP Method - A DATA SCIENCE PERSPECTIVE")

#  **2. Installation Guide**
To setup cloned virtual environment with required python libraries for table_digitization using environment.yml

Steps:
 1. To recreate cloned environment, go to the environment.yml directory, run command:

    conda env create -f environment.yml
            
 2. To activate cloned environment,use command:

    source activate yourenvname

Additional third party softwares required are:
1. ImageMagick 6.9.9 

    This command should work: conda install -c conda-forge imagemagick
    If not then you can learn more here: https://imagemagick.org/script/download.php
    
2. GhostScript 9.21

    This command should work: conda install -c conda-forge ghostscript
    If not then you can learn more here: https://www.ghostscript.com/download.html

Note: These are windows supported versions of third party softwares. 
