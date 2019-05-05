# ISIC 2018: Task 3 - Disease Classification using Fast AI

The International Skin Imaging Collaboration (ISIC) is an international effort to improve melanoma diagnosis, sponsored by the International Society for Digital Imaging of the Skin (ISDIS). The ISIC Archive contains the largest publicly available collection of quality controlled dermoscopic images of skin lesions. This implementation is part of [2018 ISIC Challenge](https://challenge2018.isic-archive.com/).

## Getting Started

For quick experiments, you can use [Google Colab](https://colab.research.google.com/notebooks/welcome.ipynb) using `isic_skin_lesion_diagnosis.ipynb`. You can also run the experiments locally.

### Requirements

#### For running locally
-   Install PyTorch (pytorch.org)
-   Install [Fastai](https://docs.fast.ai/install.html)
-   Download the data from [here](https://challenge2018.isic-archive.com/task3/training/)

#### For running in Colab
-   Everything is already installed
-   To download the data from [here](https://challenge2018.isic-archive.com/task3/training/) to your Colab VM, you can use CurlWget Chrome Extension
    -   Note: You should keep a copy of the data in your Google Drive for later use.


## Acknowledgments

-   Our data was extracted from the “ISIC 2018: Skin Lesion Analysis Towards Melanoma Detection” grand challenge datasets [1][2].

-   [1] Tschandl P., Rosendahl C. & Kittler H. The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions. Sci. Data 5, 180161 doi.10.1038/sdata.2018.161 (2018)

-   [2] Noel C. F. Codella, David Gutman, M. Emre Celebi, Brian Helba, Michael A. Marchetti, Stephen W. Dusza, Aadi Kalloo, Konstantinos Liopyris, Nabin Mishra, Harald Kittler, Allan Halpern: “Skin Lesion Analysis Toward Melanoma Detection: A Challenge at the 2017 International Symposium on Biomedical Imaging (ISBI), Hosted by the International Skin Imaging Collaboration (ISIC)”, 2017; [arXiv:1710.05006](https://arxiv.org/abs/1710.05006).

-   [Practical Deep Learning for Coders, v3](https://course.fast.ai/)

-   [Fast AI Forum](https://forums.fast.ai/)
