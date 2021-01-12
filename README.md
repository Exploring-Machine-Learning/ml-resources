# Getting Started in Machine Learning
There are many resources in getting started with Machine Learning and Deep Learning. To explore more of the sources that availabe for you, check out Tensorflow. Tensorflow provides people a guide to how you can go from a beginner to expert in theory and in practice. There are other popular deep learning frameworks that are often used for Deep Learning, such as **Keras**, **Caffe**, and **PyTorch**. Tensorflow, Keras, and Pytorch have been the most popular frameworks used in building NNs. Tensorflow 2.0 actually integrated Keras into their APIs, making the user experience much simpler and easier for generating NNs.  Though, do explore all and see which framework floats your boat. On the other hand, Pytorch now integrates Caffe into their APIs. <br>
* [Tensorflow](https://www.tensorflow.org/resources/learn-ml/theoretical-and-advanced-machine-learning)
* [PyTorch](https://pytorch.org/)

## Environments to code in
It is always nice to write your code using a notebook, IDE, or a text editor. (Most of the code you will be writing will be in Python). There are a couple notebooks that you can use to write your code: **Google Collab** or **Jupyter Notebooks**. Notebooks are create for organizing your code into blocks, fast prototyping, and reiteration of a specific block of code. Google Collab is a personal favorite because you can save your notebooks in your Google Drive, and you have free access to their powerful GPUs and TPUs. GPUs and TPUs drastically improves the training and test time, especially when working with images and CNNs. With Jupyter Notebooks, you get to work with more coding programs, but have no access to a GPU and TPU.  Though, we encourage you to explore both notebooks.
* [Google Collab](https://colab.research.google.com/notebooks/intro.ipynb#recent=true)
* [Jupyter Notebooks](https://jupyter.org/)

Some of the IDEs that you can use for computer programming are **PyCharm** (developed my JetBrains), **Microsoft Visual Studio Code** (VS Code), or **Spyder**. PyCharm supports virtual environments, allowing you to install scientific packages for certain projects without having to interface with the main system.  My favorite feature of Pycharm is it's scientific tool, which allows you to easily install scientific packages with just a click. This feature is only allowed if you have the professional edition, and students have the opportunity to get a year long license.  On the other hand, VS 
Code and Spyder are free IDEs, and you can make use of Anaconda to simplify package management and deployment. 
* [Pycharm](https://www.jetbrains.com/pycharm/)
* [VS Code](https://code.visualstudio.com/)
* [Spyder](https://www.spyder-ide.org/)

## Installing Virtual Environment
Python virtual environments are great for creating an isolated environment for Python projects.  If you have two separate Python projects that require the same Python library, but different versions, then creating an isolated environment would solve this issue without having to change the version in the system.  

### For Linux or MacOs
For Linux or MacOs, we will be using the virtualenv tool to create our isolated Python environments. <br/> 

First, install pip: <br />
`$ wget https://bootstrap.pypa.io/get-pip.py` <br />
`$ sudo python3 get-pip.py`

Install virtualenv and virtualenvwrapper: <br /> 
`$ sudo pip install virtualenv virtualenvwrapper` <br />
`$ sudo rm -rf ~/get-pip.py ~/.cache/pip`

Copy and paste the following text below to the ~/.bashrc file.  You can open the ~/.bashrc file with your favorite text editor. In here, I use vim: <br />

`$ sudo vim ~/.bashrc`

`#virtualenv and virtualenvwrapper `
`export WORKON_HOME=$HOME/.virtualenvs` <br />
`export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3` <br />
`source /usr/local/bin/virtualenvwrapper.sh`

Then, source your ~/.bashrc: <br />
`$ source ~/.bashrc`

## For Windows 
