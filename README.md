# Audio-Event-Detection

The objective is to develop Machine Learning models to detect events using audio files. The list of events is (10 events): dog bark, engine idling, siren, jackhammer, drilling, children playing, gun shit, car horn, air conditioner and street music. The basic idea is to extract features from audio data using *Fourier Transform*. For more details, see **report.pdf**. We develop models for two tasks: 

## Task - 1
The goal is to classify an audio file into one of the possible events. It is a **multiclassification problem**. The task-1 folder has 3 notebooks corresponding to data preprocessing, training of model and testing of model on unseen data.

## Task - 2
The goal is to determine the sequence of audio events in a single *.wav* file. The sequence of events our model outputs is critical to  the accuracy of the model. The evaluation metric is *edit distance*. The task-2 folder has 3 notebooks corresponding to generating data from single event audio files, training of model and testing of model on unseen data.
<br/><br/>

**Note:** The link to the train data ('.wav' files) is: https://drive.google.com/drive/folders/1SLk9xU8bGSb98FGqlb5Q19oqTejqKy-f?usp=sharing
