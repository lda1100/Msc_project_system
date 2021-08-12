How to use?

*************************************************************************
Firstly crawl_steam.py is executed to crawl the data requested by the user.
Next execute crawl_douban.py, which crawls the user's reviews on Douban based on the name of the game selected.
Execute add_label.py, which divides reviews into positive and negative based on star ratings.

split_pos_neg.py, which separates out four different txt files based on rules to be used as input to the model.
scatter_chart_data.py, which processes the crawled steam data into data that can be used to generate scatter plots.
Steam_reviews_neg.py, crawls negative reviews from steam, including scroll wheel loading data.
Steam_reviews_pos.py, captures positive reviews from steam, including scroll wheel loading data.

The CNN model executes the data and stores the accuracy in price_information.txt.
GRU model executes the data and stores the accuracy in price_information.txt.
LSTM model execution data, with accuracy stored in price_information.txt.

price_information.txt stores the crawled and trained game data.
calculate.py finally calculates the recommended price.

**************************************************************************

stopwords.txt is the file that contains all the words that need to be filtered.

chromedriver.exe provides drivers for Chrome.

The platform_information file holds all the acquired data and is stored in an excel file.