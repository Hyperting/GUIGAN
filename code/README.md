
# Code for GUIGAN: Learning to Generate GUI Designs Using Generative Adversarial Networks

## Subtree Splitting

use GetSubtree.save_subtree_info.py

```
python save_subtree_info.py
```

This code is implemented using PyThon3 and the paths of the data need to be modified.

Please read and modify it as you need by yourself.

### Requirement

```
python -m pip install -r requirements.txt
```

## Style Embedding of Subtree

use StyleEmbedding.load_data.py and StyleEmbedding.load_subtrees.py to allocate the data randomly.

use StyleEmbedding.train_siamese_net.py to train the siamese network.

```
python train_siamese_net.py
```

the trained models: **[`Download`](https://drive.google.com/file/d/17pDI3r9M7Dj4eDKdaiDVuZm6wauDEQfF/view?usp=sharing)**


## Training GUIGAN to Generate GUI Design

get the processed data by: **[`Here`](https://drive.google.com/file/d/1chmdg2F9IvC4vyyfovz_lvP2_WlbulVz/view?usp=sharing)**

use GUIGAN_main.py to train the GUIGAN.

```
python GUIGAN_main.py
```

use GUIGAN_test.py to generate new GUI design.

```
python GUIGAN_test.py
```
