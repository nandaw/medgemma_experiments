# medgemma_experiments

This repository contains my experiments fine tuning medgemma based on colab notebooks provided by Google. My main goal is to fine tune the original model into identifying mass or calcification on mammogram images.

At first I modified the 'quick_start_with_hugging_face' notebook in order to assess if medgemma could identify findings at mammograms. Then I used the CBIS-DDSM dataset to fine tune the model ('fine_tune_with_hugging_face') and check their answer at the 'testing_fine_tuned_model' when presented to images from the web.

Obs: O github não está renderizando corretamente os notebooks eles podem ser visualizados e executados no Google Colab nos seguintes links:
[Quick Start with Hugging Face](https://colab.research.google.com/github/nandaw/medgemma_experiments/blob/main/notebooks/quick_start_with_hugging_face.ipynb)
[Fine Tune with Hugging Face](https://colab.research.google.com/github/nandaw/medgemma_experiments/blob/main/notebooks/fine_tune_with_hugging_face.ipynb)
[Testing Fine Tuned Model](https://colab.research.google.com/github/nandaw/medgemma_experiments/blob/main/notebooks/testing_fine_tuned_model.ipynb)
