# Mining Review

##  Identifying mining related objects in films

## Short summary
The investigation aimed to assess how we can incorporate contextual information and metadata into the application of multi-modal large language models to the identification and classification of objects on film, and for the creation of detail-rich metadata for individual shots and stills.  

## Aims and objectives

The investigation incorporated a variety of sources held by the BFI, such as its catalogue metadata, Screenonline descriptions of episodes, digital files of the films, texts written by curators, and archival materials (digitised as part of the investigation). The investigation also tested the potential of ffmpeg and pyScenedetect to automatically identify shot changes for the easier extraction of key scenes from the films. In addition, it tested both LLaVA and Gemini multimodal language models to understand the how contextual information and metadata can be incorporated into prompts.


## People 

**Daniel Belteki** : Conceptualization, Data Curation, Formal Analysis, Investigation, Writing 

**Stephen McConnechie**: Conceptualization, Data Curation, Formal Analysis, Investigation, Writing

**Patrick Russell** : Conceptualization, Investigation, Writing

**Tim Boon** : Conceptualization, Investigation, Writing

**Alex Butterworth** : Conceptualization



## Data
The project employed the datasets below:
#### BFI archival materials
Digitised and OCR captured version of archival materials related to the production of selected Mining Review episodes.

#### Mining Review episodes
Digitised versions of a selection of Mining Review films.

#### BFI catalogue metadata and Screenonline descriptions
BFI catalogue metadata related to the Mining Review episodes, and descriptions of individual mining review episodes available on BFI's screenonline. 


## Outputs
1) Digitisation of BFI archival materials related to the production of three Mining Review episodes,

2) Audio transcriptions of digitised Mining Review episodes with Whisper (by OpenAI),

3) Named Entity Recognition analysis (with spaCy) of audio transcriptions,

4) Collaborative prompt-writing workshops,

5) Prompts designed for Gemini for breaking down digitised films into visual components for metadata integration,

6) Visual outputs of shot boundary detection tools (ffmpeg and PySceneDetect).

7)	As part of the preparation for the work, the investigation also collected a series of images from online and historical sources that depict domestic appliances. These are planned to serve as the basis for any future training work and/or for testing the engine.


## Licence 
This work is licensed under a [Creative Commons Attribution 4.0 License - CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
