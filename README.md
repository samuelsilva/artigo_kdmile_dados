# Materiais Suplementares: Integrando Dados Textuais e Estruturados para Compreender Fatores Associados à Infrequência Escolar

Este repositório atua como um guia complementar para os leitores do artigo submetido ao KDMiLe (Symposium on Knowledge Discovery, Mining and Learning). O foco é apresentar de forma transparente os artefatos técnicos, dicionários e tabelas estatísticas gerados ao longo do processo de Descoberta de Conhecimento em Bases de Dados (KDD) aplicado ao sistema Ficha de Comunicação de Aluno Infrequente (FICAI).

Devido a diretrizes rigorosas de privacidade e proteção de dados (LGPD) envolvendo informações de menores de idade, a base de dados transacional e as narrativas textuais completas não podem ser disponibilizadas publicamente. Este ambiente contém exclusivamente métricas probabilísticas, padrões matemáticos agregados e as estruturas metodológicas do estudo.

---

## 📂 Dados e Resultados Agregados

Os artefatos abaixo detalham as duas principais etapas analíticas da pesquisa: a extração de conceitos matemáticos dos textos não estruturados e o cruzamento probabilístico desses conceitos com os dados demográficos.

### 1. Dicionário de Variáveis Latentes (NLP)
A primeira etapa metodológica empregou o algoritmo Latent Dirichlet Allocation (LDA) para extrair os temas subjacentes documentados em texto livre pela rede de proteção. O link abaixo demonstra a composição técnica dos 30 agrupamentos semânticos isolados pelo modelo.

* 📄 **[Dicionário de Tópicos e Palavras Mais Frequentes (Bag-of-Words)](https://github.com/samuelsilva/Mestrado_kdmile_data/blob/master/Palavras_por_topico.md)**

### 2. Mineração de Padrões Interseccionais
A segunda etapa aplicou o algoritmo FP-Growth para buscar padrões determinísticos entre os diagnósticos estruturados das escolas (incluindo a "tríade pedagógica") e os reais fatores exógenos mapeados no texto. O cruzamento foi estruturado em duas frentes: uma visão global e uma análise segmentada por etapa de ensino, evidenciando como os determinantes da evasão se transformam à medida que o aluno avança no sistema. Todas as regras foram parametrizadas com suporte mínimo rigoroso para contornar o Problema do Item Raro.

* 📄 **[Tabelas de Regras de Associação: Tríade X Tópicos, Diagnósticos X Tópicos, Geral ](https://github.com/samuelsilva/Mestrado_kdmile_data/blob/master/Regras_associacao.md)**
* 📄 **[Tabelas de Regras de Associação: Evolução por Etapa Escolar (Ano a Ano)](https://github.com/samuelsilva/Mestrado_kdmile_data/blob/master/regras_associacao_etapa_ensino.md
)**


---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Processamento de Linguagem Natural:** `spaCy`, `Gensim`
* **Mineração de Regras:** `pandas`, `mlxtend`
* **Infraestrutura:** Cluster de processamento de alto desempenho orquestrado via gerenciador SLURM.
