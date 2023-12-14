# Esoteric Llama 2 7B Fine Tunes

The full project report is the file "project report.pdf".

This repo contains chat conversations with the:
  1) Llama 2 7B chat model prior to fine tuning
  2) Llama 2 7B chat model after fine tuning
  3) Llama 2 7B base model after fine tuning

Each model was asked the same series of questions, which allows for a more direct comparison.

This repo also contains the notebook file that was used to fine tune both models. The first section of the notebook is dedicated the training loop, which ends with you being able to save the model to your Google Drive The second section allows you to load the fine tuned model and run inference with a prompt you can define. Both models were trained in a Google Colab on a single Nvidia V100.

### Useful Links:
  - Dataset: https://huggingface.co/datasets/teknium/trismegistus-project
  - Fine tuned chat model: https://huggingface.co/conormackey/llama-2-chat-ft
  - Fine tuned base model: https://huggingface.co/conormackey/llama-2-base-ft
