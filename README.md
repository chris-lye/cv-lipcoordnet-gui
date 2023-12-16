## LipCoordNet

An computer vision project which is an enhancement of the LipNet Model (Yannis et al, 2016) used for translating lip movement into text. Built on top of prior work by @Fengdalu

## Instructions
Install pytorch (https://pytorch.org/get-started/locally/)
Install other dependencies
``` pip install -r requirements.txt ``` 
Run the app by: 
``` streamlit run app.py ``` 

Use the upload page to lipread an already recorded video.

Use the record page to record a video and proceed to generate the lip-read transcription. 

For best results, use sentence of the style found in the Grid Audio Visual Corpus.(e.g. "put red at G9 now")

### Dependencies
PyTorch 1.0+
opencv-python
face_alignment 

## License

The MIT License

# Acknowledgements
Dataset(s): The Grid Audio-Visual Speech Corpus https://zenodo.org/records/3625687
Built on the excellent work created by @Fengdalu https://github.com/VIPL-Audio-Visual-Speech-Understanding/LipNet-PyTorch

References:
Yannis M. Assael, Brendan Shillingford, Shimon Whiteson, and Nando de Freitas (2016) 'LipNet: End-to-End Sentence-level Lipreading' arXiv (https://arxiv.org/abs/1611.01599).
