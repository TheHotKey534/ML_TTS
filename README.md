# ML_TTS
## Dataset
* LJ_Speech dataset
* 13,000 samples
* Total time ~24 hours
## hf_tss.ipynb
* Platform for models training and work with dataset
* Using TrainerAPI

## pytorch_pretrained_tts.ipynb
* Tacotron2 model for TTS
* Already pretrained and fine-tuned

## stt_evaluation.ipynb
* OpenAI-Whisper STT (Speech-to-Text) model
* BLEU, F1, Precision and Recall evaluation metrics
* F1, Precision and Recall got from Levenshtein distance (number of modifications required to transform one string to another)

## Inferences
* hf_tts_inferences - SpeechT5 inferences
* pytorch_pretrained_inferences - Tacotron2 inferences
* cusom_TTS/samples - Inferences of model trained from scratch
