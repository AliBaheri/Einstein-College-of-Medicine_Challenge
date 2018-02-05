# Einstein College of Medicine ML Challenge:


### Overal:
This repo contains the materials for `Einstein College of Medicine ML Challenge`.

### Data:
Original data: [Citibike Monthly Trip Data](https://s3.amazonaws.com/tripdata/index.html).
Using 2014 data, I preprocessed data such that the inputs of our algorithms are `Time` and `Location ID`, and the outputs are
`# of bike in` and `# of bike out`.


### Objective:
Build a machine learning model to predict the number of riders per hour for an entire month using the previous 6 months data.


### Methods:
Two methods were used:

1) Neural network including `simple neural net`, `Recurrent neural network (RNN)`, and an `LSTM network`.
2) `Random forests`.


### Summary:
It turns out that `Random forsets` outperforms both `RNN` and `LSTM` networks. In fact, while the performance of `Random forests` algorithm is pretty good, it is a bit interesting why `RNN` and `LSTM` networks lead to poor results.
