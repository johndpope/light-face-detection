# API REFERENCES

## Base APIs
- fastface.list_pretrained_models
- fastface.download_pretrained_model
- fastface.list_archs
- fastface.list_arch_configs
- fastface.get_arch_config

## Module APIs
- fastface.module.build
- fastface.module.from_pretrained
- fastface.module.from_checkpoint

## Metric APIs
- fastface.metric.get_metric_by_name
- fastface.metric.list_metrics
- fastface.metric.WiderFaceAP

## Loss APIs
- fastface.loss.get_loss_by_name
- fastface.loss.list_losses
- fastface.loss.BinaryCrossEntropy
- fastface.loss.L2Loss

## Transform APIs
- fastface.transform.Interpolate
- fastface.transform.Padding
- fastface.transform.FaceDiscarder
- fastface.transform.ToTensor
- fastface.transform.Normalize
- fastface.transform.LFFDRandomSample
- fastface.transform.RandomHorizontalFlip
- fastface.transform.Compose

## Dataset APIs
- fastface.dataset.WiderFaceDataset

## Datamodule APIs
- fastface.datamodule.WiderFaceDataModule