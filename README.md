# teachable-gradio

Short example project to build a Gradio interface based on model trained using teachablemachine.

## Installation

All examples should be compatible with Google Colab [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yasirroni/teachable-gradio/blob/master) and did not need any local installation. To install locally, you can use:

```shell
python3.12 -m venv env
source env/bin/activate
```

## Examples

List of examples available at `nbs/`:

1. `gradio_tf.ipynb`: Gradio wrapper example using tensorflow image classification.
1. `teachable_evaluate.ipynb`: Exploratory to check and evaluate model created by teachablemachine.
1. `teachable_gradio.ipynb`: Gradio wrapper for deploying model created by teachablemachine.

## Usage

### Image classification

1. Open `nbs/teachable_gradio.ipynb` in Google Colab and save it

    You can use [this link](https://colab.research.google.com/github/yasirroni/teachable-gradio/blob/main/nbs/teachable_gradio.ipynb) to open it in Google Colab

1. Train a model on [teachablemachine](https://teachablemachine.withgoogle.com/train/image)
1. Export model in a keras format
1. Unzip the downloaded file and get a folder named `converted_keras`
1. Upload `converted_keras` on your Google Drive under `/Colab Notebooks/teachable-gradio/PROJECT_NAME/converted_keras/`
1. Go back to the opened `nbs/teachable_gradio.ipynb` example notebook and run it
