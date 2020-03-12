# Python Fundamentals

1. Install Python3
2. Install & Update Anaconda
    1. [Download](https://www.anaconda.com/distribution/) and install
    2. Open a Terminal
        1. ``vim ~/.zshrc`` 
        2. Add the following line at the end of the file
            1. ``source ~/.bash_profile``
        3. ``source ~/.zshrc``
    3. ``conda update conda``
    4. ``conda update --all``
3. Install Jupyter Matplotlib
    1. ``conda install -c conda-forge ipympl``
    2. ``conda install nodejs``
    3. ``jupyter labextension install @jupyter-widgets/jupyterlab-manager``
    4. ``jupyter labextension install jupyter-matplotlib``
4. Request access to the Twitter API
    1. [Request Access](https://developer.twitter.com/en/apply-for-access)
    2. As personal choice I select "Exploring the API"
5. Test IPython programm
    1. ``ipython``
        1. Run some commands
        2. ``exit``
    2. ipython examples/ch01/RollDieDynamic.py 10 1


Source: [PythonFundamentalsLiveLessons](https://github.com/pdeitel/PythonFundamentalsLiveLessons)