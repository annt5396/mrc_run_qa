---
license: cc-by-nc-4.0
tags:
- generated_from_trainer
datasets:
- load_data
model-index:
- name: annt
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# annt

This model is a fine-tuned version of [nguyenvulebinh/vi-mrc-base](https://huggingface.co/nguyenvulebinh/vi-mrc-base) on the load_data dataset.

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 5e-05
- train_batch_size: 8
- eval_batch_size: 8
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 3.0

### Framework versions

- Transformers 4.26.0
- Pytorch 1.13.1
- Datasets 2.9.0
- Tokenizers 0.13.2
