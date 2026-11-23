# Neural-Network-Methods

Feedforward Networks
Perceptron (1958) — single-layer binary classifier
Adaline (1960) — adaptive linear neuron with MSE loss
MLP (1986) — Multi-Layer Perceptron with backpropagation

Autoencoders
Autoencoder — compress-reconstruct unsupervised learning
Denoising Autoencoder — reconstruct from corrupted input
Variational Autoencoder (VAE) — probabilistic latent generative model

Energy-Based & Memory
Hopfield Network (1982) — associative memory via energy minimization
Boltzmann Machine (1985) — stochastic energy-based generative model
Restricted Boltzmann Machine (RBM) — no intra-layer connections
Deep Belief Network (DBN) — stacked RBMs for deep generative pretraining
Self-Organizing Map (SOM) — unsupervised topological clustering

Convolutional Networks
CNN / LeNet (1998) — first successful CNN for digits
AlexNet (2012) — deep CNN that won ImageNet 2012
VGG (2014) — stacks of 3×3 conv blocks
GoogLeNet / Inception (2014) — parallel multi-scale conv branches
ResNet (2015) — residual / skip connections
DenseNet (2017) — dense connectivity between layers
U-Net (2015) — encoder-decoder with skip connections for segmentation
YOLO (2016) — single-shot real-time object detection

Recurrent & Memory
RNN — recurrent hidden state for sequences
LSTM (1997) — gated memory cell, long-term dependencies
GRU (2014) — simplified LSTM with update/reset gates
Seq2Seq (2014) — encoder-decoder for sequence transduction
Attention (2014) — soft alignment over encoder hidden states

Transformer Family
Transformer (2017) — multi-head self-attention + FFN
BERT (2018) — masked LM + next sentence prediction
GPT (2018) — decoder-only autoregressive LM
T5 (2019) — text-to-text encoder-decoder
ViT (2020) — Vision Transformer, patches as tokens
CLIP (2021) — contrastive image-text pretraining

Generative Models
GAN (2014) — generator vs discriminator adversarial training
DCGAN (2015) — convolutional GAN with deconv generator
StyleGAN (2018) — style-based generator with AdaIN
Normalizing Flow — invertible transforms for exact likelihood
Diffusion Model (DDPM) (2020) — denoising score matching
Flow Matching (2022) — continuous-time flow objective

Graph Networks
GNN — message passing on graph-structured data
GraphSAGE — inductive neighbor sampling
GAT — attention-weighted neighbors

Modern Architectures
Mixture of Experts (MoE) — conditional computation via gating
Mamba (2023) — selective State Space Model
Diffusion LLM (2025) — discrete diffusion for text generation
