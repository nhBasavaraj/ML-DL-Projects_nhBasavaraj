### Pepper Disease Classification
### Setup for Python:

1. Install Python ([Setup instructions](https://wiki.python.org/moin/BeginnersGuide))
 else you can just search in YouTube for video installation and setup for python 3 You can refer that..

### Setup for Anaconda
2. Install Anaconda 
For to install Anaconda you can refer this [YouTube](https://youtu.be/Vt6loGK9Adc) Video. (Credits: Mr Dhaval Patel from Codebasics)

3. Install Python packages

----
pip3 install -r requirements.txt


#### To install specific version of the packages listed in requirements file using pip:

pip install tensorflow==2.4.0 matplotlib==3.3.3 pandas==1.2.3 numpy==1.19.4

#### To install packages to a specific environment,
pip install -m env_name tensorflow==2.4.0 matplotlib==3.3.3 pandas==1.2.3 numpy==1.19.4

##### NOTE: sometimes the versions you want to install may not be available in PyPi repository. In that case, you can install the package from other sources like local file or from a url.

pip install -f https://extras.wxpython.org/wxPython4/extras/linux/gtk3/ubuntu-18.04 tensorflow==2.4.0 matplotlib==3.3.3 pandas==1.2.3 numpy==1.19.4

#### To install the packages listed in requirements file using conda,
#### For Latest Version:

conda install tensorflow matplotlib pandas numpy

#### For Specific Version:

conda install tensorflow==2.4.0 matplotlib==3.3.3 pandas==1.2.3 numpy==1.19.4

----
### Training the Model

1. Download the data from [kaggle](https://www.kaggle.com/arjuntejaswi/plant-village).
2. Only keep folders related to Pepper remaining you can delete.
3. Run Jupyter Notebook or [Google Colab](https://colab.research.google.com/) in Browser.

NOTE: 📌 If in your local system contains GPU then go for Jupyter Notebook, else Go with [Google Colab](https://colab.research.google.com/) bcz this project need more computation power so google colab provides free GPU. 
