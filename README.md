# 🦷 Sprint04: BetterTooth - Detecção de Cáries com IA

## 📌 Sobre o Projeto
Este projeto faz parte do **Sprint03** da disciplina **Disruptive Architectures: IoT, IOB & Generative IA**. O objetivo principal é desenvolver um modelo de **Inteligência Artificial** para **detecção de cáries dentárias** a partir de imagens odontológicas panorâmicas, utilizando **Redes Neurais Convolucionais (CNNs)** e técnicas de **Transfer Learning**.

A solução é baseada em imagens públicas do [Panoramic Dental Dataset (Kaggle)](https://www.kaggle.com/datasets/thunderpede/panoramic-dental-dataset) e propõe uma arquitetura escalável e integrável a sistemas clínicos.

---
## 👥 Integrantes do Grupo

* **Murillo Ferreira Ramos** - RM553315
* **Pedro Luiz Prado** - RM553874
* **William Kenzo Hayashi** - RM552659

## ✅ Evolução da Versão Final

### 🔹 1. Melhorias Implementadas
- Organização e refatoração completa do notebook
- Implementação de **Transfer Learning com ResNet50**
- Acurácia significativamente aprimorada com ajuste de hiperparâmetros
- Criação de uma **API com Flask** para testes de predição externa
- EDA completa: análise de resolução, duplicatas, visualização de classes
- Documentação finalizada no GitHub

---

## 🧠 Autocrítica e Reflexão

### O que funcionou bem:
- Aplicação de Transfer Learning agilizou o desenvolvimento
- Visualização das imagens e estrutura dos dados com matplotlib e PIL
- Organização e versionamento com GitHub

### O que foi desafiador:
- Dataset desbalanceado
- Tempo limitado para exploração de outras arquiteturas
- Limitações na infraestrutura local para treinar o modelo

### O que foi aprendido:
- A importância do pré-processamento e EDA
- Como preparar uma API para integração da IA
- Boas práticas de estruturação de notebooks e GitHub

### O que faríamos diferente:
- Uso de Google Colab com GPU desde o início
- Implementação mais precoce da API
- Coleta de um dataset adicional ou rotulado manualmente

---

## 🚀 Próximos Passos
📌 **Aplicar Grad-CAM para visualização das regiões afetadas**  
📌 **Criar interface mobile/web para consulta dos diagnósticos**  
📌 **Ampliar a detecção para outras condições como periodontite e dentes impactados**  
📌 **Coletar feedback de dentistas para validar os resultados clínicos**

---

## 📂 Estrutura do Repositórioo
```
📁 Sprint03
├── 📜 Sprint03.ipynb # Notebook principal com EDA, treino e inferência
├── 📁 dataset/ # Imagens organizadas por classe
├── 📁 models/ # Modelos treinados (.h5)
├── 📁 api/ # Código Flask para execução da IA
├── 📁 docs/ # Diagramas e relatórios
├── 📜 requirements.txt # Dependências
└── 📜 README.md # Documentação final

```
---

## ⚙️ Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/sprint03.git

```
2.Instale as dependências:

```
pip install -r requirements.txt

```
3.Abra o notebook Sprint03.ipynb em Jupyter ou Colab.

4.Execute as células para carregar dados, treinar o modelo e gerar predições.

5.Para usar a API localmente:

```
cd api/
python app.py
```

## 🚀 Melhorias Implementadas no Sprint04

### 🔹 1. Evolução do Protótipo Funcional
✅ Organização aprimorada do código
✅ Melhor documentação e comentários no código
✅ Pipeline estruturado para reutilização futura
✅ Pré-processamento das imagens melhorado

### 🔹 2. Modelo de Inteligência Artificial
✅ Implementação de uma **Rede Neural Convolucional (CNN)**
✅ Ajuste de hiperparâmetros para otimizar a precisão
✅ Estratégias para evitar overfitting (**dropout, data augmentation**)
✅ Melhor visualização das métricas de avaliação

### 🔹 3. Organização e Documentação
✅ Notebook estruturado com explicações claras
✅ Documentação detalhada no GitHub
✅ Resultados e gráficos gerados para facilitar análise


## 🛠 Tecnologias Utilizadas
- **Python**
- **TensorFlow / Keras**
- **Google Colab**
- **OpenCV**
- **Redes Neurais Convolucionais (CNNs)**
- **Bibliotecas para processamento de imagens**



