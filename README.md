## S&P 500 stock market analysis

### Table of Contents

1. [Installation](#installation)
2. [Motivation](#motivation)
3. [Repository Structure](#repo)
4. [Results](#results)
5. [Colab Notebook](#colab)
6. [Final Considerations](#considerations)

## Installation <a name="installation"></a>

Create a virtual environment named **stock_analysis**.

```
$ python3 -m venv stock_analysis -- for Linux and macOS
$ python -m venv stock_analysis -- for Windows
```

After that, activate the python virtual environment

```
$ source stock_analysis/bin/activate -- for Linux and macOS
$ stock_analysis\Scripts\activate -- for Windows
```

Install the requirements

```
$ pip install -r requirements.txt
```


## Motivation <a name="motivation"></a>

As an activity of the Data Science Nanodegree I am taking at Udacity and to try to combine the two things that I love the most that is data and finance I decide to analyse the stock market data, using Data Science techniques to see how factors such as politics and pandemics can influence the stock market.
Aiming at answering the following questions:

1. Does the elected President party has some influence at stocks prices ?
2. How the earlier pandemics affected the stock market ?
3. Is it possible to generate a simple network to predict the stock market prices ?

## Repository Structure <a name="repo"></a>

- The `data` folder contain the information about the presidents terms.
- The `Udacity_stock.ipynb` has the code with the analysis.

## Results <a name="results"></a>

The results can be found at the medium post available [here](https://jair-neto.medium.com/does-joe-biden-victory-will-make-your-investments-at-stock-market-skyrocket-9c2dda725a1e).

## Colab Notebook <a name="colab"></a>

You can also see the code at the Colab Notebook [here](https://colab.research.google.com/drive/1a8SB3ozDtLaXJ3IOMSIPW2Syh5BufxzH?usp=sharing)

## Final Considerations <a name="considerations"></a>

Go ahead and contribute to this repository, adding more factors that influence stock market prices and improving the model. If you use this code, please give credits.
