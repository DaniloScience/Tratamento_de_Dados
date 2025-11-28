🏡 Base de Dados Imobiliária — Data Cleaning & Feature Engineering
📌 Objetivo do Projeto

Transformar um conjunto de dados imobiliários bruto em uma base limpa, estruturada e enriquecida, pronta para análises, visualizações e modelos de machine learning.

🧹 Etapas Realizadas
🔧 1. Padronização da Estrutura

Separação dos registros usando ; como delimitador.

Organização dos dados em 13 colunas padronizadas:

Tipo

Bairro

Quartos

Vagas

Suítes

Área

Valor

Condomínio

IPTU

Valor_por_mes

Valor_por_ano

Descricao

Possui_Suite

🧼 2. Tratamento de Valores Ausentes

Remoção de nulos explícitos.

Correção de campos vazios.

Garantia de 32960 registros sem valores faltantes.

🔍 3. Conversão de Tipos & Limpeza

Conversão de colunas numéricas que estavam como texto.

Normalização de categorias.

Ajuste de inconsistências após a separação dos campos.

🛠 4. Engenharia de Atributos

Criação de novas variáveis para enriquecer o dataset:

Valor_por_mes

Valor_por_ano

Possui_Suite (Sim/Não)

Descrição completa gerada automaticamente para cada imóvel.

📝 5. Enriquecimento Textual

Criação de descrições padronizadas utilizando os atributos do imóvel.

Preparação para análises baseadas em texto ou NLP.

📊 Resultado Final

Base completa, limpa e consistente.

Pronta para:

Análise exploratória

Visualização de dados

Modelagem preditiva

Criação de dashboards

📁 Arquivos do Repositório

dados_completos_dev.csv — Base final tratada.
