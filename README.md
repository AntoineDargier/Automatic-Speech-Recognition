# Automatic Speech Recognition

### Goal
Implementation and comparison of Speech-to-text models (CNN, CTC, Wav2Vec2.0)

### Language
```Python```

### Contents
1. Methodology
2. CNN Model
3. CTC Model
4. Wav2Vec2.0
5. Evaluation

### Libraries
* ```TensorFLow```
* ```HuggingFace, HuggingSound, SpeechRecognitionModel```
* ```scikit-learn```
* ```librosa```
* ```nltk```
* ```pandas```
* ```numpy```

### Conclusion
In the study, I was able to familiarize myself
with traditional ASR methods and seek to understand state-of-the-art algorithms. I was also able
to develop a relatively simple CNN algorithm.
I tested this algorithm on a Kaggle dataset. My
results are logically worse, largely because it was difficult for me to train our models for a long time and
on a lot of data.
The Wav2Vec2.0 model was very impressive in the
tests (WER=21.7%), as it has very good results and is very easy to
implement. The variety of languages available
is also a real advantage. However, the transcriptions
are slow (10 seconds for a 10- second audio), which
can be a hindrance to obtaining large audio transcriptions.
