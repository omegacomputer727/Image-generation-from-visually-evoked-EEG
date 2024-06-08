This repository includes notebooks used to build and train an end to end model for generation of images from visually evoked EEG signals.
The notebooks include the following:
1. Code to design, train and test various EEG encoder architectures to extract meaningful(discriminative) representations from EEG.(EEG_encoder_training_and_testing.ipynb)
2. Code to pre-train a VAE in a self-supervised manner.(VAE_Pretraining.ipynb)
3. Code to combine the EEG encoder and the decoder of the pre-trained VAE, and fine-tune the combined model on EEG-image pairs.(Image_generation_finetune.ipynb)
