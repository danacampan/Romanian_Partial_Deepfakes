## Work Completed

- Started reading and taking notes on the **SPADE** paper.
- Selected **50 Romanian and 50 English recordings** from the Mozilla Common Voice datasets for the initial pilot.
- Ran the **base F5-TTS model** and tested speech generation using a recording of my own voice.
- Contacted the authors of **F5-TTS-RO** to request access to the Romanian voice generation model.

## Challenges and What Didn't Work

- **F5-TTS-RO availability:** The Romanian model was not yet publicly available, so I could not begin generating Romanian replacement words. The authors informed me that they plan to release it in the coming days and suggested using the English-Chinese F5-TTS model in the meantime.
- **Dataset preparation:** Although the 50 recordings for each language were selected, word-level alignment and synthetic word replacement have not yet been completed.
- **Speech generation:** The initial F5-TTS experiment was performed using my own voice. The model has not yet been tested on the selected English Common Voice recordings.

## Next Steps

- Continue the literature review with the remaining recommended papers.
- Generate English replacement words using F5-TTS.
- Investigate the **Montreal Forced Aligner (MFA)** Romanian bundle and begin aligning words in the genuine Romanian recordings.
- Test F5-TTS-RO once the model becomes available.
- Begin developing the audio splicing pipeline.
