# Setup Flux Schnell GGUF (ComfyUI)

1. ### [Follow to Install GIT and Python](https://github.com/zohaibtariq/youtube-guides/blob/main/setup-git-python.md)

1. ### [Follow to Setup ComfyUI with Manager & GGUF](https://github.com/zohaibtariq/comfyui-manager/blob/main/README.md)

3. #### Download Files

### Download GGUF models (any one required)

   - [Flux.1 Dev GGUF (flux1-dev-Q4_0.gguf)](https://huggingface.co/city96/FLUX.1-dev-gguf/tree/main)
   - [Flux.1 Schnell GGUF (flux1-schnell-Q4_0.gguf)](https://huggingface.co/city96/FLUX.1-schnell-gguf/tree/main)

Move this downloaded file to `ComfyUI/models/unet/flux1-dev-Q4_0.gguf` OR `ComfyUI/models/unet/flux1-schnell-Q4_0.gguf`

### Download Clip files

  - [Clip encoder (clip_l.safetensors)](https://huggingface.co/comfyanonymous/flux_text_encoders/tree/main)
  - [Clip encoder (t5xxl_fp8_e4m3fn.safetensors)](https://huggingface.co/comfyanonymous/flux_text_encoders/tree/main)

Move this downloaded file to `ComfyUI/models/clip/clip_l.safetensors` & `ComfyUI/models/clip/t5xxl_fp8_e4m3fn.safetensors`

### Download Vae files (any relevant one)

  - [Flux.1 Dev VAE (ae.safetensors)](https://huggingface.co/black-forest-labs/FLUX.1-dev/tree/main)
  - [Flux.1 Schnell VAE (ae.safetensors)](https://huggingface.co/black-forest-labs/FLUX.1-schnell/blob/main/ae.safetensors)

Move this downloaded file to `ComfyUI/models/vae/ae.safetensors`

### Download Lora file (not required)

  - [Flux realism lora (lora.safetensors)](https://huggingface.co/XLabs-AI/flux-RealismLora/tree/main)

Move this downloaded file to `ComfyUI/models/lora/lora.safetensors`

### Download Workflows

- [Workflow - with realism lora attached](https://github.com/zohaibtariq/youtube-guides/blob/main/flux_schnell_q4_gguf_workflow.json)
- [Workflow - without realism lora attached]()
