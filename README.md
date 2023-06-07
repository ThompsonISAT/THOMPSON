# THOMPSON

Trauma THOMPSON is a telementoring project aim to providing prediction of medical instructions from videos of surgical procedures for the user.
The basic methodology is including two parts: First, create a database for surgery videos with annotations of each step in the operation. Second, train a Deep Learning model that could generate prediction of medical instructions from the videos.

The evaluation of the model will perform on the test datasets, which approximately 20% of the data of the entire dataset. Then, we will use different evaluation metrics (e.g. BLEU, METEOR, and SPICE) to evaluate the performance of the model by computing similarity score between the ground truth and the prediction. Besides the numerical evaluations, the expert emergency physician will also provide professional evaluations for the predictions.
## Disclaimer
By downloading the dataset you acknowledge and agree to the following terms and conditions:
1. “I will not distribute, copy, or reproduce any of the individual images or videos contained within this dataset.”
2. “I acknowledge the dataset was developed to demonstrate proof of concept works around medical action recognition. The procedures have been completed using ‘available’ simulation equipment and/or ‘ad hoc’ available equipment to evaluate a proof of concept, and therefore these procedural videos may leave out critical steps and/or have direct errors that have not been tagged." 
3. “I acknowledge the dataset videos were dual verified for tagging accuracy, but they were not dual verified for medical or procedural accuracy & correctness. They should not be used for direct patient care.”

## Dataset
1. The dataset includes surgical videos of different participants in the head mount view of the procedures.
2. The annotation of the action during surgeries will collected from the participants as an audio file format.
3. The dataset is provide temporal context of actions.
4. The dataset is split into train, validation and test set.

List of Procdures
1. Chest Tube
2. Cricothyroidotomy
3. Tourniquet
4. Intraosseous Infusion
5. Needle Decompression

## Download link
Prior to downloading the data, users are required to sing the data usage agreement.
Link to the data usage agreement: [Trauma THOMPSON](https://shorturl.at/afvMP)

