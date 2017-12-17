mychessgame
=========

Using a "smart" chess game as a human proof of work for the cryptocurrency Benana-Chain. 
This chess games uses machine learning to learn from a user's moves and it becomes "smarter" after each game played.

mychessgame was created after [deep-pink](http://erikbern.com/2014/11/29/deep-learning-for-chess/)


Dependencies
============

* [Theano](https://github.com/Theano/Theano): `git clone https://github.com/Theano/Theano; cd Theano; python setup.py install`
* [Sunfish](https://github.com/thomasahle/sunfish): `git clone https://github.com/thomasahle/sunfish`. You need to add it to PYTHONPATH to be able to play
* [python-chess](https://pypi.python.org/pypi/python-chess) `pip install python-chess`
* [scikit-learn](http://scikit-learn.org/stable/install.html) (only needed for training)
* [h5py](http://www.h5py.org/): can be installed using `apt-get install python-hdf5` or `pip install hdf5` (only needed for training)
