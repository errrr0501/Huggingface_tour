# Huggingface_tour

## Set up

First [Getting started with our git and git-lfs interface](https://huggingface.co/welcome). Then follow the instruction.

```shell
$ pip install huggingface_hub
# You already have it if you installed transformers or datasets

# huggingface-cli login
# Log in using a token from huggingface.co/settings/tokens
# Create a model or dataset repo from the CLI if needed
$ huggingface-cli repo create repo_name --type {model, dataset, space}
```

Installing Git Large File Storage
Download package with [`link`](https://git-lfs.com/)
Follow the [`instruction`](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage)
```shell

# Change the current working directory into the folder you downloaded and unzipped.
$ cd ~/Downloads/git-lfs-1.X.X
# Install the file
$ ./install.sh
# Verify that the installation, `should show "> Git LFS initialized."
$ git lfs install
```



