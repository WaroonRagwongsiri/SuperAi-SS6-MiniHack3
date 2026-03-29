## Prerequisite
- ollama
- uv

## Installation
1. uv sync --frozen
2. ollama pull hf.co/nectec/pathumma-thaillm-8b-think-3.0.0-GGUF:Q8_0
2. ollama pull ollama pull hf.co/mradermacher/typhoon-s-thaillm-8b-instruct-research-preview-GGUF:typhoon-s-thaillm-8b-instruct-research-preview.Q8_0.gguf
3. export CUDA_VISIBLE_DEVICES=0
4. export OLLAMA_NUM_GPU=1
5. export OLLAMA_GPU_LAYERS=all
6. export OLLAMA_LLM_LIBRARY=cuda_v12
6. run it

sudo fallocate -l 8G /swapfile

sudo chmod 600 /swapfile

sudo mkswap /swapfile

sudo swapon /swapfile 