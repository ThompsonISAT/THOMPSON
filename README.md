# THOMPSON

Trauma THOMPSON is a telementoring project aimed at providing prediction of medical instructions from videos of surgical procedures for the user.
The basic methodology is including two parts: First, create a database of surgery videos with annotations of each step in the operation. Second, train a Deep Learning model that could generate a prediction of medical instructions from the videos.

The evaluation of the model will be performed on the test datasets, which are approximately 20% of the data of the entire dataset. Then, we will use different evaluation metrics (e.g. BLEU, METEOR, and SPICE) to evaluate the performance of the model by computing a similarity score between the ground truth and the prediction. Besides the numerical evaluations, the expert emergency physician will also provide professional evaluations for the predictions.
## Disclaimer
By downloading the dataset you acknowledge and agree to the following terms and conditions:
1. “I will not distribute, copy, or reproduce any of the individual images or videos contained within this dataset.”
2. “I acknowledge the dataset was developed to demonstrate proof of concept works around medical action recognition. The procedures have been completed using ‘available’ simulation equipment and/or ‘ad hoc’ available equipment to evaluate a proof of concept, and therefore these procedural videos may leave out critical steps and/or have direct errors that have not been tagged." 
3. “I acknowledge the dataset videos were dually verified for tagging accuracy, but they were not dually verified for medical or procedural accuracy & correctness. They should not be used for direct patient care.”

## Dependencies:
1. Python >= 3.8
2. PyTorch >= 1.3
3. PyTorchVideo
4. torchvision
5. tensorboard
6. FairScale
7. GCC >= 4.9
8. OpenCV
9. Numpy, Pandas, PIL
10. lmdb, tqdm

Action recognition python main_recognition.py --mode train --path_to_data data  --path_to_save_models models --modality rgb --video_feat_dim 1024


Action anticipation python main_anticipation.py --mode train --path_to_data data  --path_to_save_models models --modality rgb --video_feat_dim 1024


## Dataset
1. The dataset includes surgical videos of different participants in the head mount view of the procedures.
2. The annotation of the actions during surgeries will be collected from the participants in an audio file format.
3. The dataset provides the temporal context of actions.
4. The dataset is split into train, validation, and test set.

## List of Procedures
1. Chest Tube
2. Cricothyroidotomy
3. Tourniquet
4. Intraosseous Infusion
5. Needle Decompression

## Download link
Prior to downloading the data, users are required to sign the data usage agreement.
Link to the data usage agreement: [Trauma THOMPSON](**https://shorturl.at/afvMP**)
   
## Dataset Download link
[Trama_THOMPSON](https://drive.google.com/file/d/1oR7ALawOAgg1LswFbtEfmL6HcbZpM5j1/view?usp=sharing)
<!-- 

Track 1: [Track 1](https://drive.google.com/drive/folders/1kuJBq5IhAXpEFoYNuSqpZb-SVWGrEen8?usp=drive_link)

Track 2: [Track 2](https://purdue0-my.sharepoint.com/:u:/g/personal/jiang841_purdue_edu/EYy9L8cxfKxBgprW4J3StAEBK1HBTRmcUE16TvSdUuNMtg?e=cDuFrG)



## Download link
Prior to downloading the data, users are required to sign the data usage agreement.
Link to the data usage agreement: [Trauma THOMPSON](https://shorturl.at/afvMP)

-->

