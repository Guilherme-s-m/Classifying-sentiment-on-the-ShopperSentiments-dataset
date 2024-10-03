Aqui está o `README.md` atualizado de acordo com as informações fornecidas:

---

# Análise de Sentimentos no Dataset TeePublic_review

Este projeto realiza uma análise exploratória sobre as avaliações presentes no dataset **TeePublic_review**, com foco na distribuição de ratings. Aplicamos técnicas de visualização de dados para extrair insights valiosos sobre o comportamento dos consumidores, analisando os diferentes níveis de ratings.

Para uma descrição completa do projeto e metodologia, consulte o arquivo `analysis.ipynb`.

## Funcionalidades

1. Carregamento e pré-processamento de dados do dataset TeePublic_review
2. Análise exploratória da distribuição de ratings
3. Visualização dos dados usando gráficos para entender padrões nos sentimentos expressos pelos usuários
4. Implementação de um pipeline de classificação usando TF-IDF e Regressão Logística para análise de sentimentos
5. Avaliação do impacto do tamanho do dataset no desempenho do modelo
6. Análise de tópicos usando LDA (Latent Dirichlet Allocation) para identificar temas centrais nas avaliações dos usuários

## Requisitos

- Python 3.7+
- Jupyter Notebook
- Dependências listadas no arquivo `requirements.txt`

## Instalação

1. Clone este repositório:
   ```bash
   git clone https://github.com/Guilherme-s-m/Classifying-sentiment-on-the-ShopperSentiments-dataset.git
   cd Classifying-sentiment-on-the-ShopperSentiments-dataset
   ```

2. (Opcional, mas recomendado) Crie e ative um ambiente virtual:
   ```bash
   python -m venv venv
   source venv/bin/activate  # No Windows use `venv\Scripts\activate`
   ```

3. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```

## Uso

1. Verifique se o dataset **TeePublic_review** está localizado no diretório `data/`.

2. Inicie o Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

3. Abra o arquivo `analysis.ipynb` no navegador e execute as células do notebook para realizar as análises e gerar os insights.

## Estrutura do Projeto

- `analysis.ipynb`: Notebook Jupyter contendo todo o código e análises
- `data/`: Diretório contendo o dataset TeePublic_review
- `requirements.txt`: Lista de dependências do projeto
- `Classifying_sentiment_on_the_TeePublic_review_dataset.pdf`: Artigo referente à análise
- `models/`: Modelos treinados a serem salvos

---

Este `README.md` está alinhado com as funcionalidades e a estrutura do seu projeto, refletindo a análise exploratória do dataset TeePublic_review e a ausência de um classificador de duas camadas.