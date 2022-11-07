# A Unified Analysis of Mixed Sample Data Augmentation: A Loss Function Perspective (NeurIPS'22) 

[[Paper]](https://neurips.cc/virtual/2022/poster/55229) [[arXiv]](https://arxiv.org/abs/2208.09913) [[Notebook]](hmix-gmix.ipynb)

by [Chanwoo Park](https://chanwoo-park-official.github.io/)<sup>\*</sup> (MIT), [Sangdoo Yun](https://sangdooyun.github.io/)<sup>\*</sup> (Naver AI Lab), [Sanghyuk Chun](https://sanghyukchun.github.io/home/) (Naver AI Lab)


![msda_mask](data/msda_mask.png)


## Usage

### Implementation
- Our implementation is based on [`timm's mixup.py`](https://github.com/rwightman/pytorch-image-models/blob/main/timm/data/mixup.py).
- Check out our HMix implementation in [here](mixup.py#L103) and [here](mixup.py#L264).
- Check out our GMix implementation in [here](mixup.py#L123) and [here](mixup.py#L277).


## Visualization
- Check out our notebook [`hmix-gmix.ipynb`](hmix-gmix.ipynb) to visualize examples. 


## License
```
HMix-GMix
Copyright (c) 2022-present NAVER Corp.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.  IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
