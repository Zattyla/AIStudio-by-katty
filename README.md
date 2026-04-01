# 🎤 AI Studio (UVR5 + RVC v2)

A professional, all-in-one Google Colab pipeline for creating high-quality AI Covers. This project integrates **Ultimate Vocal Remover (UVR5)** for elite audio separation and **RVC v2 (Applio)** for state-of-the-art voice conversion.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Zattyla/AIStudio-by-katty/blob/main/AIStudio.ipynb?authuser=4)

## ✨ Key Features
- **Elite Isolation:** Uses `Kim_Vocal_2` (MDX-Net) to separate vocals and instrumentals with studio precision.
- **Vocal Cleaning:** Integrated De-reverb models to ensure the AI conversion is crystal clear.
- **RVC v2 Engine:** Powered by Applio for the most stable and realistic voice cloning.
- **Automated Workflow:** From raw MP3 to a mixed Final Cover in one single notebook.
- **Auto-Backup:** Automatically saves your results and models to Google Drive.
- **Built-in Optimizer**: Easy one-click tool to clear GPU cache and keep the notebook running smoothly.

## 🚀 How to Use
1.  Click the **Open in Colab** badge above.
2.  Go to `Runtime` -> `Change runtime type` and select **T4 GPU**.
3.  Run **Step 1 to 5** to set up the environment.
4.  Upload your song to the `/inputs` folder.
5.  Follow the instructions in the **User Guide** inside the notebook to generate your cover.

## 📂 Project Structure
- `/inputs`: Place your raw audio files here.
- `/outputs/uvr`: Separated Vocals and Instrumentals.
- `/outputs/rvc`: AI-converted voice tracks.
- `/outputs/FINAL_COVER`: Your finished masterpieces.

## 🛠️ Requirements
- A Google Account (for Colab and Drive).
- A Voice Model link (from HuggingFace, Pixeldrain, or Drive).
- Basic understanding of RVC (Pitch/Transpose settings).

## ⚖️ Disclaimer
This tool is for **educational and creative purposes only**. Please respect copyright laws and the ethical use of AI-generated content. Do not use this to create malicious deepfakes or impersonate individuals without consent.

---
**Developer:** [newletter](https://github.com/Zattyla)  
**Credits:** Based on [Applio](https://github.com/IAHispano/Applio) and [UVR5](https://github.com/Anjok07/ultimatevocalremoverui).
