## VoxConverse speaker diarisation dataset

VoxConverse is an audio-visual diarisation dataset consisting of multispeaker clips of human speech, extracted from YouTube videos.
Updates and additional information about the dataset can be found at our [website](http://www.robots.ox.ac.uk/~vgg/data/voxconverse/index.html).

### Version 0.0.2
Please note that the number of wavfiles in test set are different from the number of test files in VoxSRC2020 challenge. There are 216 files on dev set and 232 files on test set.

#### Audio files

Dev set audio files can be downloaded from [here](https://www.robots.ox.ac.uk/~vgg/data/voxconverse/data/voxconverse_dev_wav.zip). 
Test set audio files can be downloaded from [here](https://www.robots.ox.ac.uk/~vgg/data/voxconverse/data/voxconverse_test_wav.zip)

#### Speaker Diarisation annotations 

Annotations are provided as Rich Transcription Time Marked (RTTM) files and can be found in the ```dev```  and ```test``` folder. 

#### Citation

Please cite the following if you make use of the dataset.

```
@article{chung2020spot,
  title={Spot the conversation: speaker diarisation in the wild},
  author={Chung, Joon Son and Huh, Jaesung and Nagrani, Arsha and Afouras, Triantafyllos and Zisserman, Andrew},
  journal={arXiv preprint arXiv:2007.01216},
  year={2020}
}
```

#### License

The VoxConverse dataset is available to download for research purposes under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0). The copyright remains with the original owners of the video. 

In order to obtain videos with a large amount of overlapping speech, we used data consisting of political debates and news segments. The views and opinions expressed by speakers in the dataset are those of the individual speakers and do not necessarily reflect positions of the University of Oxford, Naver Corporation, or the authors of the paper.

We would also like to note that the distribution of identities in this dataset may not be representative the global human population. Please be careful of unintended societal, gender, racial, linguistic and other biases when training or deploying models trained on this data.

