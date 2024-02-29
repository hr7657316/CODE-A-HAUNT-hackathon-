# CODE-A-HAUNT-hackathon-


Problem-statement-no: CBP21
problem-statement:
Speech to text transcription for Indian languages. The problem entails transcription in the native script and then translation to English. The languages of interest are Hindi, Indian English, Urdu, Bengali, Punjabi.

SOLUTION :  automatic -  transcript - system 
the way to get rid of this native indian language in to way to correctly match and fine tune the modal with its accent is challenging. 
but we have come with the solution of it here we go : 



1. Model Selection

Base Model: Choosing  a robust pre-trained speech recognition model as a foundation.

whisper ai 

2. Dataset Preparation

Combine Datasets: combining Hindi, Punjabi, Urdu, Bengali, and Indian English datasets into a unified dataset into  the  indian accents . This will provide the model with a wide range of variations.

Transcription Accuracy:  Any errors in transcripts will propagate mistakes into the model.

Normalization: Normalize the audio to ensure a consistent volume and reduce noise.
Feature Extraction: Extracting relevant features like Mel-Frequency Cepstral Coefficients (MFCCs) or spectrograms from the audio.

3. Fine-tuning

Framework Choice: choosing  deep learning framework such as TensorFlow 
Load Pre-trained Model: Loding  chosen base model (wisper ai).

Adjust Output Layer: Modify the model's output layer to match the graphemes or phonemes of the languages in your dataset.
Training: Begin training the model using your dataset. Consider techniques like:
Data augmentation: Apply techniques like adding noise or time stretching to increase dataset diversity, preventing overfitting.
Learning rate scheduling: Start with a moderate learning rate and gradually decrease it over time.
Batch size and epoch tuning: Experiment to find the optimal values.

4. Evaluation

Validation Set: Spliting  dataset into a training set and a validation set.
Metrics: Evaluate the model's performance on the validation set using metrics like Word Error Rate (WER) or Character Error Rate (CER). These are used to measure the difference between the predicted transcripts and the ground truth.


5) Noice reduction 

modal work completely fine if there is background noice or any chaos in surrounding.



and final output will be there in form of transcript . and also will be adding text to speech as well to reverify the data.













