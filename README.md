# 🎬 Lazy Tutorial | How to use Wan 2.2 Video Generation on Colab | FREE by:: vadigr (silly and easy)

⚠️ **WARNING!**  
I'm not very experienced in this matter, so I recommend you first learn all the functions and read some more tutorials on how to do it in the [Official ComfyUI Documentation](https://github.com/Comfy-Org/docs).

---

## 📥 Colab URL:
**[Download Virus Free 2026](https://colab.research.google.com/github/vadigr123/WAN_BY-mikus/blob/master/WAN_T2V_with_LoRA_by_mikus.ipynb)** ⬅️ Click

---

## 🚀 Downloading ComfyUI:

Use `UPDATE_COMFY_UI`, `USE_COMFYUI_MANAGER`, `INSTALL_CUSTOM_NODES_DEPENDENCIES` - make sure to enable all of them so everything downloads properly!

**`USE_GOOGLE_DRIVE`** is used to store all models and files on your Google Drive

![Install ComfyUI](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/22d475de-c194-4881-985a-af3c12eacc8c/original=true/22d475de-c194-4881-985a-af3c12eacc8c.jpeg)

---

## 📦 Downloading Models:

Choose one of two options (I recommend 2.2, though 2.1 is also good - I'm just too dumb to figure it out, read below to learn more)

![Download Models](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/94268708-29f0-4df4-9782-db059847032e/original=true/94268708-29f0-4df4-9782-db059847032e.jpeg)

### 📝 Note:
* **Model 2.2 generates surprisingly faster than 2.1!**
* **CUSTOM_LORA_URL** is only used for downloading specific models, meaning if it says the LoRA is for 2.1 and you're using 2.2, it won't work
* I recommend using **GGUF** because it works more stably although it's slower
* I tried WAN 2.1 14B.safetensor but.. it didn't work, only 1.3 of this format worked!

---

## 🎯 Launch:

After the download completion message appears, activate ComfyUI and wait for the text with the link:

```
Warning: This function may stop working due to changes in browser security.
Try `serve_kernel_port_as_iframe` instead. 

https://localhost:8188/
```

You need to click on **`https://localhost:8188/`**

![Launch Link](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/200f2018-976d-4aa7-8033-b07c143efc10/original=true/200f2018-976d-4aa7-8033-b07c143efc10.jpeg)
---

## 🛠️ Workflow Setup:

All you need is:
* **`GGUF`** to load the correct models
* **`Empty HunyuanVideo 1.0 Latent`** to change video size
* **`CLIP Text Encode`** for prompts

(Although you should also use **`KSampler`** to edit the Steps)

![Workflow Example](https://image.civitai.com/xG1nkqKTMzGDvpLrqFT7WA/eb94d9df-9efd-456c-8a5f-5f4c3bc36d19/original=true/eb94d9df-9efd-456c-8a5f-5f4c3bc36d19.jpeg)

---

## ⚙️ My Recommended Settings:

**Resolution:**
* 512x512
* 480x832
* 832x480

**Parameters:**
* **CFG:** 1
* **Steps:** 8-50 (10 can take 15 minutes or more, so I recommend 10 - the more steps, the longer you'll have to wait!)

**Note:** 
* Size: 512x512, 480x832, 832x480
* CFG: 1
* Steps: 8-50 (10 can take 15 minutes or more, so I recommend 10 - the more steps, the longer you'll have to wait!)

---

## ⏱️ Generation Time:

Video generation can take **from 5 minutes to 1 hour**.

---

## 📹 Video Format:

All videos are saved in **WEBP format**, so I recommend using a converter or wait until my lazy ass tries to do something 😅

---

## 📌 Important Notes:

* The link `https://localhost:8188/` is not local but hosted on Colab servers, meaning links like `"https://8188-gpu-t4-....prod.colab.dev/"`
* **I don't recommend using resolutions larger than 832x480** (or vice versa) because it will take longer and doesn't guarantee 100% generation success
* **`SAVE_TO_DRIVE`** is used to store all media on your Google Drive
* **Free Colab** provides 3-4 hours of free usage. After that, you will need to wait another 12-24 hours to use it again.
* **Do not close the tab** while generating. If you do, the generation will stop, and you will have to start over.

---

## 💾 Saving Your Work:

If you enabled **`USE_GOOGLE_DRIVE`**, all your generated videos will be automatically saved to:
* **Local:** `/content/ComfyUI/output`
* **Google Drive:** `/content/drive/MyDrive/ComfyUI_Wan2.1_Output`

New videos and images will auto-copy to Drive!

---

## ❓ Troubleshooting:

### Why GGUF?
I recommend using GGUF because it works more stably although it's slower. I tried WAN 2.1 14B.safetensor but.. it didn't work, only 1.3 of this format worked!

### Why not MP4?
All videos are saved in WEBP format, so I recommend using a converter or wait until my lazy ass tries to do something 😂

### Generation too slow?
* Use smaller resolution (512x512 recommended)
* Reduce steps to 8-10
* Model 2.2 is faster than 2.1

---

## 🎓 Need More Help?

If you have any questions for me and about my experience (I may not have added something here), you can ask me on:

**Discord:** vadigr123

Or join the [Official ComfyUI Discord](https://discord.gg/comfyui)

---

## 📜 Credits:

* Original ComfyUI by [comfyanonymous](https://github.com/comfyanonymous/ComfyUI)
* Wan 2.2 Models by [QuantStack](https://huggingface.co/QuantStack)
* GGUF Node by [calcuis](https://github.com/calcuis/gguf)

---

## ⭐ Star this repo if it helped you!

Thanks for reading this guide! 💕
