# This repository is for demonstration of "Contrastive Learning for Vietnamese Abstractive Summarization" study

## Implementation
The implementation is based on the implementation of [BRIO system](https://github.com/yixinL7/BRIO). The source code is being refactored and will be published soon.

## To reproduce the result in the paper

| Models                             ||        WikiLingua        |||        Vietnews        ||
|------------------------------------|:----------:|:-----:|:-----:|:--------:|:-----:|:-----:|
|                                    |     R-1    |  R-2  |  R-L  |    R-1   |  R-2  |  R-L  |
| BARTpho (from the  original paper) |      -     |   -   |   -   |   60.88  | 29.90 | 39.64 |
| BARTpho  (baseline)                |    55.32   | 29.55 | 40.39 |   60.77  | 30.24 | 40.05 |
| **BARTpho (our method)**           |  **60.10** | **32.42** | **42.28** | **62.87** | **32.58** | **41.33** |
| ViT5 (from the  original paper)    |    58.61   | 31.46 | 41.45 |   62.77  | 33.16 | 42.75 |
| ViT5 (baseline)                    |    57.20   | 30.30 | 40.99 |   62.77  | 33.16 | 42.75 |
| **ViT5 (our method)**              |  **58.27** | **30.51** | **40.58** | **63.34** | **33.41** | **42.75** |

Please refer to the [evaluation script](eval.ipynb)

The models, configs and test sets can be obtained from https://studenthcmusedu-my.sharepoint.com/:f:/g/personal/20c11040_student_hcmus_edu_vn/EkW3bLr1XhVCuNeRc8anjMIBce40rha11KN6N82wlanrCw?e=bxq4zZ

