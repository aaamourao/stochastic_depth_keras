# Deep Networks with Stochastic Depth
Rewriting code for "Deep Networks with Stochastic Depth" http://arxiv.org/abs/1603.09382 in Keras.

Original code is at https://github.com/yueatsprograms/Stochastic_Depth.


## Usage

1. Install [Theano](https://github.com/Theano/Theano) following its instruction.
2. Install [Keras](https://github.com/fchollet/keras) (I use new API at `keras-1` branch)
   ```
$ cd keras
$ git checkout keras-1
$ python setup.py install
```

3. Just run `python train.py`


## Results

- Initial learning rate == 0.1
- Number of layers == 50
- (other configs are same as `train.py`)

![results](https://cloud.githubusercontent.com/assets/10726958/14409972/45c9b22c-ff5d-11e5-99ab-ab3fd9069bdd.png)
