# Action-recognition-using-CNN-and-RNN

## About the Project
* This project aims to classify the videos present in UCF-101 dataset() using CNN and RNN<br>
* Video frames are extracted from the videos using ffmpeg, then Inception v3 (pretrained on Imagenet) is used to extract the features from the video frames which are then passed to a bi-directional LSTM for video classification<br>

## Working
* clone this project to your local repo
* `cd data` and download the dataset using `curl -k https://www.crcv.ucf.edu/data/UCF101/UCF101.rar --output UCF101.rar`
* unzip the `unrar e UCF101.rar` <br>
* `mkdir train,test,sequences,checkpoints`
* run the move_files.py and then extract_frames.py<br>
* Now run extract_features.py to extract features from the frames <br>
* Finally run the train_lstm.ipynb for training the neural network<br>
