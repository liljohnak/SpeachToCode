This may be useful for anyone who wants to write arcpy python code with their voice.
Steps:
1. Get a developer API key from OpenAI
2. 
   1. Right click `My Computer`>>Click Properties
   2. Properties Window>>Click Set the environment variables
   3. Environment Variables Window>>Click the New button under variables
   4. Name it `OPENAI_API_KEY2` and set the value to the key OpenAI has given you, then click Ok.
3. Run `python speachToCode.py`
4. The Whisper AI understanding is saved as an audio here: `%USERPROFILE%\Documents\Sound recordings`, and arcpy python code is generated in the response. 