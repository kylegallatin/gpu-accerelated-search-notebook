# gpu-accerelated-search-notebook
Notebook tutorial for creating a GPU accelerated search index on a Nvidia Data Science Workstation. Blog post is available [here](https://towardsdatascience.com/nvidia-gave-me-a-15k-data-science-workstation-heres-what-i-did-with-it-70cfb069fc35) and the video tutorial to accompany this repository is also [available on YouTube](https://www.youtube.com/watch?v=WCz8AF-wT1I&feature=emb_title).

To run this notebook, you'll need a system with GPU compute. This tutorial uses a Nvidia Data Science Workstation.

## Setup Your Environment
First, you'll need to install all basic python packages:
```pip install -r requirements.txt```

Also, you'll need to follow the installation instructions for [NVIDIA's RAPIDS](https://rapids.ai/start.html) and [Facebook's Faiss library](https://github.com/facebookresearch/faiss/blob/master/INSTALL.md).