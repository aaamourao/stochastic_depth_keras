# Deep Networks with Stochastic Depth
Rewriting code for ["Deep Networks with Stochastic Depth"](http://arxiv.org/abs/1603.09382) in Keras.

Original code is at [yueatsprograms/Stochastic_Depth](https://github.com/yueatsprograms/Stochastic_Depth).

> Fork by @aaamourao
>
> mourao.aaa@gmail.com
>
> Encrypted mail: adrianomourao@protonmail.com

## Usage
### System requirements
You need to install the following libraries:
* Developer version of **libblas**
* Developer version of **liblapack**
* Developer version of **libatlas**
* **GNU Fortran**

##### Fedora install instructions
```
sudo dnf install blas blas-devel lapack lapack-devel atlas atlas-devel gcc-fortran
```

##### Ubuntu install instructions
```
sudo apt-get install libblas-dev liblapack-dev libatlas-base-dev gfortran
```

### [optional] Create a virtual environment
Run the following commands and replace `<virtual-dir-path>` for your target directory on your workspace
```
virtualenv --distribute <virtual-dir-path>
source <virtual-dir-path>/bin/activate
```

### Install python requirements
There are some python libraries required to run this project
```
pip install -r requirements.txt
```
> Hint : if pip doesn't find Keras library install it manually:
>
> ``` pip install git+https://github.com/aaamourao/keras.git@keras-1;
pip install -r requirements.txt```

### Install python libraries from repo

Just run `python train.py`


## Results

- Initial learning rate == 0.1
- Number of layers == 50
- (other configs are same as `train.py`)

![results](https://cloud.githubusercontent.com/assets/10726958/14409972/45c9b22c-ff5d-11e5-99ab-ab3fd9069bdd.png)
