# CIKM-blind-review-demo (DVAR)
This is a demo of CIKM submission "Adaptive User Preference Learningwith Macro- and Micro-Views" (DVAR for short). This repository is for blind review only.
## Requirment

numpy

numpy_indexed

dgl 0.6.x

tensorflow 2.x

## File structure

code/</br>
&nbsp;&nbsp;&nbsp;&nbsp;|_ DVAR.py  \# defines the DVAR model we used in the paper.</br>
&nbsp;&nbsp;&nbsp;&nbsp;|_ train.py  \# an example training script. </br>

data/ \# The pre-processed datasets</br>
&nbsp;&nbsp;&nbsp;&nbsp;|_ movielens/</br>
&nbsp;&nbsp;&nbsp;&nbsp;|_ lastfm/</br>
&nbsp;&nbsp;&nbsp;&nbsp;|_ serendipity/</br>
&nbsp;&nbsp;&nbsp;&nbsp;|_ ali/</br>

## Quick start

python code/train.py

After all training epochs finish, the optimal performance will be printed out.
