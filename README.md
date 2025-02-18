# Previsão K-Means para Segmentação de Mercado

Este projeto utiliza o algoritmo de clusterização K-Means para segmentar clientes com base em seus padrões de comportamento, proporcionando insights para estratégias de marketing mais eficientes.

## Acesso à Aplicação

Acesse a aplicação online para testar a segmentação de dados:

[Previsão K-Means Marketing](https://previsao-kmeans-marketing-jgt5avx75hj9j4gtmuawmr.streamlit.app/)

## Visão Geral

O projeto agrupa clientes com características semelhantes para otimizar campanhas de marketing e personalizar abordagens comerciais. Com isso, empresas podem tomar decisões mais assertivas ao identificar padrões de consumo e preferências do público.

## Tecnologias Utilizadas

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Streamlit

## Funcionalidades

- Identificação de perfis de consumidores
- Segmentação automática via K-Means
- Visualização gráfica interativa dos grupos
- Upload de dados para análise em tempo real

## Como Testar a Aplicação

Para validar o funcionamento do modelo, utilize o dataset de exemplo `dados_test.csv`.

1. Faça o download do arquivo no repositório
2. Acesse a aplicação
3. Realize o upload do arquivo
4. Analise os agrupamentos gerados

## Executando Localmente

Para rodar o projeto em sua máquina:

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/previsao-kmeans-marketing.git
   cd previsao-kmeans-marketing
   ```
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Execute a aplicação:
   ```bash
   streamlit run src/app.py
   ```

Acesse a interface local em `http://localhost:8501/`.

## Processo de Segmentação

O K-Means identifica padrões e agrupa dados de acordo com proximidade matemática entre os pontos. As etapas do processo incluem:

1. Escolha do número de clusters (K)
2. Inicialização dos centróides
3. Atribuição de pontos aos centróides mais próximos
4. Reavaliação das posições dos centróides
5. Repetição até convergência dos agrupamentos

O modelo pode ser ajustado conforme novas análises e necessidades do usuário.

## Como Melhorar a Segmentação

- Testar diferentes valores de K
- Normalizar dados para melhor distribuição
- Analisar métricas de avaliação dos clusters


