# Lo-fi-Music-Generation

*__Train data:__* copyright-free lo-fi audio files uploaded by HoliznaCC0 on Free Music Archive

*__Links to his work!__*

- https://freemusicarchive.org/music/holiznacc0/lazy-summer-lofi-1
- https://freemusicarchive.org/music/holiznacc0/busted-guitar-lofi-edit
- https://freemusicarchive.org/music/holiznacc0/spring-at-last-lofi-tape

## Preliminary Audio Data Analysis using Librosa

<img width="410" alt="image" src="https://user-images.githubusercontent.com/64684527/197673369-e7bfd88a-e86a-4132-a94d-d28d873d9267.png">

<img width="397" alt="image" src="https://user-images.githubusercontent.com/64684527/197673252-8b4c7825-c4ab-4516-8db9-9fdbd78395fe.png">

## Why RNN?

Music is *__sequential time series data__* where data points are plotted in a sequence with time values. This is evident from the *__spectrogram__* above which is a plot of audio frequencies with respect to time. Hence, we can model audio data using RNN which learns the sequential characteristics and patterns of music to predict the next musical note.

## Model-Building using Tensorflow

The MP3 audio files were converted into the desired format of MIDI files to train the *__Recurrent Neural Network__*.

*__Reference__*: Music generation tutorial on [Tensorflow Github Repository](github.com/tensorflow/tensorflow) 

## Final Product

