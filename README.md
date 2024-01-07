# Persona

Tool for creating talking head videos using generative AI. Uses the following projects/libraries:

1. [Tortoise-TTS](https://github.com/neonbjb/tortoise-tts) - generating speech
2. [SDXL-Turbo](https://huggingface.co/stabilityai/sdxl-turbo) - generating the digital avatar image
3. [One-Shot Free-View Neural Talking Head Synthesis](https://github.com/zhanglonghao1992/One-Shot_Free-View_Neural_Talking_Head_Synthesis) - animating the face
4. [Wav2Lip](https://github.com/Rudrabha/Wav2Lip) - using speech to generate lip movement and superimposing it on the animated face
5. [Real ESRGAN](https://github.com/ai-forever/Real-ESRGAN) - improving the image and scaling it

# Setup

```Bash
$ git clone https://github.com/sarumaj/persona.git
$ cd persona
$ pip install -r requirements.txt
```

<!--- https://iiitaphyd-my.sharepoint.com/:u:/g/personal/radrabha_m_research_iiit_ac_in/EdjI7bZlgApMqsVoEUUXpLsBxqXbn5z8VTmoxp55YNDcIA?e=n9ljGW -->

1. Download [Way2Lib weights](https://1drv.ms/u/s!AryV_R9880sVgqF9hRIQXLFDOhHBhw?e=ZKUWMa) and put them in the `wav2lip` directory

<!--- https://www.adrianbulat.com/downloads/python-fan/s3fd-619a316812.pth -->

2. Download [Face detection weights](https://1drv.ms/u/s!AryV_R9880sVgqF8HHMzPCRoWLlPMg?e=zZc3Yt) and place them in the directory `wave2lip/face_detection/detection/sfd/s3fd.pth`

<!--- https://drive.google.com/drive/folders/16PlVKhTNkSyWFx52RPb2hXPIQveNGbxS -->

3. Create a folder a folder `weights` and place the [Real-ESRGAN weight](https://1drv.ms/f/s!AryV_R9880sVgqF-Y2Q3AzImizcmag?e=2YeKtJ) files in there

# Examples

## Santa Claus Christmas Greetings

https://github.com/sausheong/persona/assets/5962/2d60798f-e877-46b1-90a0-afa864dab50e

## Chinese New Year Greetings

https://github.com/sausheong/persona/assets/5962/31ae4da6-3739-49aa-b4a7-5d20e6759795

## NORAD Tracking Santa

https://github.com/sausheong/persona/assets/5962/c400edfd-7316-4d07-998f-9b94bf5c64af

## Taking photos and videos

https://github.com/sausheong/persona/assets/5962/1862f202-ec10-40e2-9ebc-83652945924e

## Apple closing its Infinite Loop retail store

https://github.com/sausheong/persona/assets/5962/575667e5-7946-4fd7-9eae-1192e79f7392

## Apple closing its Infinite Loop retail store (2)

https://github.com/sausheong/persona/assets/5962/68018299-a458-4f9f-8fa3-9640f910dfaf
