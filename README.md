# huggingface-lab

Lab for CS6983/CS4973 Research in Human-Centered NLP.

You can run these notebooks on [Google Cola](https://colab.research.google.com/github/hyesunyun/huggingface-lab/blob/main/huggingface_inference.ipynb). You won't need to create a virtual environment for Google Colab as it comes with most of the packages we need installed and we can install the HuggingFace libraries directly on Colab.

In order to run the Colab with GPU, change the runtime type to one of the GPU options for Hardware accelerator.

You can also run them locally (no GPU is needed):
```bash
# clone the repo
git clone https://github.com/hyesunyun/huggingface-lab.git
cd huggingface-lab

# create a virtual environment (conda)
conda create -n huggingface-lab python=3.10
conda activate huggingface-lab

# install dependencies
pip install -r requirements.txt

# run the server
jupyter notebook
```