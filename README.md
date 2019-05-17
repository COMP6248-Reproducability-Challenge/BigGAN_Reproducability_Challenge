# BigGAN_Reproducability_Challenge

- Paper: [Large Scale GAN Training for High Fidelity Natural Image Synthesis](https://openreview.net/forum?id=B1xsqj09Fm)



## Dataset

Anime avatars, see `data.zip`.

## Usage

- Unzip the data, follow the structure path `/BigGAN-PyTorch/data/ImageNet/face-small/...`
- Run the `dl_cw.ipynb`, don't run the downloading data cell if you have already unzipped the data in your own.
- The weights will be saved to `weights` folder.
- If you want to change the batch size (we use 20 in this repo), and epoch (10 in this repo) or any other parameters, go check the `scripts/lauch_BigGAN_bs256x8.sh` and `scripts/sample_BigGAN_bs256x8.sh`
- Pay attention to the structure of the files.