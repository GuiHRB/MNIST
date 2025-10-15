# 🧠 Análise de Robustez de Redes Neurais com Dropout (MNIST)

## 📋 Breve Descrição do Projeto

Este projeto consiste em uma investigação sobre a **robustez e a eficácia do mecanismo de Dropout** como técnica de regularização em Redes Neurais Artificiais (RNAs) contra o **overfitting** e a **presença de ruído** nos dados.

O estudo utiliza o clássico dataset de dígitos manuscritos **MNIST**. Vários modelos de RNAs sequenciais foram treinados, cada um com uma **taxa de Dropout diferente** (variando de 0.1 a 0.5), para determinar qual taxa oferece o melhor equilíbrio entre:

1.  **Acurácia Máxima** (em dados limpos).
2.  **Estabilidade de Treinamento** (resistência ao *overfitting*).
3.  **Robustez** (capacidade de manter a alta acurácia em dados modificados com **ruído Gaussiano**).

Os resultados mostram que o **Dropout de 0.2** oferece o melhor ponto de equilíbrio, mantendo uma alta acurácia de $97.6\%$ e sofrendo a menor queda de performance em cenários ruidosos.

---

## 🚀 Como Executar o Projeto

O projeto está configurado para ser executado em um ambiente de notebook (Jupyter Notebook, Google Colab ou VS Code).

### Pré-requisitos

Certifique-se de que as seguintes bibliotecas Python estejam instaladas:

TensorFlow / Keras
NumPy	
Matplotlib
Scikit-learn
