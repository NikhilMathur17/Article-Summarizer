# EY-GDS-hackathon
This projects aims to generate a text summary for audio, video and text files.
Uses Tkinter for UI ,Gensim for summarization, Speaker Recognition using Scikit learn GMM module and mfcc techniques.

Minutes of meeting problem prototype instructions for run :
1. This code is created in Jupyter Notebook 
2. Run command !pip install -r requirement.txt in command promt to install all the required libraries .
3. You also need to download ffmpeg in the computer from ffmpeg.org.
4. There is a need to change a path in AudioUpload function command = [r"your_path_for_ffmpeg.exe","-y","-i", filename, filename1].
