# YouTube-Transcript-Summarizer
Built a simple chrome extension that uses hugging-face Transformers to summarise a YouTube video by utilising YouTube's transcript feature in 200 words.

## Requirements
- The following python modules must be installed to run the API
  - ```flask```
  - ```youtube-transcript-api```
  - ```transformers```

## Setuup
- Run ```app.py``` to start the summarizer API.
- Load the custom extension into any Chromium browser.
- Go to any YouTube video and click on the extension logo to start summarizing.
