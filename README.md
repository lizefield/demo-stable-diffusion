# demo-stable-diffusion

## setup

- Visual Studio Code with Jupyter extension

### python venv

```
python -m venv .venv
source .venv/bin/activate
```

### pytorch (M1)

https://pytorch.org/get-started/locally/

- Preview (Nightly)
- Mac
- Pip
- Python
- Default

```
pip3 install --pre torch torchvision --extra-index-url https://download.pytorch.org/whl/nightly/cpu
```

### environment

create `.env`

https://huggingface.co/CompVis/stable-diffusion-v1-4

```
USER_ACCESS_TOKEN=<your user access token on hugging face>
```

### notebook

select virtual environment
