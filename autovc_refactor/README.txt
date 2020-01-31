This code is a refactored version for research purposes only. Please do not use it for commercial purposes or release it in any means.

We have included a small set of training audio files in the wav folder. However, the data is very small and is for code verification purpose only. Please prepare your own dataset for training.

Below are the steps to run the code.

Step 1. Generate spectrogram data from the wav files: 
python make_spect.py

Step 2. Generate training metadata, including the GE2E speaker embedding (please use one-hot embeddings if you are not doing zero-shot conversion):
python make_metadata.py 

Step 3. Run the main training script
python main.py 

Converges when loss is around 0.0001