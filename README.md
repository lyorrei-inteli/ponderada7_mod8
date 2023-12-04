# Classificação MNIST com CNN

Este repositório contém um projeto que treina uma Rede Neural Convolucional (CNN) para classificar dígitos manuscritos do dataset MNIST. O modelo é capaz de alcançar uma acurácia superior a 95% no conjunto de treinamento com apenas 3 épocas.

## Como Instalar e Executar

### Pré-requisitos

Antes de começar, certifique-se de ter o Python instalado em sua máquina. Este projeto foi testado com Python 3.8.

### Instalação

1. **Navegar até a pasta do repositório**

2. **Criar um Ambiente Virtual**

   ```bash
   python -m venv .venv
   source .venv/bin/activate  # No Windows use: .venv\Scripts\activate
   ```

3. **Instalar as Dependências**

   ```bash
   pip install -r requirements.txt
   ```

### Execução

Para treinar o modelo e testar uma imagem aleátoria do dataset MNIST, abra o arquivo `main.ipynb`, selecione o kernel da venv no vscode e execute as células.

## Demonstração do Projeto

Um vídeo demonstrativo do projeto pode ser encontrado [aqui](URL do vídeo).

## Estrutura do Projeto

- `main.ipynb`: Notebook contendo todo o código para treinamento e teste do modelo.
- `requirements.txt`: Arquivo contendo todas as dependências necessárias para executar o projeto.
- `README.md`: Este arquivo, contendo instruções e informações sobre o projeto.