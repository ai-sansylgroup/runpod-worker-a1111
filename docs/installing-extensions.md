## Example on Roop Extension

```bash
source /workspace/venv/bin/activate
cd /workspace/stable-diffusion-webui/extensions
git clone --depth=1 https://github.com/example-extension/example-extension.git
cd /workspace/stable-diffusion-webui/extensions/example-extension
pip3 install -r requirements.txt
```

#### Download the model

```bash
mkdir -p /workspace/stable-diffusion-webui/models/roop
cd /workspace/stable-diffusion-webui/models/roop && \
wget https://huggingface.co/ai-sansylgroup/inswapper/resolve/main/inswapper_128.onnx
```
