# StainRestorer

High-Fidelity Document Stain Removal via A Large-Scale Real-World Dataset and A Memory-Augmented Transformer

<div>
<span class="author-block">
  Mingxian Li<sup> 👨‍💻‍ </sup>
</span>,
  <span class="author-block">
    Hao Sun<sup> 👨‍💻‍ </sup>
  </span>,
  <span class="author-block">
    Yingtie Lei<sup> 👨‍💻‍ </sup>
  </span>,
  <span class="author-block">
    <a href='https://zhangbaijin.github.io/'>Xiaofeng Zhang</a>
  </span>,
  <span class="author-block">
    Yihang Dong
  </span>,
  <span class="author-block">
    Yilin Zhou
  </span>,
  <span class="author-block">
    Zimeng Li
  </span>,
  <span class="author-block">
  <a href='https://cxh.netlify.app/'>Xuhang Chen</a><sup> 📮</sup>
</span>
  ( 👨‍💻‍ Equal contributions, 📮 Corresponding author)
</div>

<b>Huizhou Univeristy, University of Macau, Shanghai Jiao Tong University, SIAT CAS, Shenzhen Polytechnic University</b>

In <b>_IEEE/CVF Winter Conference on Applications of Computer Vision 2025 (WACV 2025)_</b>

# 🔮 Dataset

[Kaggle](https://www.kaggle.com/datasets/xuhangc/wacv2025-staindoc)

StainDoc is the first large-scale high-resolution dataset that includes ground truth data specifically for the task of document stain removal.

StainDoc_mark and StainDoc_seal are made with the process in [DocDiff](https://github.com/Royalvice/DocDiff).

# ⚙️ Usage

## Training
You may download the dataset first, and then specify TRAIN_DIR, VAL_DIR and SAVE_DIR in the section TRAINING in `config.yml`.

For single GPU training:
```
python train.py
```
For multiple GPUs training:
```
accelerate config
accelerate launch train.py
```
If you have difficulties with the usage of `accelerate`, please refer to <a href="https://github.com/huggingface/accelerate">Accelerate</a>.

## Inference

Please first specify TRAIN_DIR, VAL_DIR and SAVE_DIR in section TESTING in `config.yml`.

```bash
python infer.py
```

# Citation

```bib
```

