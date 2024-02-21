# **OpenAI's Whisper 3 transcriber + Subtitles Formatting by Yuval Avidani - יובל אבידני**

**Please support with Beer: [https://linktree.com/hackit.co.il](https://linktree.com/hackit.co.il)**

**IMPORTANT: V100/A100 GPU IS REQUIRED TO USE THIS NOTEBOOK! OTHERWISE, THE NOTEBOOK WILL CRASH AND WILL SHOW CUDA MEMORY ERROR MESSAGES**

This notebook has the following capabilities:

1. Select between YouTube URL and Media Files Upload
2. YouTube Videos are downloaded and converted to WAV
3. Uploaded media files are also being converted to WAV
4. File size check is made to adhere to Whisper's file limit size of 25MB
5. If the file is larger, the notebook uses Smart Chunking
6. It then transcribes each chunk and concatenates it all to one SRT / TXT file
7. The files can be downloaded using the last cell

**Instructions:**
1. Run cells 1-2
2. Run cell 3 and note to choose your media source (YouTube URL / Upload Media File)
3. Select the formatting of the desired subtitles - number of rows and number of words per subtitle and then run cell 4
4. Run cell 5 to get transcription in SRT / TXT format
5. Run cell 6 to download SRT / TXT
   Note: the files can also be downloaded from the file explorer on the sidebar.

Enjoy!
Yuval Avidani
יובל אבידני
Proud to be an Israeli!
Proud to be Jewish!
