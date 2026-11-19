# Awesome-AI-Image-Editing-Creative-Retouching

# Top AI Image Editing & Creative Retouching Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on AI Inpainting & Object Removal, Background Matting & Relighting, Generative Fill, Super-Resolution Upscaling & Non-Destructive Photo Editing*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Image Editing & Creative Retouching**. These tools remove unwanted objects, isolate foreground subjects with hair-level alpha matting, relight portraits and product shots, restore degraded photographs, and integrate generative AI directly into raster and RAW photo editors.

**Examples** include Photoroom, Clipdrop, Canva Magic Studio, Adobe Photoshop Web, Pixlr, Fotor, BeFunky, Photopea, Luminar Neo, Topaz Photo AI, and storytold/photocraft (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosted AI inpainting/outpainting studios (`IOPaint`), desktop raster/RAW editors with AI plugins (`GIMP`, `Krita AI Diffusion`, `Darktable`), pixel-accurate background removal (`rembg`, `BiRefNet`), portrait relighting (`IC-Light`), and generative upscaling/restoration (`SUPIR`, `Real-ESRGAN`, `GFPGAN`) — ideal for photographers, e-commerce creators, digital artists, and developers building sovereign image-editing pipelines.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Photoroom](https://photoroom.com)**  
  AI photo editing and product photography platform specializing in instant subject segmentation, AI studio backgrounds, batch relighting, shadow generation, and magic retouching.

- **[Clipdrop (Jasper)](https://clipdrop.co)**  
  Browser-based AI visual editing ecosystem providing instant background removal, ambient relighting, generative fill, object cleanup, and image upscaling tools.

- **[Adobe Photoshop Web (Firefly)](https://adobe.com)**  
  Cloud-based version of Photoshop featuring browser-native Generative Fill, Generative Expand, Remove Tool object cleanup, and non-destructive layer compositing.

- **[Canva (Magic Studio)](https://canva.com)**  
  All-in-one cloud visual design and photo editing suite featuring Magic Eraser, Magic Edit, Magic Expand, Background Remover, and instant brand mockups.

- **[Photopea](https://photopea.com)**  
  Advanced browser-native raster and vector image editor with full PSD/XCF/Sketch layer compatibility, smart objects, and AI-assisted magic replace and background removal tools.

- **[Pixlr](https://pixlr.com)**  
  Cloud photo editing and graphic design suite offering browser-based AI generative fill, object removal, auto-cutout, and quick social templates.

- **[Luminar Neo (Skylum)](https://skylum.com)**  
  AI-powered creative photo editor built for photographers featuring Relight AI, Sky AI replacement, GenErase object removal, Portrait Bokeh AI, and RAW processing.

- **[Topaz Photo AI](https://topazlabs.com)**  
  Commercial computer-vision image enhancement suite renowned for AI noise reduction, motion deblurring, face recovery, and high-detail super-resolution upscaling.

- **[Fotor](https://fotor.com)**  
  Cloud photo retouching and design platform providing one-click AI photo enhancer, blemish/object remover, background replacement, and batch e-commerce editing.

- **[BeFunky](https://befunky.com)**  
  Browser-based creative photo editor and collage maker featuring AI portrait retouching, background remover, art-style filters, and smart sky replacement.


## Open-Source GitHub Projects

- **[storytold/photocraft](https://github.com)**  
  Open-source AI photo editing and creative retouching toolkit engineered for structured visual adjustments, non-destructive workflows, and local/API-driven image manipulation.

- **[IOPaint (`Sanster/IOPaint`)](https://github.com)**  
  Free, open-source (`Apache-2.0`) self-hosted image inpainting, object removal, outpainting, and upscaling web studio powered by `LaMa`, `PowerPaint`, `BrushNet`, and `FLUX` / `SDXL` models.

- **[Krita AI Diffusion (`Acly/krita-ai-diffusion`)](https://github.com)**  
  Open-source (`GPL-3.0`) plugin integrating ComfyUI directly inside Krita for real-time live painting, layer-aware ControlNet, seamless regional inpainting, and generative upscaling.

- **[GIMP (`GNOME/gimp`) & G'MIC (`GreycLab/gmic`)](https://github.com)**  
  Flagship open-source (`GPL-3.0`) cross-platform raster image editor extensible with `G'MIC` filters, `Resynthesizer` smart object removal, and local Stable Diffusion/OpenVINO AI plugins.

- **[Darktable (`darktable-org/darktable`) & RawTherapee (`Beep6581/RawTherapee`)](https://github.com)**  
  Professional open-source (`GPL-3.0`) non-destructive RAW photography workflow applications featuring parametric masking, color grading, denoising, and lens correction.

- **[rembg (`danielgatis/rembg`)](https://github.com)**  
  Widely adopted open-source (`MIT`) background removal CLI, Python library, and HTTP server supporting `BiRefNet`, `U2Net`, `IS-Net`, and `SAM` ONNX models for local batch cutouts.

- **[BiRefNet (`ZhengPeng7/BiRefNet`)](https://github.com)**  
  High-resolution open-source (`MIT`) Bilateral Reference Network achieving state-of-the-art dichotomous image segmentation and fine hair/fur alpha matting.

- **[IC-Light (`lllyasviel/IC-Light`)](https://github.com)**  
  Open-source (`Apache-2.0`) illumination-manipulation diffusion framework for consistent portrait and product background relighting matching Photoroom and Clipdrop's AI Relight tools.

- **[SUPIR (`Fanghua-Yu/SUPIR`)](https://github.com)**  
  Open-source generative photo-realistic image restoration and creative upscaling model delivering high-frequency texture recovery guided by multimodal prompts.

- **[Real-ESRGAN (`xinntao/Real-ESRGAN`)](https://github.com)**  
  Standard open-source (`BSD-3-Clause`) blind image and illustration super-resolution framework for fast, artifact-free 2x/4x upscaling on consumer GPUs.

- **[GFPGAN (`TencentARC/GFPGAN`) & CodeFormer (`sczhou/CodeFormer`)](https://github.com)**  
  Leading open-source (`Apache-2.0` / `S-Lab`) blind face restoration models for recovering sharp facial details in degraded, low-resolution, or archival portraits.

- **[Upscayl (`upscayl/upscayl`)](https://github.com)**  
  Free and open-source (`AGPL-3.0`) cross-platform desktop AI image upscaler built on `ncnn-vulkan` that runs smoothly on Linux, macOS, and Windows without requiring NVIDIA CUDA.

- **[InvokeAI (`invoke-ai/InvokeAI`)](https://github.com)**  
  Professional open-source (`Apache-2.0`) creative studio featuring an infinite Unified Canvas for non-destructive regional inpainting, outpainting, Control Layers, and photobashing.

- **[FLUX.1 Kontext / FLUX.1 Fill (`black-forest-labs/flux`)](https://github.com)**  
  Open-weight 12B-parameter rectified-flow Transformer models engineered for instruction-based image editing, object replacement, style transfer, and seamless masked inpainting.

- **[ComfyUI (`comfyanonymous/ComfyUI`)](https://github.com)**  
  Industry-standard open-source (`GPL-3.0`) node-based visual pipeline engine for chaining segmentation (`SAM 2`), inpainting, relighting (`IC-Light`), color matching, and upscaling locally.

- **[Lama Cleaner / LaMa (`advimman/lama`)](https://github.com)**  
  Fast open-source (`Apache-2.0`) Resolution-robust Large Mask Inpainting model utilizing Fast Fourier Convolutions to cleanly erase objects, watermarks, and wires at high resolutions.

### Additional Strong Open-Source Options

- **[Segment Anything 2 / SAM 2 (`facebookresearch/sam2`)](https://github.com)** for instant click-and-box object selection masks powering precision retouching and regional edits.
- **[InstructPix2Pix (`timothybrooks/instruct-pix2pix`)](https://github.com)** and **[OmniGen (`VectorSpaceLab/OmniGen`)](https://github.com)** for unified natural-language instruction-guided image editing without manual masks.
- **[DeOldify (`jantic/DeOldify`)](https://github.com)** and **[DDColor (`piddnad/DDColor`)](https://github.com)** for open-source automatic colorization and restoration of black-and-white photography.
- **[Hugin (`hugin`)](https://sourceforge.io)** and **[Luminance HDR](https://github.com)** for open-source panoramic stitching, exposure bracketing, and high-dynamic-range tone mapping.
- **[ImageMagick (`ImageMagick/ImageMagick`)](https://github.com)** and **[libvips (`libvips/libvips`)](https://github.com)** for high-speed CLI and server-side batch resizing, color-profile conversion, and compositing pipelines.

**Frameworks for building custom systems**: Combine **storytold/photocraft** or **GIMP / Krita AI Diffusion** (desktop editing) with **IOPaint** (object removal & inpainting), **rembg + BiRefNet** (background matting), **IC-Light** (relighting), and **SUPIR / Real-ESRGAN** (upscaling) for a complete, subscription-free AI photo editing and retouching suite.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
