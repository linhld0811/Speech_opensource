1. [FreeV](https://github.com/BakerBunker/FreeV) - [paper](https://arxiv.org/pdf/2406.08196) - [12/Jun/2024]:
    - Generator:
      * ASP: Pseudo-Inverse -> 1xConvNeXtv2
    - Loss: Same APNet2
2. [APNet2](https://github.com/redmist328/APNet2) - [paper](https://arxiv.org/pdf/2311.11545) - [20/Nov/2023]:
    - Generator:
      * ASP: 8xConvNeXtv2 -> Amplitude spectrum
      * PSP: 8xConvNeXtv2 -> Phase spectrum
      * ISTFT reconstruct the waveform
    - Loss:
      * Amplitude Spectrum Loss
      * Phase Spectrum Loss
      * Recontructed STFT Spectrum loss
      * MPD/MRD with Hinge GAN loss
      * Melspectrogram loss
3. [Vocos](https://github.com/gemelo-ai/vocos) - [paper](https://arxiv.org/pdf/2306.00814) - [1/Jun/2023]:
   - ConvNeXt block consists of a depth-wise convolution with a larger-thanusual kernel size
   - Loss:
     * Melspectrogram loss
     * Feature matching loss
     * MPD/MRD-based Hinge GAN loss
4. [APNet](https://github.com/YangAi520/APNet) - [paper](https://arxiv.org/pdf/2305.07952) - [13/May/2023]:
    - Generator:
      * amplitude spectra predictor (ASP): ResNet -> Amplitude spectrum
      * phase spectra predictor (PSP): Resnet -> Phase spectrum
      * ISTFT reconstruct the waveform
    - Loss:
      * Amplitude Spectrum Loss
      * Phase Spectrum Loss: Instantaneous Phase Loss, Group Delay Loss, Phase Time Difference Loss
      * Recontructed STFT Spectrum loss
      * MPD/MSD with Least Squares GAN loss
      * Melspectrogram loss
5. [iSTFTNet](https://github.com/rishikksh20/iSTFTNet-pytorch) - [paper](https://arxiv.org/pdf/2203.02395) - [4/Mar/2022]:
   - ResNet + upsampling -> phase + amplitude
   - Loss:
      * Melspectrogram loss
      * MPD/MSD with Least Squares GAN loss
6. [Hifigan](https://github.com/jik876/hifi-gan) - [paper](https://arxiv.org/pdf/2010.05646) - [23/Oct/2020]:
   - Generator: ConvTranspose + MRF (Multi-Receptive Field Fusion)
   - Discriminator:
     * multi-period discriminator (MPD) consisting of several sub-discriminators each handling a portion of periodic signals of input audio.
     * multi-scale discriminator (MSD)  capture consecutive patterns and long-term dependencies
   - Loss:
     * MPD/(MSD)-based least squares GAN losses
     * Mel-spectrogram loss
     * Feature matching loss
       

