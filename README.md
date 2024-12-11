# An Audio-Ultrasound Synchronized Tongue Movement Database for Mandarin speech 

## Introduction


*  The AUSpeech dataset is a  multimodal database designed to advance research in Mandarin speech production. It includes synchronized ultrasound tongue imaging (UTI), audio recordings, and text annotations, supporting research in linguistics, speech recognition, and clinical applications etc.

*  The dataset  contributions from 54 participants, including 43 healthy individuals and 11 patients with dysarthria. The total dataset size is approximately 700 GB.



![image](https://github.com/huanraozhineng1/AUSpeech_code/blob/master/Figure/fig1.png)

## Data Structure 
*  Audio Data: Stored in .wav format (16 kHz sampling rate, mono-channel).
*  Ultrasound Imaging Data: Stored in .dcm format.
*  Text Annotations: Stored in .lab and .TextGrid formats for precise alignment.

## Other Technical Validation

The alignment using the [MFA](https://github.com/MontrealCorpusTools/Montreal-Forced-Aligner) on the normal subject data, followed by manual labeling checks for verification. For the patient data, we employ manual annotation for audio pronunciation labeling to ensure accuracy.
## Citation

If you use our dataset, please consider citing:
```
@article{yang2024Auspeech,
  title={An Audio-Ultrasound Synchronized Tongue Movement Database for Mandarin speech},
  author={Yudong, Yang and Rongfeng, Su and Shaofeng, Zhao and Jianguo, Wei and Manwa.Lawrence, Ng and Nan, Yan and Lan, Wang},
}
```