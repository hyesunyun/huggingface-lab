# huggingface-lab

Lab for CS6983/CS4973 Research in Human-Centered NLP.

You can run these notebooks on [Google Colab](https://colab.research.google.com/github/hyesunyun/huggingface-lab/blob/main/huggingface_inference.ipynb). You won't need to create a virtual environment for Google Colab as it comes with most of the packages we need installed and we can install the HuggingFace libraries directly on Colab.

In order to run the Colab with GPU, change the runtime type to one of the GPU options for Hardware accelerator.

![Screenshot 2025-01-03 at 12 17 40 AM](https://github.com/user-attachments/assets/908d6f02-2ead-449c-9191-8d82a858923e)
![Screenshot 2025-01-03 at 12 18 08 AM](https://github.com/user-attachments/assets/220f1f55-6b88-40a5-986f-c3b95aa149b4)

You can also run them locally although a GPU may be needed for the fine-tuning notebook:
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
