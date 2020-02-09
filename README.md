# Fallout4-Voice-Generator
This Project Aims to use deep learning and generative modelling to allow FO4 modders to create new NPC voices through interpolation.

#High Level Task List
- [ ] Extract fallout voices from game files
- [ ] Create Data Processing pipeline to transform voices 
- [ ] Learn Pytorch for model creation
- [ ] Create VAE Model and apply FO4 voices to it
- [ ] Asses VAE Latent Space through interpolation
- [ ] Explore the use of disentangled VAE's on voice data
- [ ] Explore comparisons between VAE's and GANs on this data
- [ ] Explore the idea of not just generating new voices but also generating new voices for spesfic words
- [ ] Explore the idea of not just generating new voices to spesfic words but also to spesfic emotional representations e.g Angry "The"

# Extract Fallout Voices
Use the Links to extract Bethesda game file:

Bethesda Archive extractor for ba and ba2 files: https://www.youtube.com/watch?v=hw8PFGjgxYc

Use Unfuzer to convert .fuz files to .wav audio files: https://www.nexusmods.com/skyrim/mods/9797/

# Data processing Pipelines


