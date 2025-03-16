# Music genre classifier

## Task
Classifier build using statistical learning techniques to classify the genre of songs; the idea behind the solution I implemented is to use short time Fourier transform coefficients to obtain from them some features useful for both supervised learning (classification) and unsupervised learning (clustering) tasks.  In particular the STFT coefficients are complex numbers so I extract features from both real and imaginary part.

Another important point is I don't focus the work on the entire songs but split each of them into sequences and work independently on each one.

## Data
The dataset consist in 150 songs with their labels:

- Metal
- Rock
- Hip hop
- Reggae
- Country


## Results

I tried different models for the classification and we obtain accuracy value taking the most common label of sequences for each songs. The final result we obtained is an accuracy of 94 % using random forest algorithm.

The project is developed in R.
