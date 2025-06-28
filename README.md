# medgemma_experiments

This repository contains my experiments fine tuning medgemma based on colab notebooks provided by Google. My main goal is to fine tune the original model into identifying mass or calcification on mammogram images.

At first I modified the 'quick_start_with_hugging_face' notebook in order to assess if medgemma could identify findings at mammograms. Then I used the CBIS-DDSM dataset to fine tune the model ('fine_tune_with_hugging_face') and check their answer at the 'testing_fine_tuned_model' when presented to images from the web.
