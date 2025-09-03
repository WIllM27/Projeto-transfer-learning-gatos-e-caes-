# 🐱🐶 Classificação de Gatos e Cachorros com Transfer Learning

## 📌 Sobre o projeto
Este repositório contém um projeto de **classificação de imagens** para distinguir entre **gatos** e **cachorros** utilizando **Transfer Learning**.  

O Transfer Learning consiste em **reaproveitar redes neurais já treinadas em grandes datasets** (como o *ImageNet*) e adaptá-las a novas tarefas específicas.  
Aqui, utilizamos uma rede pré-treinada (ex.: VGG16) como **extratora de características**, adicionando uma nova camada de classificação binária.

---

## ⚙️ Passos do Projeto
1. **Configuração do ambiente** → utilização da GPU no Google Colab.  
2. **Preparação do dataset** → extração do `.zip`, organização e carregamento das imagens.  
3. **Pré-processamento** → normalização, resize e divisão em treino/validação.  
4. **Transfer Learning** → uso de uma rede pré-treinada como base (camadas congeladas).  
5. **Treinamento** → apenas a camada final é ajustada no início.  
6. **Avaliação** → geração de métricas e gráficos para interpretar desempenho.  
7. **Conclusão** → análise dos resultados obtidos.  

---

## 📂 Estrutura do repositório
```
📁 cats-vs-dogs-transfer-learning
 ┣ 📜 Projeto_transfer_learning_revisado.ipynb   # Notebook principal
 ┣ 📜 README.md                                  # Este arquivo
```

---

## 🚀 Como executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/cats-vs-dogs-transfer-learning.git
   cd cats-vs-dogs-transfer-learning
   ```

2. Abra o notebook no **Google Colab** ou em Jupyter Notebook.  

3. Baixe o dataset **Cats vs Dogs** do Kaggle ([link aqui](https://www.kaggle.com/datasets/tongpython/cat-and-dog)).  

4. Extraia o arquivo `.zip` em `/content/dataset` (se usar Colab) ou ajuste o caminho no notebook.  

5. Execute todas as células.  

---

## 📊 Resultados
- O modelo alcançou boa acurácia na classificação de gatos e cachorros.  
- O uso do **Transfer Learning** reduziu o tempo de treinamento.  
- Os gráficos de acurácia e perda mostram a evolução do aprendizado.  

---

## 📌 Conclusão
Este projeto demonstrou a eficácia do **Transfer Learning** em visão computacional.  
Reaproveitando redes pré-treinadas, conseguimos treinar um modelo robusto de classificação binária com menos dados e menor custo computacional.  

Essa técnica pode ser aplicada em diversos cenários reais:  
- 📷 Diagnóstico médico por imagem  
- 🚗 Sistemas de vigilância e segurança  
- 🛍️ Classificação de produtos em e-commerce  

---

✍️ Desenvolvido por [Seu Nome]
