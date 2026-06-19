# Materiais Suplementares: Integrando Dados Textuais e Estruturados para Compreender Fatores Associados à Infrequência Escolar

Este repositório atua como um guia complementar para os leitores do artigo submetido ao KDMiLe (Symposium on Knowledge Discovery, Mining and Learning). O foco é apresentar de forma transparente os artefatos técnicos, dicionários e tabelas estatísticas geradas ao longo do processo de Descoberta de Conhecimento em Bases de Dados (KDD) aplicado ao sistema Ficha de Comunicação de Aluno Infrequente (FICAI).

Devido a diretrizes rigorosas de privacidade e proteção de dados (LGPD) envolvendo informações de menores de idade, a base de dados transacional e as narrativas textuais completas não podem ser disponibilizadas publicamente. Este ambiente contém exclusivamente métricas probabilísticas, padrões matemáticos agregados e as estruturas metodológicas do estudo.

---

## 📂 Dados e Resultados Agregados

Os artefatos abaixo detalham as duas principais etapas analíticas da pesquisa: a extração de conceitos matemáticos dos textos não estruturados e o cruzamento probabilístico desses conceitos com os dados demográficos.

### 1. Dicionário de Variáveis Latentes (NLP)
A primeira etapa metodológica empregou o algoritmo Latent Dirichlet Allocation (LDA) para extrair os temas subjacentes documentados em texto livre pela rede de proteção. O link abaixo demonstra a composição técnica dos 30 agrupamentos semânticos isolados pelo modelo.

* 📄 **[Dicionário de Tópicos e Palavras Mais Frequentes (Bag-of-Words)](https://github.com/samuelsilva/Mestrado_kdmile_data/blob/master/Palavras_por_topico.md)**

### 2. Mineração de Padrões Interseccionais
A segunda etapa aplicou o algoritmo FP-Growth para buscar padrões determinísticos entre a "tríade pedagógica" (diagnósticos de múltipla escolha das escolas) e os reais fatores exógenos mapeados no texto. O link a seguir apresenta as regras consolidadas, parametrizadas para contornar o Problema do Item Raro.

* 📄 **[Tabelas de Regras de Associação (Correlações Positivas e Negativas)](https://github.com/samuelsilva/Mestrado_kdmile_data/blob/master/Regras_associacao.md)**

---

## 💻 Códigos Fonte e Reproducibilidade

*(Em breve)*

Esta seção será atualizada com os scripts em Python detalhando os fluxos de engenharia de dados, parametrização dos modelos e filtragem estatística, demonstrando o pipeline de ponta a ponta.

* `[01_pre_processamento_e_nlp.ipynb - Link a ser adicionado]`
* `[02_modelagem_de_topicos_lda.ipynb - Link a ser adicionado]`
* `[03_regras_de_associacao_fpgrowth.ipynb - Link a ser adicionado]`

---

## 🛠️ Tecnologias Utilizadas

* **Linguagem:** Python
* **Processamento de Linguagem Natural:** `spaCy`, `Gensim`
* **Mineração de Regras:** `pandas`, `mlxtend`
* **Infraestrutura:** Cluster de processamento de alto desempenho orquestrado via gerenciador SLURM.
