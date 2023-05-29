install requirements.txt

Download model through my huggingface for this use bellow commands

""" git lfs install """
""" git clone https://huggingface.co/GharudxD/faster-rcnn-for-invoice """

Add path in config path in belllow variables
TRAIN_DIR
VALID_DIR

config.py -- all config all paths
datasets.py -- preprocessing of data
utils.py -- for utlites
model.py -- define pre trained faster rnn model
main.py -- run this file for tranning
predict.py -- predict and save result