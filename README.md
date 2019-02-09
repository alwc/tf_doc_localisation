# tf_doc_localisation

### Requirements

1. tensorflow version==1.12.0
2. PIL (pip install PIL)
3. download [part of the dataset](https://drive.google.com/drive/u/0/folders/1D7tv5NkFlnVWZQ3ViIO2EHpYK0nlGRfV)，extract it to $MIDV_DATASET
4. Edit tf_doc_localisation/receipt_dataset.py line 18 

``` python
midv_dir = MIDV_DATASET ## for example: /data/your_download_directory/midv_500
```

### how to train the network

1. cd tf_doc_localisation
2. mkdir data
3. python synthesis_data.py
4. python receipt_dataset.py
5. python train.py

### todo

1. add evaluation code.
2. 🚧 🚧 🚧 🚧 🚧


