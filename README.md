# recsperts-transcripts
Transcripts for Episodes of my Podcast "Recsperts - Recommender Systems Experts"

Repository for code and output of episode transcription

## How To

1. Upload episode mp3-file to Google Drive Recsperts' audio folder
2. Start this Notebook in Colab and choose GPU as runtime type
3. Adapt filename for episode file
4. Run the transcription with whisper
5. Save pickle file to the Recsperts transcripts folder as `${episode_name}_raw.pkl`
6. Run postprocessing to generate `${episode_name}.txt`
7. Add, commit and push to git repository: https://github.com/mkurovski/recsperts-transcripts
8. Upload to transistor (use API for this): https://developers.transistor.fm/

## References

Model size that is used for transcriptions: `small.en`.
For more info, check out https://github.com/openai/whisper

