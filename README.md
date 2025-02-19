# POC - Reconhecimento Facial com TensorFlow e Face Recognition

## 📌 Sobre o Projeto
Este repositório contém uma **Prova de Conceito (POC)** sobre **Reconhecimento Facial** utilizando **TensorFlow**, **NumPy**, **Matplotlib**, **OpenCV** e **Face Recognition**. O projeto demonstra como utilizar um modelo pré-treinado para extrair embeddings faciais e comparar rostos com um banco de imagens.

📅 **Bootcamp:** BairesDev - Machine Learning Practitioner - Fevereiro 2025  
👨‍🎓 **Aluno:** Marcello S. Bastos

## 🛠 Tecnologias Utilizadas
- **Python 3.x**
- **TensorFlow 2.x**
- **NumPy**
- **Matplotlib**
- **OpenCV**
- **Face Recognition (dlib)**
- **Google Colab** (para execução do código)

## 📖 Descrição do Projeto

Este projeto realiza as seguintes etapas:
1. **Importação das bibliotecas**
2. **Carregamento do modelo MobileNetV2** para extração de embeddings faciais
3. **Criação de um diretório** para armazenar imagens de referência (Rocky III)
4. **Pré-processamento das imagens**
5. **Extração de embeddings faciais**
6. **Comparação de uma nova imagem com as imagens do banco de dados**
7. **Exibição do resultado do reconhecimento facial**

## 🚀 Como Executar

### 🔹 Passo 1: Clonar o Repositório
```bash
git clone https://github.com/seu-usuario/POC_reconhecimento_facial.git
cd POC_reconhecimento_facial
```

### 🔹 Passo 2: Instalar as Dependências
```bash
pip install tensorflow numpy matplotlib opencv-python face_recognition
```

### 🔹 Passo 3: Executar no Google Colab
1. Acesse o [Google Colab](https://colab.research.google.com/).
2. Faça upload do arquivo **POC_reconhecimentoFacial.ipynb**.
3. Execute as células sequencialmente.

## 📂 Estrutura do Projeto
```
POC_reconhecimento_facial/
│── rocky_iii_faces/         # Diretório de imagens de referência
│── POC_reconhecimentoFacial.ipynb  # Notebook principal
│── README.md                # Documentação do projeto
```

## 🎯 Resultados Esperados
Após o upload de uma nova imagem de teste, o sistema exibirá a imagem carregada junto com a identidade reconhecida e a distância entre embeddings, indicando o nível de similaridade.

## 📌 Exemplo de Uso

```python
identity, distance = recognize_face("test_image.jpg", dataset_embeddings)
print(f"Reconhecido como: {identity} (Distância: {distance:.2f})")
```

## 📜 Licença
Este projeto é disponibilizado sob a licença MIT. Sinta-se livre para modificar e utilizar conforme necessário.

