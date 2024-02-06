# Fine-tuning-Vinallama-for-Elementary-math-solving

# experiments

This model is a fine-tuned version of [vilm/vinallama-7b-chat](https://huggingface.co/vilm/vinallama-7b-chat) on the None dataset.

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.0002
- train_batch_size: 1
- eval_batch_size: 8
- seed: 42
- gradient_accumulation_steps: 4
- total_train_batch_size: 4
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: cosine
- lr_scheduler_warmup_ratio: 0.05
- num_epochs: 1
- mixed_precision_training: Native AMP

### Training results



### Framework versions

- PEFT 0.7.2.dev0
- Transformers 4.38.0.dev0
- Pytorch 2.0.0
- Datasets 2.16.1
- Tokenizers 0.15.0
