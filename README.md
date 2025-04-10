🎨 Anime Faces Generation with GANs

Generating high-quality anime faces using Deep Convolutional GAN (DCGAN), Wasserstein GAN (WGAN), Wasserstein GAN with Gradient Penalty (WGAN-GP)

📝 Project Overview

This project explores three GAN architectures for generating anime faces:

    DCGAN (Baseline)

    WGAN ( Improved stability + overall better / faster learning )

    WGAN-GP # TO DO

Key features:

    🖼️ 10,000+ anime faces trained from scratch.

    📊 Frechet Inception Distance (FID) for quantitative evaluation.

    📈 Loss curves and sample evolution logged every epoch.

Training

    Dataset: Anime Faces (64x64 RGB).

    FID Calculation: Evaluated every 10 epochs.

    Trained for 50 epochs

📂 Repository Structure:

    ├── data/                  # Raw anime faces dataset
    ├── DCGAN/                 # DCGAN implementation
        ├── samples/               # Generated images per epoch
        ├── generated_fid_samples/ # Images for FID calculation
    ├── WGAN/                 # WGAN implementation
        ├── samples/               # Generated images per epoch
        ├── generated_fid_samples/ # Images for FID calculation
    └── README.md

Links to papers I have used for this project:

    DCGAN Paper: https://arxiv.org/abs/1511.06434

    WGAN Paper: https://arxiv.org/abs/1701.07875

    WGAN-GP Paper: https://arxiv.org/abs/1704.00028
