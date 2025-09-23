# Deep Learning Specialization — Resumo & Portfólio

![Deep Learning Specialization](https://www.coursera.org/specializations/deep-learning)

> **Andrew Ng & DeepLearning.AI — Coursera**

---

## 🎯 Elevator pitch

Este repositório reúne os notebooks e exercícios da *Deep Learning Specialization* (DeepLearning.AI / Coursera). O objetivo aqui é **mostrar, executar e replicar** os projetos práticos do curso — com instruções claras para executar localmente, visualizar experimentos e adaptar os códigos para projetos reais.

---

## 📚 Sobre a especialização

A *Deep Learning Specialization* é um conjunto de **5 cursos** focados em ensinar desde fundamentos de redes neurais até arquiteturas modernas para visão computacional e sequências (NLP). É reconhecida por sua didática prática e por alinhar conceitos teóricos com implementações em código.

<details>
<summary><strong>Conteúdo dos 5 cursos (clique para expandir)</strong></summary>

1. **Neural Networks and Deep Learning** — fundamentos: forward/backward propagation, funções de ativação, rede totalmente conectada.
2. **Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization** — técnicas práticas: regularização, normalização por batch, otimização (Momentum, RMSprop, Adam) e tuning.
3. **Structuring Machine Learning Projects** — estratégia de projeto, análise de erros, ciclo de produção em machine learning.
4. **Convolutional Neural Networks** — CNNs para visão computacional: detecção, reconhecimento, transfer learning, redes residuais.
5. **Sequence Models** — RNNs, LSTMs, word embeddings, atenção/transformers e aplicações em NLP.

</details>

---

## ✨ O que você aprenderá (resumo prático)

* Construir, treinar e diagnosticar redes neurais profundas.
* Aplicar técnicas de otimização e regularização para melhorar performance.
* Projetar pipelines e estratégias para projetos ML em produção.
* Implementar CNNs para visão computacional e RNNs/transformers para linguagem.
* Usar frameworks e labs práticos (notebooks) para consolidar o aprendizado.

---

## 🚀 Por que é relevante (para quem visita este repositório)

* 🧠 **Didática prática**: o curso prioriza exercícios implementados do zero — excelente para portfólio.
* 📈 **Foco em produção**: ensina não só como treinar modelos, mas como analisar erros e organizar projetos.
* 🌍 **Autoridade**: ministrado por Andrew Ng e equipe DeepLearning.AI — currículo reconhecido na indústria.

---

## 🔎 Estrutura deste repositório

* `n00_NN/` — Notebooks do módulo de redes neurais (fundamentos e DNNs).
* `n01_Improving_DNN/` — Notebooks sobre regularização, batch norm e otimização.
* `n02_CNN/` — Notebooks e experimentos de visão computacional.
* `n03_SM/` — Notebooks de Sequence Models e NLP.
* `data/` — (opcional) pequenos datasets ou scripts para baixar datasets públicos.
* `requirements.txt` — dependências para rodar os notebooks localmente.
* `README.md` — este arquivo.

> Se quiser, eu posso gerar um `requirements.txt` / `environment.yml` automaticamente com base nos notebooks — peça que eu faça.

---

## 🛠 Como executar (guia rápido)

```bash
# 1) clonar
git clone git@github.com:gaab-braga/DeepLearningSpecialization.git
cd DeepLearningSpecialization

# 2) criar ambiente (recomendado)
python -m venv .venv
# Windows
.venv\Scripts\activate
# macOS / Linux
source .venv/bin/activate

# 3) instalar dependências
pip install -r requirements.txt

# 4) abrir Jupyter Lab
jupyter lab
```

> Se preferir, substitua pelo `conda env create -f environment.yml` se eu gerar o arquivo para você.

---

## 📌 Sugestões de badges & primeiros visuais

* Badge Coursera / DeepLearning.AI
* Linha do tempo do curso (pequeno roadmap com setas)
* GIF curto mostrando um notebook rodando (`jupyter nbconvert --to html` e screenshot)

---

## 💡 Dicas para quem visita e quer contribuir

* Abra uma *issue* para sugerir melhorias nos notebooks (estrutura, comentários, melhores hiperparâmetros).
* Pull requests são bem-vindos — foque em **reprodutibilidade** (scripts para baixar dados, seeds para aleatoriedade).
* Para grandes datasets, prefira links externos e scripts de download em vez de commitar dados no repositório.

---

## ⚖️ Licença & Créditos

* Este repositório contém minha (sua) implementação dos exercícios/notebooks do curso. Respeite a **licença original do curso** e use este material apenas para fins educativos e de portfólio.
* Créditos: Andrew Ng & DeepLearning.AI (Coursera).

---

## 📬 Contato

Quer que eu adapte o README (trocar tom, incluir imagens/vídeos, adicionar badges dinâmicos ou gerar `requirements.txt`)? Me fala o tom que prefere: **mais formal**, **mais técnico** ou **mais atraente para recrutadores** — eu ajusto na hora.

---

*Gerado automaticamente: README detalhado para destacar o conteúdo e a prática da Deep Learning Specialization. Se quiser, faço uma versão em inglês.*

