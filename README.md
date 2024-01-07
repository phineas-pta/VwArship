# Faster Whisper + Silero VAD + DeepL

a fork of https://github.com/ANonEntity/WhisperWithVAD (DeepL integration for translation)

adapted to Faster-Whisper with built-in SileroVAD: https://github.com/guillaumekln/faster-whisper

for vocals extraction, replace `spleeter` with `demucs`, inspired from: https://github.com/EtienneAb3d/WhisperHallu

several enhancements for Japanese from somewhere on internet

## How to use

 - [![Open In Colab][colab-badge]][colab-notebook] to open the notebook in Google Colab.
 - Run the Setup Whisper cell.
 - Upload your input audio to either the runtime itself, Google Drive, or a file hosting service with direct download links.
 - Set the audio_path and language variables, and then run the Run Whisper cell. (Note: Audio path is set automatically if you use the Upload cell)
 - Once it's done, the notebook will automatically download the generated SRT file.

~~bonus: youtube version [![Open In Colab][colab-badge]][yt-notebook] inspired from https://github.com/ArthurFDLR/whisper-youtube~~ (currently not working)

[colab-badge]: <https://colab.research.google.com/assets/colab-badge.svg>
[colab-notebook]: <https://colab.research.google.com/github/phineas-pta/VwArship/blob/main/WhisperWithVAD.ipynb>
[yt-notebook]: <https://colab.research.google.com/github/phineas-pta/VwArship/blob/main/whisper_youtube.ipynb>
