# An Audio-Ultrasound Synchronized Tongue Movement Database for Mandarin speech 

## Introduction


*  The AUSpeech dataset is a  multimodal database designed to advance research in Mandarin speech production. It includes synchronized ultrasound tongue imaging (UTI), audio recordings, and text annotations, supporting research in linguistics, speech recognition, and clinical applications etc.

*  The dataset  contributions from 54 participants, including 43 healthy individuals and 11 patients with dysarthria. The total dataset size is approximately 700 GB.



![image](https://github.com/huanraozhineng1/AUSpeech_code/Figure/fig1.png)

## Data Structure 
*  Audio Data: Stored in .wav format (16 kHz sampling rate, mono-channel).
*  Ultrasound Imaging Data: Stored in .dcm format.
*  Text Annotations: Stored in .lab and .TextGrid formats for precise alignment.

## Basic Information

Built upon [MFA](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner), five-fold cross-validation experiments are conducted during the establishment of the NasalSeg dataset. Please refer to [the paper](https://www.nature.com/articles/s41597-024-04176-1) for more details.


## Citation

If you use our dataset, please consider citing:
```
@article{yang2024Auspeech,
  title={An Audio-Ultrasound Synchronized Tongue Movement Database for Mandarin speech},
  author={Yudong, Yang and Rongfeng, Su and Shaofeng, Zhao and Jianguo, Wei and Manwa.Lawrence, Ng and Nan, Yan and Lan, Wang},
}
```