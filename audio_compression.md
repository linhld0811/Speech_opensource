1. [Encodec](https://github.com/facebookresearch/encodec) - [paper](https://arxiv.org/pdf/2210.13438) - [24/10/2022]:
Sample rate: 24kHz & 48kHz at 24kbps
Reconstruction Loss:
  - Time domain: L1 (target audio; compressed audio)
  - Frequency domain: L1; L2 of mel-spectrogram using several time scales
Discriminator Loss: MS-STFT
Feature matching loss
VQ commitment loss
2. [Opus](https://en.wikipedia.org/wiki/Opus_(audio_format)):
Opus supports constant and variable bitrate encoding from 6 kbit/s to 510 kbit/s (or up to 256 kbit/s per channel for multi-channel tracks),
frame sizes from 2.5 ms to 60 ms, and five sampling rates from 8 kHz (with 4 kHz bandwidth) to 48 kHz (with 20 kHz bandwidth,
the human hearing range).
3. [Enhanced Voice Services](https://en.wikipedia.org/wiki/Enhanced_Voice_Services):
It is a versatile codec operating at multiple bitrates, 5.9 kbps to 128 kbps
4. [Lyra](https://github.com/google/lyra) - [Paper](https://arxiv.org/pdf/2102.09660) - [18/2/2021] - Latest [21/12/2022]:
Features are extracted from speech every 20ms and are then compressed for transmission at a desired bitrate between 3.2kbps and 9.2kbps
5. [SoundStream](https://github.com/lucidrains/audiolm-pytorch) - [Paper](https://arxiv.org/pdf/2107.03312) - [7/7/2021]
- 24kHz at 6kbps
6. [Hifi-Codec](https://github.com/yangdongchao/AcademiCodec) - [Paper](https://arxiv.org/pdf/2305.02765) - [7/5/2023]
- Sample rate: 24kHz & 16kHz
7. [SpeechTokenizer](https://github.com/ZhangXInFD/SpeechTokenizer) - [paper](https://arxiv.org/pdf/2308.16692) - [31/08/2023]
8. [DAC](https://github.com/descriptinc/descript-audio-codec) - [Paper](https://arxiv.org/pdf/2306.06546) - [26/10/2023]
- RVQGAN
- Sample rate: 16kHz, 24kHz, 44.1kHz at 8kbps 
## References
1. [Hearing range](https://en.wikipedia.org/wiki/Hearing_range): The human range is commonly given as 20 to 20,000 Hz
2. [CBR](https://en.wikipedia.org/wiki/Constant_bitrate) and [VBR](https://en.wikipedia.org/wiki/Variable_bitrate)

## Repo
1. [MQTTS](https://github.com/b04901014/MQTTS) - [Paper](https://arxiv.org/pdf/2302.04215) [8/2/2023]
A Vector Quantized Approach for Text to Speech Synthesis on Real-World Spontaneous Speech.
2. [IMS-Toucan](https://github.com/DigitalPhonetics/IMS-Toucan):
Multilingual and Controllable Text-to-Speech Toolkit 
3. [MARS5-TTS](https://github.com/Camb-ai/MARS5-TTS)
4. 
