<p align="center">
<img src="https://www.google.com/search?q=https://images.unsplash.com/photo-1599658880122-91e3b4d532de%3Fixlib%3Drb-4.0.3%26ixid%3DMnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8%26auto%3Dformat%26fit%3Dcrop%26w%3D1200%26h%3D300" alt="Banner de Deep Learning com arte de redes neurais">
</p>

<h1 align="center">Deep Learning Specialization — Portfólio de Projetos</h1>

<p align="center">
<strong>Implementações e anotações da especialização da DeepLearning.AI por Andrew Ng</strong>
</p>

<p align="center">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/DeepLearning.AI-Coursera-0056D2%3Fstyle%3Dfor-the-badge%26logo%3Dcoursera" alt="Curso DeepLearning.AI na Coursera">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Python-3.8%2B-3776AB%3Fstyle%3Dfor-the-badge%26logo%3Dpython" alt="Python 3.8+">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/TensorFlow-2.x-FF6F00%3Fstyle%3Dfor-the-badge%26logo%3Dtensorflow" alt="TensorFlow 2.x">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Status-Conclu%C3%ADdo-4CAF50%3Fstyle%3Dfor-the-badge" alt="Status Concluído">
</p>

<p align="center">
<a href="#-objetivo-principal">Objetivo</a> •
<a href="#-showcase-de-projetos">Projetos em Destaque</a> •
<a href="#-estrutura-do-repositório">Estrutura</a> •
<a href="#-como-executar-localmente">Como Executar</a> •
<a href="#-licença-e-créditos">Licença</a>
</p>

🎯 Objetivo Principal
Este repositório é o meu portfólio prático da Deep Learning Specialization. O objetivo é mostrar, executar e replicar os projetos do curso, com instruções claras para rodar os notebooks localmente, visualizar os experimentos e adaptar os códigos para aplicações no mundo real.

📚 Sobre a Especialização
A Deep Learning Specialization é um programa de 5 cursos que ensina desde os fundamentos de redes neurais até arquiteturas avançadas para visão computacional e processamento de linguagem natural (NLP). É mundialmente reconhecida por aliar conceitos teóricos sólidos com implementação prática.

<details>
<summary><strong>Clique para expandir o conteúdo detalhado dos 5 cursos</strong></summary>

Neural Networks and Deep Learning: Fundamentos essenciais como forward/backward propagation, funções de ativação e a primeira rede neural totalmente conectada.

Improving Deep Neural Networks: Técnicas para aprimorar modelos, incluindo regularização (L2, Dropout), normalização por batch, otimizadores (Momentum, RMSprop, Adam) e tuning de hiperparâmetros.

Structuring Machine Learning Projects: Estratégias para construir projetos de ML de ponta a ponta, com foco em análise de erro, métricas e o ciclo de vida de produção.

Convolutional Neural Networks (CNNs): Arquiteturas para visão computacional, como LeNet, AlexNet, VGG, ResNet e Inception, aplicadas a detecção e reconhecimento de imagens.

Sequence Models: Modelos para dados sequenciais, como RNNs, LSTMs, GRUs, word embeddings, e a revolucionária arquitetura de Atenção/Transformers para tarefas de NLP.

</details>

✨ Showcase de Projetos em Destaque
Abaixo estão alguns dos projetos implementados durante o curso.

<table>
<tr>
<td align="center" width="50%">
<strong>Reconhecimento de Sinais Manuais (0-5)</strong><br/><br/>
<img src="https://www.google.com/search?q=https://placehold.co/400x250/2d3748/e2e8f0%3Ftext%3DGIF%2Bdo%2BProjeto%2B1" alt="GIF demonstrando o reconhecimento de sinais manuais" style="border-radius: 8px;" /><br/><br/>
<small>Implementação de uma Rede Neural do zero para classificar imagens de sinais manuais, aplicando conceitos de forward e backward propagation.</small><br/><br/>
<a href="./n00_NN/link_para_o_notebook.ipynb">➡️ Ver o Notebook</a>
</td>
<td align="center" width="50%">
<strong>Detecção de Emoções em Faces com CNNs</strong><br/><br/>
<img src="https://www.google.com/search?q=https://placehold.co/400x250/2d3748/e2e8f0%3Ftext%3DGIF%2Bdo%2BProjeto%2B2" alt="GIF demonstrando a detecção de emoções em faces" style="border-radius: 8px;" /><br/><br/>
<small>Uso de uma Rede Convolucional (CNN) com Keras/TensorFlow para identificar emoções (feliz, triste, etc.) em imagens de rostos.</small><br/><br/>
<a href="./n02_CNN/link_para_o_notebook.ipynb">➡️ Ver o Notebook</a>
</td>
</tr>
</table>

📂 Estrutura do Repositório
📁 n00_NN/ — Notebooks sobre fundamentos de Redes Neurais e DNNs.

📁 n01_Improving_DNN/ — Notebooks sobre regularização, batch norm e otimização.

📁 n02_CNN/ — Notebooks e experimentos de Visão Computacional.

📁 n03_SM/ — Notebooks de Modelos Sequenciais e NLP.

📄 requirements.txt — Dependências Python para rodar os notebooks.

📄 README.md — Este arquivo de apresentação.

🚀 Como Executar Localmente
Siga os passos abaixo para configurar o ambiente e rodar os projetos na sua máquina.

# 1. Clone o repositório
git clone [https://github.com/gaab-braga/DeepLearningSpecialization.git](https://github.com/gaab-braga/DeepLearningSpecialization.git)
cd DeepLearningSpecialization

# 2. Crie e ative um ambiente virtual (recomendado)
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate

# 3. Instale as dependências
pip install -r requirements.txt

# 4. Inicie o Jupyter Lab
jupyter lab

Agora você pode navegar pelas pastas e executar os notebooks!

💡 Dicas e Contribuições
Sugestões? Abra uma issue para sugerir melhorias na estrutura, nos comentários ou nos hiperparâmetros dos modelos.

Melhorias? Pull Requests são bem-vindos! O foco principal é garantir a reprodutibilidade e a clareza do código.

Datasets: Para datasets grandes, a preferência é sempre por scripts de download em vez de adicioná-los diretamente ao repositório.

⚖️ Licença e Créditos
Este repositório contém minhas implementações dos exercícios propostos no curso. O material deve ser utilizado para fins educacionais e de portfólio, sempre respeitando a licença original do curso.

Todo o crédito pelo conteúdo teórico e prático é de Andrew Ng & DeepLearning.AI (Coursera).

<p align="center">
<small>Desenvolvido com ❤️ por <a href="https://www.google.com/search?q=https://github.com/gaab-braga">Gabriel Braga</a></small>
</p>