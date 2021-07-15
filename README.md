# spacy_base

docker for spacy basic use with jupyterlab/extensions and mecab

## usage

```$docker-compose up -d --build```

After docker container start up, open jupyterlab with <http://localhost:8080/lab?>

## Jupyter Lab

Following jupyter extensions will be installed
You can refer links for each extension for your configuration

- [jupyterlab_code_formatter](https://github.com/ryantam626/jupyterlab_code_formatter)
- [jupyterlab_theme_solarized_dark](https://github.com/AllanChain/jupyterlab-theme-solarized-dark)
- [jupyterlab-lsp](https://github.com/krassowski/jupyterlab-lsp)
- [yapf](https://github.com/google/yapf)
- [python-lsp-server](https://pypi.org/project/python-lsp-server/)
  - [pyls-flake8](https://pypi.org/project/pyls-flake8/)

jupyter configurations will be stored under `/.jupyter/lab/user-settings/`

### reference for JupyterLab setting

<https://github.com/fuchami/jupyterlab-template>
