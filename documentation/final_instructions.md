Please fork this repository and paste the github link of your fork on Microsoft CMT. Detailed instructions are on Coursera under Week 1: Course Project Overview/Week 9 Activities.

Watch our presentation and demo of this project here:

T20 Cricket World Cup Tweet Analysis Project In this project, we set out to mine a large number of tweets and answer the high level question of are the predictions that are made on twitter about a sporting even accurate and is their a coorelation with who wins?

We have built a notebook that you can walk through to see what we did for our analysis and be able to test out some of the code on your own.

This notebook can be used as a starting point and altered to do further analysis to answer other questions.

In order to run the analysis notebook follow the instructions below:

Instructions:

    Clone the rep
    Create the python env needed to run the program by running the following command in your terminal
        conda env create --file tweet_env.yml python=3.7
    Activate the env by running the following command in your terminal
        conda activate tweet_env
    Navigate to the bsi_sentiment folder to install this custom package by running the following command in your terminal
        cd dependencies/bsi-sentiment/
    Pip install a few other packages by running the following commands in your terminal:
        pip install pandas
        pip install selenium
        pip install webdriver_manager
        pip install sklearn
        pip install matplotlib
        pip install jupyter notebook
    Install the custom version of bsi_sentiment by running the following command in your terminal
        python setup.py install
    Navigate back to the root folder by running the following command in your terminal
        Cd ../..
    Add New Env to Jupyter Notebook Kernal by running the following command in your terminal
        python -m ipykernel install --user --name=tweet_env
    Open the Jupyter Notebook by running the following command in your terminal

    jupyter notebook

    Navigate to project/tweet_analysis_example.ipynb with in the Jupyter Notebook Portal
    Open the analysis notebook by clicking on the file of 'tweet_analysis_example.ipynb'
    Change kernel to tweet_env within the jupyter notebook
    Follow the instructions on notebook