
# Unveiling the patterns and influencing factors of rural housing landscape homogenization in China based on large visual models

**[China Regional Coordinated Development and Rural Construction Institute, Sun Yat-sen University](https://rrlab.sysu.edu.cn/)**

Yaofu Huang,
Weihuan Deng,
Xun Li,

The model has been implemented utilizing the PyTorch framework, with experimental benchmarks established against the latest versions of LLaVA-v1.6 and DINOv2.

## Installation

To install all the required dependencies for inference, please follow the instructions below:

*[conda](https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html)* **(Recommended)** - Clone the repository and then create and activate a `dino` conda environment using the provided environment definition:

```shell
conda create -n dino python=3.10
conda activate dino
```

*[pip](https://pip.pypa.io/en/stable/getting-started/)* - Clone the repository and then use the provided `requirements.txt` to install the dependencies:

```shell
pip install -r requirements.txt
```

## Data preparation

### House_prototype

- `1_Simple_Chinese_style`
- `2_European_and_American_style`
- `3_Modern_Style`

### Town_demo_village_scene
- `Province`
- `City`
- `County`
- `Town`

## Inference

### Image filtering and matching

```shell
Bash Image_filtering_and_matching.sh
```

## Citing paper
The paper is currently under review. We invite you to stay tuned for updates and the publication of our research findings.

