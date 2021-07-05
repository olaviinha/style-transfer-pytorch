# style-transfer-pytorch

This is a **modified version** of an implementation of neural style transfer ([A Neural Algorithm of Artistic Style](https://arxiv.org/abs/1508.06576)) in PyTorch, supporting CPUs and Nvidia GPUs.

## Modified as follows:

1. `--save_every` to a new file with current iteration number, rather than overwriting the same `--output` file.
2. Output messages muted.

See [the original repository](https://github.com/crowsonkb/style-transfer-pytorch) for details.
