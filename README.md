# Challenge_7
## Project Overview
notebook that clusters cryptocurrencies by their performance in different time periods.
---

## Technologies

The application is in python and is uing the following libraries:



* [pandas](https://pandas-profiling.github.io/pandas-profiling/docs/master/index.html) - For data analysis.

* [hvplot.pandas](https://github.com/holoviz/hvplot) - For advanced graphs.

* [Path](https://github.com/jaraco/path) - For relative and absolute path to the file.

* [scikit-learn](https://github.com/scikit-learn/scikit-learn)- Has many features. Used for Kmeans, PCA adn StandardScaler for this assignment. 


The operating system used in creating the application is Windows 10 64 bit. The application that used to code in notebook is Jupyter and then tested in Gitbash and Terminal. 

I created a engine for the application

The output file was read by:

```python
df_market_data = pd.read_csv(
    Path("./crypto_market_data.csv"),
    index_col="coin_id")
```
---

## Installation Guide

1. Open Gitbach or terminal and go ito the folder where you want to place the files.
2. Click on the blue "code" button which will allow you to clone.![<Code button in Github>]()
3. Then click on SSH or HTTPS as a clone method depending on if you have the SSH key setup. You will copy the link. You will then type "git clone" in Gitback or Terminal. Then paste the ssh or https information and press enter.
4. Next type "git pull" command in Temrinal or GitBash to pull the repository from the remote Github repository to a local directory on your computer.
5. You have access to the application. Also there will be all the python files that the application is depended on,  plus the excel file. 

---

## Usage

Below is a list of steps/analysis seen in the notebook:
    1.Find the Best Value for k Using the Original Data
    2.Cluster Cryptocurrencies with K-means Using the Original Data
    3.Optimize Clusters with Principal Component Analysis
    4.Find the Best Value for k Using the PCA Data
    5.Cluster Cryptocurrencies with K-means Using the PCA Data
    6.Visualize and Compare the Results

---

## Contributors

This application was provided by the instrutor of Columbia University and addtional code was added by Khatija Azeem to complete the project.

---

## License

For this application, I used Github to uplaod the file into a repository. Since this is a public file, there will be no restriction on usage of this code. 
