# Aplicacao-de-Machine-Learning-em-Dados-Imobiliarios

## Projeto de Análise de Dados e Modelagem Preditiva

Este projeto realiza a análise de dados, tratamento de dados, análise exploratória, modelagem preditiva e sugestões de investimento com base em um conjunto de dados de acomodações.

### Estrutura do Projeto

- `lh_cd_gessicassilva.ipynb`: Notebook Jupyter contendo todas as etapas de análise e modelagem.
- `filtered_data.csv`: Conjunto de dados filtrado utilizado na modelagem.
- `optimized_model.pkl`: Modelo preditivo otimizado salvo.
- `geo_data_original.png`: Visualização da distribuição geográfica das acomodações.

### Requisitos

Para executar este projeto, você precisará dos seguintes pacotes Python:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- nltk
- spacy
- geopandas
- contextily
- tabulate

Você pode instalar todos os pacotes necessários utilizando o arquivo `requirements.txt`.

### Instalação

1. Clone o repositório para sua máquina local:
    ```bash
    git clone <URL_DO_REPOSITORIO>
    ```
2. Navegue até o diretório do projeto:
    ```bash
    cd <NOME_DO_DIRETORIO>
    ```
3. Crie um ambiente virtual:
    ```bash
    python -m venv venv
    ```
4. Ative o ambiente virtual:
    - No Windows:
        ```bash
        venv\Scripts\activate
        ```
    - No macOS/Linux:
        ```bash
        source venv/bin/activate
        ```
5. Instale os pacotes necessários:
    ```bash
    pip install -r requirements.txt
    ```

### Execução

Para executar o projeto, basta abrir o Jupyter Notebook:
```bash
jupyter notebook lh_cd_gessicassilva.ipynb
