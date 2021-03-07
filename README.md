# Cryptocurrencies

## Overview of the Analysis

    Accountability Accounting, a prominent investment bank, is interested in offering a new cryptocurrency
    investment portfolio.  They asked us to create a report that includes what cryptocurrencies are on the
    trading market and how they could be grouped to create a classification system for this new investment.
    
    The data we will be working with is not ideal, so it will need to be processed to fit the machine learning
    models. We will use unsupervised learning since there is no known output. To group the cryptocurrencies,
    we will use a clustering algorithm and use data visualizations to share findings with the board.
    
##  Summary

    Our analysis shows that there are a couple outliers that may need to be removed to get a better analysis
    of the data.  The BitTorrent currency is in it own class and is leading the pack in supply and mined.  The
    TurtleCoin currency, class 2, has a supply double and triples other class 2 coins.  These two should be
    removed and the analysis re-ran.
    
    The vast majority of other currencies are quite similar, almost equal, with a few that do better than the
    others.


<p align="center"><img src=https://github.com/PJ427/Cryptocurrencies/blob/main/Images/3D_scatter.PNG></p>

<p align="center"><img src=https://github.com/PJ427/Cryptocurrencies/blob/main/Images/hv_scatter.PNG></p>
