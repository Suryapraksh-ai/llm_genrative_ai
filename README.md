# llm_genrative_ai
# 🎨 CLIP + VQGAN Text-to-Image Generator & Video Interpolation

This project uses **OpenAI's CLIP** and **VQGAN** (via Taming Transformers) to generate **images from text prompts**, and then **interpolates** between generated images to create a **video animation**.

> ✅ Fully implemented in **Google Colab**  
> ✅ Combines vision-language and generative modeling  
> ✅ Supports prompt engineering and exclusion terms  
> ✅ Outputs **MP4 video** from your prompt-driven imagination!

---

## 🌟 Demo Output

| 🎬 Prompt-based Interpolation Video |
|------------------------------------|
| A blue tree → Kids playing in moon → Dancing flowers |

> **Watch generated video at the end of this notebook or GitHub Pages (if hosted)**

---

## 🛠️ Tech Stack

- 🧠 **CLIP** (ViT-B/32) - OpenAI's vision-language model
- 🧱 **VQGAN** - Taming Transformers for image generation
- 🔁 **Latent Interpolation** between vectors
- 🎞️ **Imageio** - for video creation
- 🧪 PyTorch, Torchvision, NumPy, Matplotlib

---

## 📦 Installation & Setup (Google Colab Recommended)

```bash
# Clone Required Repositories
git clone https://github.com/openai/CLIP.git
git clone https://github.com/CompVis/taming-transformers

# Install Python Dependencies
pip install --no-deps ftfy regex tqdm
pip install omegaconf==2.0.0 pytorch-lightning==1.0.8
pip install einops taming-transformers-rom1504
pip install numpy==1.21.6
