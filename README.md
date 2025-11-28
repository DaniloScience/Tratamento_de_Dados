🏡 Base de Dados Imobiliária — Data Cleaning & Feature Engineering

Um projeto de limpeza, padronização e enriquecimento de dados imobiliários, transformando um dataset bruto em uma base estruturada, consistente e pronta para análises avançadas.

🧭 Objetivo

Criar um dataset totalmente limpo e organizado, aplicando:

Tratamento de valores ausentes

Padronização estrutural

Conversão de tipos

Engenharia de atributos

Enriquecimento textual

Perfeito para análises, dashboards e modelos de Machine Learning.

🧹 1. Padronização da Estrutura

A base original estava unificada em uma única coluna com dados separados por ;.
Após processamento, os dados foram divididos corretamente em 13 colunas:

# Tipo

# Bairro

# Quartos

# Vagas

# Suítes

# Área

# Valor

# Condomínio

#IPTU

# Valor_por_mes

# Valor_por_ano

# Descricao

# Possui_Suite

🧼 2. Tratamento de Valores Ausentes

Remoção de valores nulos explícitos

Ajuste de campos vazios

Garantia de 32960 registros completos

🔧 3. Conversão e Limpeza dos Dados

Conversão de colunas numéricas armazenadas como texto

Normalização de categorias

Correção de inconsistências pós-separação

🛠 4. Engenharia de Atributos

Foram criadas novas variáveis para enriquecer o dataset:

# Valor_por_mes

# Valor_por_ano

# Possui_Suite

Descrição completa gerada automaticamente

📝 5. Enriquecimento Textual

Cada imóvel recebe uma descrição padronizada baseada em suas características, ideal para:

Análise textual

NLP

Busca e classificação

📊 Resultado Final

Dataset totalmente preparado para:

Análise exploratória (EDA)

Visualizações

Machine Learning

Criação de dashboards

📁 Arquivos do Repositório

dados_completos_dev.csv
 — Base final tratada
