# machine_learn_0414

Este repositório contém a implementação do algoritmo **K-Nearest Neighbors (KNN)** desenvolvido do zero, aplicado à classificação de tumores (Benigno vs. Maligno) com base em características clínicas.

## 📂 Conteúdo

* **tumores.csv**: Dataset contendo medidas de tamanho (cm) e pontuação de textura de diferentes amostras, acompanhadas de seu rótulo de classificação (0 para Benigno, 1 para Maligno).
* **knn.ipynb**: Notebook com a implementação completa do algoritmo, abrangendo:
    - **Cálculo de Distância**: Implementação da fórmula de Distância Euclidiana.
    - **Lógica do KNN**: Processo de identificação dos $k$ vizinhos mais próximos e votação majoritária para definição da classe.
    - **Visualização**: Gráficos gerados com Matplotlib que mostram a dispersão dos dados e destacam a "vizinhança" em torno de novos pontos a serem classificados, incluindo um círculo delimitador para facilitar a interpretação visual.

## 🛠️ Tecnologias e Bibliotecas

As ferramentas centrais utilizadas neste projeto são:

* **Python 3**: Linguagem base.
* **NumPy**: Manipulação de arrays e cálculos de distância.
* **Matplotlib**: Visualização de dados e plotagem da vizinhança.
* **Collections (Counter)**: Utilizada para a contagem eficiente dos votos dos vizinhos.
* **Jupyter Notebook**: Ambiente interativo para execução dos experimentos.

## 🚀 Como começar

1.  Clone este repositório:
    ```bash
    git clone https://github.com/felipe-r-regiani/machine_learn_0414.git
    ```
2.  Instale as dependências:
    ```bash
    pip install numpy matplotlib
    ```
3.  Execute o notebook:
    - Abra o arquivo `knn.ipynb`.
    - Experimente alterar o valor de $k$ no código para observar como a classificação do "Novo Tumor" se comporta graficamente.
