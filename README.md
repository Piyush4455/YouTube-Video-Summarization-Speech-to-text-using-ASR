# YouTube-Video-Summarization-Speech-to-text-using-ASR
YouTube Video Summarizer is a Python project that aims to provide a convenient way to summarize the content of YouTube videos by converting their audio into text. The project utilizes automatic speech recognition (ASR) techniques, fine-tuned models, and audio processing to generate concise summaries of the video's content.

## Features ##
* Downloads YouTube videos and extracts the audio.
* Converts audio format from .mp4 to .wav for further processing.
* Uses a popular fine-tuned CTC model, "jonatasgrosman/wav2vec2-large-xlsr-53-english," for English speech recognition.
* Audio chunking: Splits the audio into smaller segments of 30 seconds each for efficient processing.
* Summarizes the audio transcript using pipeline techniques for a concise summary.
* Provides the summarized text as the output.

## Installation ##
1. Clone the repository:
```git clone https://github.com/Piyush4455/YouTube-Video-Summarization-Speech-to-text-using-ASR.git
```
2. Change to the project directory:
```cd YouTube-Video-Summarization-Speech-to-text-using-ASR
```
3. Install the required dependencies:
```pip install -r requirements.txt
```

## USAGE ##
1.Run the YouTube_Video_Summarizer_Speech_to_Text_ASR.ipynb notebook.
2.Replace `video_link` with the URL of the YouTube video you want to summarize.
3.It will download the video, convert the audio to .wav format, perform automatic speech recognition (ASR) using the fine-tuned model, chunk the audio, and generate a summarized transcript.
4.The summarized text will be displayed.

