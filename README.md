# Speech_opensource
## VAD:
I. Open Source
1. [webrtc](https://github.com/wiseman/py-webrtcvad)
2. [silero](https://github.com/snakers4/silero-vad)
3. 
## Speech Enhancement
### I. Open Source:
1. [CleanUnet](https://github.com/NVIDIA/CleanUNet/tree/main)
2. [DeepFilterNet](https://github.com/Rikorose/DeepFilterNet/tree/main): A Low Complexity Speech Enhancement Framework for Full-Band Audio (48kHz) using on Deep Filtering.
3. 
### II. Metric
1. [STOI](https://github.com/mpariente/pystoi): <br>
- Short-Time Objective Intelligibility Measure: is calculated by comparing the short-term power spectra of the noisy speech and the clean speech. <br>
- The correlation between the two spectra is then used to calculate the STOI score. <br>
- It is based on the idea that intelligibility can be measured by the correlation between the noisy speech and the clean speech.
- Higher STOI scores indicate better intelligibility.
2. [PESQ](https://github.com/ludlows/PESQ): <br>
- Perceptual Evaluation of Speech Quality is calculated by comparing the noisy speech and the clean speech using a listening test. <br>
- The results of the listening test are then used to calculate the PESQ score. <br>
- It is based on the idea that speech quality can be measured by how well the listener can understand the speech and how pleasant it sounds.  <br>
- Higher PESQ scores indicate better quality.
3. 
## TTS
### I. Open Source
1. [VITS Fast Fine-tuning](https://github.com/Plachtaa/VITS-fast-fine-tuning/tree/main)
2. [NaturalSpeech](https://github.com/heatz123/naturalspeech/tree/main) - [Demo](https://github.com/heatz123/naturalspeech/wiki) - [Paper](https://arxiv.org/pdf/2205.04421.pdf)
3. [NaturalSpeech2](https://github.com/lucidrains/naturalspeech2-pytorch/tree/main) - [Demo](https://speechresearch.github.io/naturalspeech2/) - [Paper](https://arxiv.org/pdf/2304.09116.pdf)
4. [Efficient Speech](https://github.com/roatienza/efficientspeech): An On-Device Text to Speech Model
5. 
### II. Metric
1. [NISQA](https://github.com/gabrielmittag/NISQA):
MOS - Mean Opinion Score
2. [MCD](https://github.com/MattShannon/mcd):
- Mel cepstral distortion (MCD) is a measure of how different two sequences of mel cepstra are.
- The smaller the MCD between synthesized and natural mel cepstral sequences, the closer the synthetic speech is to reproducing natural speech.
3. 

## Audio Generation
### I. Open Source
1. [Auffusion](https://github.com/happylittlecat2333/Auffusion): Leveraging the Power of Diffusion and Large Language Models for Text-to-Audio Generation
2. 
### II. Metric
1. [Audioldm](https://github.com/haoheliu/audioldm_eval): 
2. [Torch-fidelity](https://github.com/toshas/torch-fidelity)
