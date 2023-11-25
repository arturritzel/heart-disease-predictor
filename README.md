# heart-disease-predictor
  Este algoritmo realiza a previsão de uma pessoa ter a tendência de desenvolver algum tipo de doença cardíaca com base em alguns fatores clínicos e laboratoriais. Projeto utilizado como base para estudo de inteligência artificial, machine learning, deep learning, estrutura de dados, etc.
  

## arquivos

### tratamento
**1_tratamento.ipynb**
- Abre o arquivo contendo os dados dos pacientes. Analisa informação por informação em busca de dados incondizentes que possam dificultar, fragilizar ou diminuir a eficácia do código, e trata os valores quando necessário.

**2_preprocessamento_treino_testes.ipynb**
- Pré-processa os dados. Separa os dados de previsores/alvo de diferentes formas e testa em aproximadamente 10 modelos de deep learning de aprendizado supervisionado (classificação), buscando o melhor modelo possível com o melhor formato de dados. Ao final, exporta os dados tratados.

**3_simulador.ipynb**
- Através do tratamento e análise dos códigos anteriores, esse código interpreta informações de novos pacientes fictícios e informa a presença da tendência ou não de desenvolvimento de doença cardíaca com (baseando-se na tabela de dados disponível) 87.13% de acurácia.

**heart.csv**
- Dados para análise: informações médicas sobre pacientes testados sobre doenças cardíacas

**heart_tratado.csv**
- heart.csv depois da análise e tratamento de dados incondizentes e prejudiciais
