# Stock-News-relation-Analysis
This project target is want to find the relation between stock &amp; News


## Platform
Use jupyter Notebook to perform the project

## Analysis Model
Stock Data: We download the stock history data from the following website,and we choose 11 company for 5 years(2014~2018) to do the analysis
url:https://www.cnyes.com/USASTOCK/index.htm

News Data: We use spiter to craw the news from the "Seeking alpha",this website involve many information and financial news. We craw the detail from News summarries,you can see the detail from "WebCrawler_seeking alpha.ipynb"
url:https://seekingalpha.com/

## Text Analysis
We can get the Sentiment score from -1~+1,so we use the score to define the news is "good" or "bad"
tools: NLTK
url: 
NLTK - https://www.nltk.org/
Loughran and McDonald Financial Sentiment Word List - https://sraf.nd.edu/textual-analysis/resources/#LM%20Sentiment%20Word%20Lists

## Analusis Results
We found the bad news rate which in "Decrease data" is almost equal the "Increase data" for big commany.

If the company news data is to small like Acer,it won't have good analysis results.

Another question is the news website,because the "Seeking alpha" news have too much number like +5% or -3%.The number will impact the score from Text analysis.

But we can general say the news won't direct effect the stock rate for long period,because most of news is the company to operate the market. If you saw the bad news from the website,you can't surer predict the stock rate 
will down.
