# TP4MTS
Temporal Pattern Recognition for Medical Time Series by Adversarial Learning with Curricular Masking.

All datasets are preprocessed and accessible at https://github.com/SCXsunchenxi/ISMTS-Review

## To run your own model

`python model/ajrnn.py --batch_size 20 --epoch 400 --lamda_D 1 --G_epoch 5 --train_data_filename xxx.csv --test_data_filename xxx.csv`
