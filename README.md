## VoxConverse speaker diarisation dataset

VoxConverse is an audio-visual diarisation dataset consisting of multispeaker clips of human speech, extracted from YouTube videos.
Updates and additional information about the dataset can be found at our [website](http://www.robots.ox.ac.uk/~vgg/data/voxconverse/index.html).


### Version 0.3
We have recently detected an error in some of our test rttm files. They are fixed in this master branch. Please use the 0.3 version for more accurate labels.

### Version 0.2
If you want to see the previous version, please go to the ver0.2 branch in this repository.

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
  booktitle={Interspeech},
  year={2020}
}
```

#### License

The VoxConverse dataset is available to download for research purposes under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0). The copyright remains with the original owners of the video. 

In order to obtain videos with a large amount of overlapping speech, we used data consisting of political debates and news segments. The views and opinions expressed by speakers in the dataset are those of the individual speakers and do not necessarily reflect positions of the University of Oxford, Naver Corporation, or the authors of the paper.

We would also like to note that the distribution of identities in this dataset may not be representative the global human population. Please be careful of unintended societal, gender, racial, linguistic and other biases when training or deploying models trained on this data.

