# Music Genre Classification

In this python notebook we explore the flaws of the [GTZAN dataset](https://www.kaggle.com/carlthome/gtzan-genre-collection) and build several classification models. We use [librosa](https://librosa.org/) to extract spectrograms from audio samples and [keras](https://keras.io/) to build and train the models. We discuss how CNN kernels might not be well fit for spectrograms and also provide a simple recommendation system based on cosine similarity and use it to find replicas in the dataset.
