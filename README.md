## Prerequisite
- ollama
- uv

## Installation
1. uv sync --frozen
2. ollama pull hf.co/nectec/pathumma-thaillm-8b-think-3.0.0-GGUF:Q8_0
3. export CUDA_VISIBLE_DEVICES=0
4. export OLLAMA_NUM_GPU=1
5. export OLLAMA_GPU_LAYERS=all
6. run it