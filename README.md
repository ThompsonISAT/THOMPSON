# THOMPSON

Trauma THOMPSON is a telementoring project aim to providing prediction of medical instructions from videos of surgical procedures for the user.
The basic methodology is including two parts: First, create a database for surgery videos with annotations of each step in the operation. Second, train a Deep Learning model that could generate prediction of medical instructions from the videos.

The evaluation of the model will perform on the test datasets, which approximately 20% of the data of the entire dataset. Then, we will use different evaluation metrics (e.g. BLEU, METEOR, and SPICE) to evaluate the performance of the model by computing similarity score between the ground truth and the prediction. Besides the numerical evaluations, the expert emergency physician will also provide professional evaluations for the predictions.

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
