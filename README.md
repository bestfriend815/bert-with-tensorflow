# bert-with-tensorflow

This is simple bert example and purposed for running on windows. You can download this and run on windows.

#Setup
  pip install -q tf-models-official==2.3.0

You can't access to the google cloud storage like this gs_folder_bert = "gs://cloud-tpu-checkpoints/bert/keras_bert/uncased_L-12_H-768_A-12" on Windows.
So it was modified for the purpose to run on windows by modifying some of the code.
Please reference this code I published
