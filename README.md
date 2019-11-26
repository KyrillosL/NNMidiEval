# NNMidiEval - Only for a presentation purpose
Simple midi file evaluator based on a Keras neural network. 

The aim is to give a score for a drum midi file. The dataset contains random generated midi files and real midi files, truncated to 2 bars. 
The rest of the dataset are interpolations from a random file to a real file. 
Interpolated midi files are generated with a VAE.


The model is currently very basic and should be updated soon to a better model (RNN will be the first).


