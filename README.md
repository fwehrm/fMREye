# fMREye
## About the project
Eye movements are closely connected to memory. One particularly interesting example of this relationship is refixation, where our gaze returns to a location that we have already looked at. Previous research suggests that these revisits may support memory formation and that the hippocampus, a brain region central to memory, could play an important role in guiding them.

In my Master’s thesis, I investigated how refixations relate to long-term memory formation and hippocampal activity. The project combined eye-tracking, fMRI, and behavioral memory data from participants performing a subsequent memory task.

## What I looked at
The analyses focused on three main questions:
1) Are people who make more refixations better at remembering what they saw?
2) Does hippocampal activity increase with the number of refixations during memory encoding?
3) Does functional connectivity between the hippocampus and other brain regions change during successful memory formation?

## What’s in this repository?
This repository contains selected Python code from the analysis pipeline, including:
- identification of refixations
- behavioral memory analyses
- whole-brain and ROI activation analyses
- parametric modulation analyses
- psychophysiological interaction (PPI) analyses

The code has been cleaned up for publication and is intended primarily as an overview of the analyses rather than a fully reproducible version of the original project.

## Tools
The analyses were mainly performed in Python using packages such as nilearn, numpy, and pandas. Additional preprocessing and parts of the original fMRI workflow were performed using SPM and MATLAB.

## Data
No participant data are included in this repository.

## Results
This repository is not intended to present or discuss the results in detail, but I wanted to include a couple of figures to give a visual impression of the project.

<p align="center">
  <img width="600" alt="github_panel" src="https://github.com/user-attachments/assets/d6ee931b-ad17-4cff-af9c-b7130966bdf9" />
</p>

<p align="center">
  <img width="600" alt="github_aa png" src="https://github.com/user-attachments/assets/58dc5f92-0eb6-444b-9be5-a85429320119" />
</p>

## Acknowledgments
Special thanks to Luise for saving me from what was rapidly turning into psychological crisis - I'm forever in your debt. Also, a big thank you to everyone at the Wagner Lab for supporting me throughout my thesis. Finally, I'd like to thank the University of Vienna for funding the project!
