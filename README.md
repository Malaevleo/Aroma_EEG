# Aroma_EEG
*Project for Skoltech Neurocenter*

**Full version available here: https://colab.research.google.com/drive/1ln8PLRY4LyOPAOhXjCvgI4xjtd0hCCBF?usp=sharing**

**Presentation from the conference: https://docs.google.com/presentation/d/1cGXkIyrTi3Gm3t4nrVG68EoVzck6hK3MXnNNlH8pVCs/edit?usp=sharing**

# Concept

The idea was to replicate this paper:

*Xia, X., Liu, X., Zheng, W. et al. Recognition of odor and pleasantness based on olfactory EEG combined with functional brain network model. Int. J. Mach. Learn. & Cyber. 14, 2761–2776 (2023). https://doi.org/10.1007/s13042-023-01797-7*

But with our own data. The pipeline works like this:

![alt text](https://github.com/Malaevleo/Aroma_EEG/blob/main/PIPELINEEEG.png "The pipeline")

We had 20 respondents and each were provided 8 different odors multiple times with water serving as the control (additional 2 odors basically). 

# TMS-EEG

TMS-EEG file is from the separate project but it is here to show that EEGNET is overall well-suited for the EEG data analysis when the stimuli is really pronounced. When we have to deal with subtle signals it does not work as intended sadly. TMS notebook was also done on our own data. I actually was the respondent in that experiment, thus I analyzed my own brain. Surreal experience to say the least

