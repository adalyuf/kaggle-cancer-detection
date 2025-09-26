# Histopathologic cancer detection
Kaggle cancer detection.

Identifying cancer based on small patches of radiological imaging.  

We use the more modern libraries of timm and transformers to pull down pre-trained image classification models and fine tune them on the cancer dataset.

For this experiment we tested:
- resnet34
- repvit_m2
- convnextv2

These were tested in both training the whole model weights and fine-tuning just the classifier head.




