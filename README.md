# AnimeWebUI Colab

A streamlined Google Colab notebook for running Stable Diffusion anime image generation models with a modern web interface.

## Notebook Structure

- **Intro**: Project info and quick links
- **Generation**: Model, LoRA, and extension selection. Now includes an automatic fix for Add-Detail-XL LoRA download issues.
- **Mobile**: Keep-alive for mobile users
- **Saving**: Image saving and export options

## Features

- **Multiple Model Support**: Animagine-XL 4.0, Stable Diffusion 3.5 Large, SDXL, FLUX.1-dev, and more
- **LoRA Categories**: 
  - 🔧 Detailer LoRAs (including Add-Detail-XL, with auto-download fix)
  - 🎨 Style LoRAs
  - 🎬 Action LoRAs
  - 👥 Character LoRAs
- **ControlNet Support**: Advanced image control (v1.0, v1.1, t2i)
- **Enhanced Extensions**: CLIP Interrogator, background removal, upscaling tools
- **Google Drive Integration**: Save outputs directly to your Drive
- **VAE**: Uses a different VAE from the default for improved results

## Quick Start

1. Open the notebook in Google Colab
2. Select your desired model and LoRAs (Add-Detail-XL will auto-download if selected)
3. Run the "🚀 Launch web UI" cell
4. Wait for the web interface link to appear
5. Start generating anime images!

## Model Compatibility

- **SDXL Models**: Compatible with TrendCraft, Add-Detail-XL, and T-Rex Studio LoRAs
- **Illustrious Models**: Compatible with all available LoRAs
- **SD3/FLUX Models**: Base models only (no LoRA support yet)

## Additional Tools

- Mobile keep-alive functionality
- Image saving and export options
- Automatic compatibility checking

Based on [anime-webui-colab](https://github.com/NUROISEA/anime-webui-colab).
