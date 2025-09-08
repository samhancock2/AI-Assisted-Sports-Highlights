## Sports Highlight Generator

This short project automatically generates football match highlight reels by combining speech transcription (OpenAI Whisper), audio excitement levels, text analysis (NLP), and keyphrase matching.

The workflow extracts commentary from a full match recording, identifies exciting moments, and produces a highlight video.

Git LFS was used for the handling of NOR.mp4 and commentary.wav.

Project Structure:

data/         # raw + processed data
notebooks/    # Jupyter notebooks (transcription, highlight generation)
outputs/      # final highlight video

## Prerequisites
- Python 3.9+
- FFmpeg (must be installed and available in PATH)

Python dependencies can be found in requirements.txt 



