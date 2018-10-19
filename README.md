# Transcribing-Long-Phone-Calls-With-Speaker-Diarization-on-Google-Cloud-Speech-To-Text
  This code is implementation for connverting audio in .wav files to text using the Google Cloud Speech to Text API.
  
  There was no direct code available on Google Cloud Speech To Text Documentation for transcribing long phone calls with speaker diarization enabled. 
  
 # Working with Code
 1) Clone the repository.
  
  ``` git clone https://github.com/ChiragSehra/Transcribing-Long-Phone-Calls-With-Speaker-Diarization-on-Google-Cloud-Speech-To-Text.git```
 
 2) Following the Google Cloud Speech To Text Documentation, you can download the credentials json file: 
 https://cloud.google.com/speech-to-text/docs/reference/libraries
 
 3) Add your path of JSON file in the code at line 7.
 
 4) Google allows to transribe audios of length less than 1 minute from your local computer. For transribing longer audios, you have to       upload your audio files to a bucket on google cloud storage. For this, learn to create a bucket here: https://cloud.google.com/storage/docs/creating-buckets
 
 5) Run the code as :

  ```python .\speaker_diarization.py gs://bucketname/audio_file.wav```
 
 6) Thank me later.
