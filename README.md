# Synthetic Mulberry Leaf Disease Image Generation using WGAN-GP

Deep learning-based synthetic data generator for plant disease detection using 
Wasserstein GAN with Gradient Penalty, Spectral Normalization, and Self-Attention.

## Key Features
- WGAN-GP architecture with Spectral Normalization for stable training
- Self-Attention layers for capturing complex spatial patterns
- Exponential Moving Average (EMA) for improved generation quality
- Distributed training support with TensorFlow MirroredStrategy
- Automated checkpointing and FID score evaluation
- Generates 128×128 high-quality synthetic disease images

## Technologies
Python • TensorFlow • Keras • Computer Vision • GANs • Deep Learning

## Results
Successfully generated diverse synthetic mulberry leaf disease images from 131 
training samples, achieving stable training with GP reduction from 44.5 → 1.2
