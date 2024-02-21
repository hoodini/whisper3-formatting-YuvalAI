# **OpenAI's Whisper 3 Transcriber + Subtitles Formatting by Yuval Avidani - יובל אבידני**

**Please support with Beer: [https://linktree.com/hackit.co.il](https://linktree.com/hackit.co.il)**

**IMPORTANT: V100/A100 GPU IS REQUIRED TO USE THIS NOTEBOOK! OTHERWISE, THE NOTEBOOK WILL CRASH AND WILL SHOW CUDA MEMORY ERROR MESSAGES**

*This notebook has the following capabilities:*

- Select between YouTube URL and Media Files Upload
- Select the language of the original language in the media file / YouTube URL
- YouTube Videos are downloaded and converted to MP3
- File size check is made to adhere to Whisper's file limit size of 25MB
- If the file is larger, the notebook uses Smart Chunking
- It then allows to select the subtitles formatting (how many rows and words in each one), transcribes each chunk and concatenate it all to one TXT / SRT file
- Optional: translate the TXT / SRT to another language
- The files can be downloaded using the last cell

**Instructions to Transcribe from YouTube / Media File:**

1. Run cells 1-2
2. Run cell 3 and note to choose your media source (YouTube URL / Upload Media File)
3. Select the formatting of the desired subtitles - number of rows and number of words per subtitle and then run cell 4
4. Run cell 5 to get transcription in SRT / TXT format
5. Run cell 6 to download SRT / TXT Note: the files can also be downloaded from the file explorer on the sidebar.

**Instructions to Transcribe from an existing SRT / TXT File:**

1. Run cells 1-2
2. Upload your TXT / SRT file by right-clicking with the mouse on the white area under 'files' in the tab and select 'upload' -> select your file
3. Run cell 6 and select your file, the target language, and click 'Translate'
4. After you'll see the 'Completed' text the files will be available to download from the sidebar directly
5. You can also run cell 7 and select your file and then 'Download' and it will download it

Note: the files can also be downloaded from the file explorer on the sidebar.

**Enjoy!**  
**Yuval Avidani**
