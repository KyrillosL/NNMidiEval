# NNMidiEval - Only for a presentation purpose
Simple midi file evaluator based on a Keras neural network. 

The aim is to give a score to a drum midi file. 
The dataset contains randoms generated midi files and reals midi files, truncated to 2 bars. 
The rest of the dataset are interpolations from a random file to a real file. 
Interpolated midi files are generated with a VAE.


The model is currently very basic and should be updated soon to a better model (RNN will be the first).


