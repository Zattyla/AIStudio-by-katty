# 🎵 AI Cover Factory (UVR + RVC)

Este repositório contém um notebook Google Colab otimizado para a criação de AI Covers, unindo separação de áudio profissional e conversão de voz em um único fluxo de trabalho.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Zattyla/RVC-UVR-Pipeline/blob/main/AIStudio.ipynb)


## ✨ Funcionalidades
- **Separação de Elite:** Usa modelos MDX-Net (UVR5) para isolar vocais sem restos de bateria ou melodia.
- **Limpeza Profunda:** Algoritmos de De-reverb integrados para evitar vozes metálicas.
- **Motor Applio:** Baseado na tecnologia RVC v2 mais estável do mercado.
- **Mixagem Automática:** Ajuste de ganho e volume para que o cover soe profissional.

## 🚀 Como usar
1. Clique no botão **Open in Colab** acima.
2. Ative a GPU em `Ambiente de Execução` > `Alterar tipo de ambiente`.
3. Rode as células em ordem (1 a 15).
4. Suba sua música na pasta `inputs`.
5. Insira o link do seu modelo RVC favorito e divirta-se!

## 📂 Estrutura de Pastas
- `/inputs`: Coloque aqui seus arquivos `.mp3` ou `.wav`.
- `/outputs/uvr`: Arquivos separados (Vocals/Instrumental).
- `/outputs/rvc`: Resultado da voz convertida pela IA.
- `/outputs/FINAL_COVER`: O resultado pronto para postar.

---
**Créditos:** Baseado no motor [Applio](https://github.com/IAHispano/Applio) e modelos UVR5.
