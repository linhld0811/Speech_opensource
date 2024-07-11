# Speech_opensource
## [VAD](vad.md)
## Speech Enhancement
### I. Open Source:
1. [CleanUnet](https://github.com/NVIDIA/CleanUNet/tree/main)
2. [DeepFilterNet](https://github.com/Rikorose/DeepFilterNet/tree/main): A Low Complexity Speech Enhancement Framework for Full-Band Audio (48kHz) using on Deep Filtering.
3. [Voicefixer](https://github.com/haoheliu/voicefixer): restore human speech regardless how serious its degraded. It can handle noise, reveberation, low resolution (2kHz~44.1kHz) and clipping (0.1-1.0 threshold) effect within one model.
4. 
### II. Metric
1. [STOI](https://github.com/mpariente/pystoi):<br>

<details><summary>Descriptions</summary> 

- Short-Time Objective Intelligibility Measure: is calculated by comparing the short-term power spectra of the noisy speech and the clean speech. <br>
- The correlation between the two spectra is then used to calculate the STOI score. <br>
- It is based on the idea that intelligibility can be measured by the correlation between the noisy speech and the clean speech.
- Higher STOI scores indicate better intelligibility.<br>

</details>

2. [PESQ](https://github.com/ludlows/PESQ):<br>

<details><summary>Descriptions</summary> 
  
  - Perceptual Evaluation of Speech Quality is calculated by comparing the noisy speech and the clean speech using a listening test. <br>
  - The results of the listening test are then used to calculate the PESQ score. <br>
  - It is based on the idea that speech quality can be measured by how well the listener can understand the speech and how pleasant it sounds. <br>
  - Higher PESQ scores indicate better quality.<br>
  
</details>

3. 
## TTS
### I. Open Source
1. [VITS Fast Fine-tuning](https://github.com/Plachtaa/VITS-fast-fine-tuning/tree/main)
2. [NaturalSpeech](https://github.com/heatz123/naturalspeech/tree/main) - [Demo](https://github.com/heatz123/naturalspeech/wiki) - [Paper](https://arxiv.org/pdf/2205.04421.pdf)
3. [NaturalSpeech2](https://github.com/lucidrains/naturalspeech2-pytorch/tree/main) - [Demo](https://speechresearch.github.io/naturalspeech2/) - [Paper](https://arxiv.org/pdf/2304.09116.pdf)
4. [Efficient Speech](https://github.com/roatienza/efficientspeech): An On-Device Text to Speech Model
5. [StyleTTS](https://github.com/yl4579/StyleTTS) - [Paper](https://arxiv.org/pdf/2205.15439.pdf) - [Demo](https://styletts.github.io/)
6. [EmotiVoice](https://github.com/netease-youdao/EmotiVoice)
### II. Metric
1. [NISQA](https://github.com/gabrielmittag/NISQA):
MOS - Mean Opinion Score
2. [MCD](https://github.com/MattShannon/mcd):
- Mel cepstral distortion (MCD) is a measure of how different two sequences of mel cepstra are.
- The smaller the MCD between synthesized and natural mel cepstral sequences, the closer the synthetic speech is to reproducing natural speech.
3. 
## Zero-Shot TTS
### I. Open Source
1. [Vall-e](https://github.com/lifeiteng/vall-e) (for training); [Vall-E-X](https://github.com/Plachtaa/VALL-E-X)
2. [OpenVoice](https://github.com/myshell-ai/OpenVoice)
## Audio Encode
### I. Open Source
1. [Vector Quantization](https://github.com/lucidrains/vector-quantize-pytorch)
2. [AudioLM](https://github.com/lucidrains/audiolm-pytorch): 
3. [SoundStream](https://arxiv.org/pdf/2107.03312.pdf)(2021): An End-to-End Neural Audio Codec
4. [Encodec](https://github.com/facebookresearch/encodec): High Fidelity Neural Audio Compression
5. 
## [Vocoder](vocoder.md)
## Audio Generation
### I. Open Source
1. [Auffusion](https://github.com/happylittlecat2333/Auffusion): Leveraging the Power of Diffusion and Large Language Models for Text-to-Audio Generation
2. [Bark](https://github.com/suno-ai/bark): transformer-based text-to-audio model. Bark can generate highly realistic, multilingual speech as well as other audio - including music, background noise and simple sound effects. The model can also produce nonverbal communications like laughing, sighing and crying.
### II. Metric
1. [Audioldm](https://github.com/haoheliu/audioldm_eval): 
2. [Torch-fidelity](https://github.com/toshas/torch-fidelity)
## Pitch 
1. [Crepe](https://github.com/maxrmorrison/torchcrepe): Crepe: A Convolutional Representation for Pitch Estimation
