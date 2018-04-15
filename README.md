### Jupyter Notebooks - Predict Polish stock market prices using RNN
The task of the project is to facilitate the work with the Stock-RNN project in order to predict the price of shares on the Polish stock exchange. The project is fully described in my blog [code-addict.pl](http://code-addict.pl).
The project consists of:
1. Docker containers containing Jupyter Notebooks, Tensorflow (with Tensorboard), MongoDB
2. Jupyter notebooks with code described in blog post.
3. Project subtree - Stock-RNN which allow to build ,train and test neural network to predict Polish stock market prices.


## Running
To run project simply run docker container using:
```bash
docker-compose up
```
You will find http link to Jupyter Notebooks in the console.

There are two notebooks. They are both creating same Tensorflow graph and initialize training process but I thins `PolishStockMarketPredictor_2` is better and I described it in my blog post.


