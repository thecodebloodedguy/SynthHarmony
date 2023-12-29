# SynthHarmony 
## _AI Lip Sync Editor_
A modified version of the Wav2Lip by [![Github](https://svgshare.com/i/11NL.svg)](https://github.com/Rudrabha/Wav2Lip)

- Creates a convolutional layer of lipsync of a provided raw audio and a face shown in provided image.
- Input is provided as Video or Image and Audio file
- Wav2Lip's Pretrained model and its architecture is used to provide the lipsync layer.


## How to Install?

- Clone the code to a local directory from [![Github](https://svgshare.com/i/11NL.svg)](https://github.com/thecodebloodedguy/SynthHarmony)
- Install the 'requirements.txt' 
- Download the model from [Wav2Lip](https://iiitaphyd-my.sharepoint.com/personal/radrabha_m_research_iiit_ac_in/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fradrabha%5Fm%5Fresearch%5Fiiit%5Fac%5Fin%2FDocuments%2FWav2Lip%5FModels%2Fwav2lip%2Epth&parent=%2Fpersonal%2Fradrabha%5Fm%5Fresearch%5Fiiit%5Fac%5Fin%2FDocuments%2FWav2Lip%5FModels&ga=1) or [Wav2Lip-GAN](https://iiitaphyd-my.sharepoint.com/personal/radrabha_m_research_iiit_ac_in/_layouts/15/onedrive.aspx?id=%2Fpersonal%2Fradrabha%5Fm%5Fresearch%5Fiiit%5Fac%5Fin%2FDocuments%2FWav2Lip%5FModels%2Fwav2lip%5Fgan%2Epth&parent=%2Fpersonal%2Fradrabha%5Fm%5Fresearch%5Fiiit%5Fac%5Fin%2FDocuments%2FWav2Lip%5FModels&ga=1)
- Download [Face Detection Model](https://www.adrianbulat.com/downloads/python-fan/s3fd-619a316812.pth) and save it to 'face_detection/detection/sfd/'.

## How to Use?

### Using the terminal:
- Open Terminal and run command
```
python infer.py --checkpoint_path <ckpt> --face <video.mp4> --audio <audio.wav> 
```
- File will be saved in results directory

## Disclaimer: 
- A GPU is required for higher quality or longer videos.
- Processing on CPUs can be time consuming.
- GAN version is slower but haves better quality.
- Non GAN version is better at Lip Syncing but quality losses maybe seen.
