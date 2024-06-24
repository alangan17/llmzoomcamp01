# llmzoomcamp01
Large Language Model Zoomcamp Week 01

- [llmzoomcamp01](#llmzoomcamp01)
- [0. Setup venv](#0-setup-venv)
- [0.1. Activate venv](#01-activate-venv)
- [0.2. Install uv (Faster package installation then pip)](#02-install-uv-faster-package-installation-then-pip)
- [1.1 Install Libraries using uv](#11-install-libraries-using-uv)
- [1.2 setup jupyter notebook kernal for VSCode, restart VSCode after running the following command](#12-setup-jupyter-notebook-kernal-for-vscode-restart-vscode-after-running-the-following-command)
- [2. Get OpenAI API Key from platform.openai.com, set it in `.env` file (OPENAI\_API\_KEY)](#2-get-openai-api-key-from-platformopenaicom-set-it-in-env-file-openai_api_key)
- [3. Set the Environment Variables (make sure you're in the root folder)](#3-set-the-environment-variables-make-sure-youre-in-the-root-folder)

# 0. Setup venv
```bash
python3 -m venv venv
```

# 0.1. Activate venv
```bash
source venv/bin/activate
```

# 0.2. Install uv (Faster package installation then pip)
```bash
pip install uv
```

# 1.1 Install Libraries using uv
```bash
uv pip install -r requirements.txt
```

# 1.2 setup jupyter notebook kernal for VSCode, restart VSCode after running the following command
```bash
python3 -m ipykernel install --user
```

# 2. Get OpenAI API Key from platform.openai.com, set it in `.env` file (OPENAI_API_KEY)

# 3. Set the Environment Variables (make sure you're in the root folder)
```bash
bash script/set_env.sh
```
