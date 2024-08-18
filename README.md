# Fine-tuning a Speech-to-Text Whisper model on Urdu language

This focuses on fine-tuning a pre-trained Whisper model for the Urdu language.
## Creating a conda environment

Its assumed that conda is already installed and nvidia gpu is available.

1. Install ffmpeg utility:

```bash
sudo apt update
sudo apt install ffmpeg
```

2. Create a new conda environment and activate it.

```bash
conda create -n speech-to-text python=3.11
conda activate speech-to-text
```

3. Install all the requirement:

```bash
pip install -r requirements.txt
```

4. Install transformers library from source.

```bash
git clone https://github.com/huggingface/transformers.git
cd transformers/
pip install -e .
cd ..
```

## Machine Learning

## References

- Made use of Whisper pre-trained model - sinhalese language.
- HuggingFace Audio Course - https://huggingface.co/learn/audio-course/en/chapter5/fine-tuning
