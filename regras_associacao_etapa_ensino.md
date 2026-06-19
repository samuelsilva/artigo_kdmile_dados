# Regras de Associação: Fatores de Evasão por Etapa de Ensino (FICAI)

Este documento apresenta o detalhamento das Regras de Associação (algoritmo FP-Growth) segmentadas por etapa escolar do estudante. O objetivo é demonstrar como os fatores de atração e repulsão entre os diagnósticos institucionais e as variáveis latentes da evasão se transformam ao longo do desenvolvimento do aluno.

---

## ENSINO MÉDIO - 1º ANO
**Total de Alunos Únicos:** 15.934

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | GESTACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 10.97x | 0.8% | 48.4% |
| 02 | FILHO_PEQUENO_SEM_CRECHE -> Gravidez_Adolescente_e_Cuidados_Bebes | 9.80x | 0.3% | 43.2% |
| 03 | ENSINO_MEDIO -> Transferencia_Escolar_Bairro_Vaga | 9.60x | 0.2% | 56.9% |
| 04 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Violencia_Drogas_Rua_e_Fuga | 9.04x | 0.2% | 36.6% |
| 05 | VIOLENCIA_ENTORNO_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 7.56x | 0.2% | 30.6% |
| 06 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 6.47x | 1.1% | 30.5% |
| 07 | ENSINO_MEDIO -> Mudanca_de_Cidade_e_Municipio | 6.39x | 0.1% | 31.4% |
| 08 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Gravidez_Adolescente_e_Cuidados_Bebes | 6.33x | 0.5% | 27.9% |
| 09 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Saude_Mental_Psicologico_e_Depressao | 5.74x | 3.9% | 36.2% |
| 10 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 5.56x | 0.4% | 26.2% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | NECESSIDADE_DE_CUIDADOS_FAMILIA -> Desinteresse_Geral_e_Desmotivacao | 0.40x | 0.2% | 5.3% |
| 02 | GESTACAO -> Trabalho_Precoce_e_EJA_Noturno | 0.41x | 0.1% | 7.9% |
| 03 | TRABALHO -> Saude_Mental_Psicologico_e_Depressao | 0.43x | 0.6% | 2.7% |
| 04 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Desinteresse_Geral_e_Desmotivacao | 0.46x | 0.1% | 6.2% |
| 05 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Faltas_Intercaladas_Sem_Justificativa | 0.49x | 0.1% | 7.6% |
| 06 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Trabalho_Precoce_e_EJA_Noturno | 0.50x | 0.1% | 9.8% |
| 07 | FALTA_DE_TRANSPORTE_ESCOLAR -> Desinteresse_Geral_e_Desmotivacao | 0.50x | 0.2% | 6.7% |
| 08 | GESTACAO -> Faltas_Intercaladas_Sem_Justificativa | 0.51x | 0.1% | 7.9% |
| 09 | TRABALHO -> Afastamento_Medico_Doenca_Aguda | 0.52x | 0.6% | 2.6% |
| 10 | FALTA_DE_RECURSOS -> Trabalho_Precoce_e_EJA_Noturno | 0.53x | 0.1% | 10.5% |
| 11 | FALTA_DE_TRANSPORTE_ESCOLAR -> Saude_Mental_Psicologico_e_Depressao | 0.55x | 0.1% | 3.5% |
| 12 | SAUDE_FISICA_MENTAL_FAMILIA -> Desinteresse_Geral_e_Desmotivacao | 0.55x | 0.1% | 7.3% |
| 13 | NECESSIDADE_DE_CUIDADOS_FAMILIA -> Verificacao_de_Historico_e_Bolsas | 0.55x | 0.3% | 8.2% |
| 14 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Trabalho_Precoce_e_EJA_Noturno | 0.56x | 1.2% | 10.9% |
| 15 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Baixa_Frequencia_Trimestral | 0.61x | 0.1% | 7.6% |

---

## ENSINO MÉDIO - 2º ANO
**Total de Alunos Únicos:** 6.630

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | ENSINO_MEDIO -> Transferencia_Escolar_Bairro_Vaga | 18.89x | 0.2% | 100.0% |
| 02 | VIOLENCIA_ENTORNO_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 11.49x | 0.2% | 44.0% |
| 03 | GESTACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 11.01x | 0.8% | 50.0% |
| 04 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 7.41x | 0.9% | 30.7% |
| 05 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 7.39x | 0.3% | 30.7% |
| 06 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Violencia_Drogas_Rua_e_Fuga | 7.12x | 0.1% | 27.3% |
| 07 | RELACIONAMENTO_NA_ESCOLA -> Comportamento_Indisciplina_Conflito | 6.51x | 0.4% | 43.3% |
| 08 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Gravidez_Adolescente_e_Cuidados_Bebes | 6.51x | 0.7% | 29.6% |
| 09 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Saude_Mental_Psicologico_e_Depressao | 5.50x | 4.0% | 36.2% |
| 10 | FILHO_PEQUENO_SEM_CRECHE -> Gravidez_Adolescente_e_Cuidados_Bebes | 5.14x | 0.2% | 23.3% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | TRABALHO -> Saude_Mental_Psicologico_e_Depressao | 0.38x | 0.7% | 2.5% |
| 02 | TRABALHO -> Afastamento_Medico_Doenca_Aguda | 0.38x | 0.5% | 1.9% |
| 03 | SAUDE_FISICA_MENTAL_FAMILIA -> Trabalho_Precoce_e_EJA_Noturno | 0.41x | 0.2% | 9.2% |
| 04 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Desinteresse_Geral_e_Desmotivacao | 0.48x | 0.2% | 6.3% |
| 05 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Trabalho_Precoce_e_EJA_Noturno | 0.50x | 0.2% | 11.2% |
| 06 | GESTACAO -> Desinteresse_Geral_e_Desmotivacao | 0.50x | 0.1% | 6.6% |
| 07 | GESTACAO -> Trabalho_Precoce_e_EJA_Noturno | 0.54x | 0.2% | 12.3% |
| 08 | SAUDE_FISICA_MENTAL_FAMILIA -> Atingimento_Idade_Maioridade_Ensino_Medio | 0.55x | 0.1% | 6.4% |
| 09 | SAUDE_FISICA_MENTAL_FAMILIA -> Desinteresse_Geral_e_Desmotivacao | 0.56x | 0.1% | 7.3% |
| 10 | TRABALHO -> Violencia_Drogas_Rua_e_Fuga | 0.58x | 0.6% | 2.2% |
| 11 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Trabalho_Precoce_e_EJA_Noturno | 0.59x | 1.4% | 13.3% |
| 12 | NECESSIDADE_DE_CUIDADOS_FAMILIA -> Desinteresse_Geral_e_Desmotivacao | 0.59x | 0.3% | 7.8% |
| 13 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Faltas_Intercaladas_Sem_Justificativa | 0.59x | 0.1% | 9.0% |
| 14 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Conflito_Relacionamento_Professores_Turma | 0.60x | 0.1% | 10.7% |
| 15 | NECESSIDADE_DE_CUIDADOS_FAMILIA -> Promessas_Quebradas_de_Retorno | 0.61x | 0.2% | 5.0% |

---

## ENSINO MÉDIO - 3º ANO
**Total de Alunos Únicos:** 1.786

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | ENSINO_MEDIO -> Transferencia_Escolar_Bairro_Vaga | 15.95x | 0.1% | 100.0% |
| 02 | NAO_OFERTA_DE_EDUCACAO_ESPECIAL -> Saude_Mental_Psicologico_e_Depressao | 10.26x | 0.1% | 50.0% |
| 03 | GESTACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 9.82x | 1.3% | 56.1% |
| 04 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Transferencia_Escolar_Bairro_Vaga | 8.86x | 0.3% | 55.6% |
| 05 | NAO_OFERTA_DE_EDUCACAO_ESPECIAL -> Gravidez_Adolescente_e_Cuidados_Bebes | 8.75x | 0.1% | 50.0% |
| 06 | VIOLENCIA_ENTORNO_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 8.64x | 0.2% | 30.0% |
| 07 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 6.92x | 0.8% | 33.3% |
| 08 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 6.92x | 0.3% | 33.3% |
| 09 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Violencia_Drogas_Rua_e_Fuga | 6.65x | 0.2% | 23.1% |
| 10 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Saude_Mental_Psicologico_e_Depressao | 5.63x | 3.3% | 27.4% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | SAUDE_FISICA_MENTAL_FAMILIA -> Trabalho_Precoce_e_EJA_Noturno | 0.28x | 0.1% | 5.3% |
| 02 | NECESSIDADE_DE_CUIDADOS_FAMILIA -> Faltas_Intercaladas_Sem_Justificativa | 0.35x | 0.2% | 5.3% |
| 03 | TRABALHO -> Saude_Mental_Psicologico_e_Depressao | 0.36x | 0.4% | 1.8% |
| 04 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Baixa_Frequencia_Trimestral | 0.38x | 0.1% | 5.3% |
| 05 | SAUDE_FISICA_MENTAL_FAMILIA -> Desinteresse_Geral_e_Desmotivacao | 0.40x | 0.1% | 5.3% |
| 06 | GESTACAO -> Conflito_Relacionamento_Professores_Turma | 0.43x | 0.2% | 7.3% |
| 07 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Trabalho_Precoce_e_EJA_Noturno | 0.44x | 0.1% | 8.3% |
| 08 | TRABALHO -> Violencia_Drogas_Rua_e_Fuga | 0.45x | 0.4% | 1.6% |
| 09 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Relatorio_Busca_Ativa_Porto_Alegre | 0.46x | 0.2% | 1.9% |
| 10 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Conflito_Relacionamento_Professores_Turma | 0.46x | 0.2% | 7.9% |
| 11 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Mudanca_de_Cidade_e_Municipio | 0.47x | 0.3% | 2.8% |
| 12 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Conflito_Relacionamento_Professores_Turma | 0.49x | 0.1% | 8.3% |
| 13 | GESTACAO -> Faltas_Intercaladas_Sem_Justificativa | 0.49x | 0.2% | 7.3% |
| 14 | FALTA_DE_RECURSOS -> Dialogos_Informais_Pedidos_de_Transferencia | 0.49x | 0.1% | 9.5% |
| 15 | NECESSIDADE_DE_CUIDADOS_FAMILIA -> Promessas_Quebradas_de_Retorno | 0.50x | 0.2% | 3.9% |

---

## ENSINO FUNDAMENTAL - 1º ANO
**Total de Alunos Únicos:** 6.237

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | NAO_OFERTA_DE_EDUCACAO_ESPECIAL -> Saude_Mental_Psicologico_e_Depressao | 9.76x | 0.3% | 85.0% |
| 02 | VIOLENCIA_ENTORNO_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 8.35x | 0.2% | 21.2% |
| 03 | TRABALHO -> Trabalho_Precoce_e_EJA_Noturno | 7.70x | 1.1% | 28.5% |
| 04 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Violencia_Drogas_Rua_e_Fuga | 7.00x | 0.4% | 17.7% |
| 05 | RELACIONAMENTO_NA_ESCOLA -> Comportamento_Indisciplina_Conflito | 4.92x | 0.3% | 43.6% |
| 06 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Transferencia_Escolar_Bairro_Vaga | 4.59x | 2.6% | 77.1% |
| 07 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 3.90x | 1.5% | 24.5% |
| 08 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 3.88x | 0.6% | 24.3% |
| 09 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Desastre_Climatico_Enchente_Retorno_Adiado | 3.56x | 1.5% | 38.1% |
| 10 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Saude_Mental_Psicologico_e_Depressao | 3.33x | 4.1% | 29.0% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Faltas_Intercaladas_Sem_Justificativa | 0.22x | 0.2% | 4.7% |
| 02 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Afastamento_Medico_Doenca_Aguda | 0.28x | 0.1% | 3.7% |
| 03 | TRABALHO -> Afastamento_Medico_Doenca_Aguda | 0.31x | 0.2% | 4.0% |
| 04 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Relatorio_Busca_Ativa_Porto_Alegre | 0.41x | 0.2% | 1.4% |
| 05 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Mudanca_de_Cidade_e_Municipio | 0.42x | 0.4% | 3.0% |
| 06 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Dificuldade_Aprendizagem_e_Rotina | 0.43x | 0.3% | 7.5% |
| 07 | FALTA_DE_TRANSPORTE_ESCOLAR -> Saude_Mental_Psicologico_e_Depressao | 0.45x | 0.2% | 3.9% |
| 08 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Afastamento_Medico_Doenca_Aguda | 0.47x | 0.2% | 6.1% |
| 09 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Transferencia_Escolar_Bairro_Vaga | 0.47x | 1.1% | 7.8% |
| 10 | SAUDE_FISICA_MENTAL_FAMILIA -> Abandono_Logo_Apos_Matricula | 0.49x | 0.2% | 3.8% |
| 11 | FALTA_DE_TRANSPORTE_ESCOLAR -> Promessas_Quebradas_de_Retorno | 0.51x | 0.2% | 2.9% |
| 12 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Baixa_Frequencia_Trimestral | 0.51x | 0.2% | 7.4% |
| 13 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Comportamento_Indisciplina_Conflito | 0.53x | 0.2% | 4.7% |
| 14 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Comportamento_Indisciplina_Conflito | 0.53x | 0.1% | 4.7% |
| 15 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Saude_Mental_Psicologico_e_Depressao | 0.54x | 0.2% | 4.7% |

---

## ENSINO FUNDAMENTAL - 2º ANO
**Total de Alunos Únicos:** 4.759

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | VIOLENCIA_ENTORNO_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 9.58x | 0.3% | 29.8% |
| 02 | TRABALHO -> Trabalho_Precoce_e_EJA_Noturno | 7.71x | 0.7% | 21.4% |
| 03 | GESTACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 7.13x | 0.2% | 66.7% |
| 04 | NAO_OFERTA_DE_EDUCACAO_ESPECIAL -> Saude_Mental_Psicologico_e_Depressao | 6.96x | 0.1% | 54.5% |
| 05 | RELACIONAMENTO_NA_ESCOLA -> Comportamento_Indisciplina_Conflito | 6.28x | 0.4% | 50.0% |
| 06 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Violencia_Drogas_Rua_e_Fuga | 6.11x | 0.4% | 19.0% |
| 07 | RELACIONAMENTO_NA_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 5.36x | 0.1% | 16.7% |
| 08 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 4.56x | 0.6% | 27.0% |
| 09 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Transferencia_Escolar_Bairro_Vaga | 4.25x | 2.6% | 76.2% |
| 10 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 4.03x | 1.4% | 23.9% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Afastamento_Medico_Doenca_Aguda | 0.24x | 0.1% | 3.0% |
| 02 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Saude_Mental_Psicologico_e_Depressao | 0.29x | 0.1% | 2.3% |
| 03 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Dificuldade_Aprendizagem_e_Rotina | 0.31x | 0.2% | 6.1% |
| 04 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Faltas_Intercaladas_Sem_Justificativa | 0.31x | 0.2% | 6.7% |
| 05 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Afastamento_Medico_Doenca_Aguda | 0.32x | 0.2% | 4.1% |
| 06 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Afastamento_Medico_Doenca_Aguda | 0.39x | 0.1% | 5.0% |
| 07 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Mudanca_de_Cidade_e_Municipio | 0.39x | 0.4% | 3.2% |
| 08 | FALTA_DE_TRANSPORTE_ESCOLAR -> Promessas_Quebradas_de_Retorno | 0.41x | 0.1% | 2.4% |
| 09 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Desastre_Climatico_Enchente_Retorno_Adiado | 0.42x | 0.1% | 5.0% |
| 10 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Transferencia_Escolar_Bairro_Vaga | 0.48x | 1.2% | 8.6% |
| 11 | SAUDE_FISICA_MENTAL_FAMILIA -> Mudanca_de_Cidade_e_Municipio | 0.50x | 0.3% | 4.1% |
| 12 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Faltas_Intercaladas_Sem_Justificativa | 0.51x | 0.2% | 11.0% |
| 13 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Faltas_Intercaladas_Sem_Justificativa | 0.53x | 0.5% | 11.5% |
| 14 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Verificacao_de_Historico_e_Bolsas | 0.53x | 0.3% | 7.3% |
| 15 | VIOLENCIA_ENTORNO_ESCOLA -> Dificuldade_Aprendizagem_e_Rotina | 0.54x | 0.1% | 10.6% |

---

## ENSINO FUNDAMENTAL - 3º ANO
**Total de Alunos Únicos:** 5.719

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | NAO_OFERTA_DE_EDUCACAO_ESPECIAL -> Saude_Mental_Psicologico_e_Depressao | 9.49x | 0.2% | 83.3% |
| 02 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Violencia_Drogas_Rua_e_Fuga | 6.33x | 0.7% | 24.7% |
| 03 | VIOLENCIA_ENTORNO_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 6.31x | 0.3% | 24.6% |
| 04 | RELACIONAMENTO_NA_ESCOLA -> Comportamento_Indisciplina_Conflito | 6.01x | 0.6% | 56.1% |
| 05 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 5.45x | 2.0% | 32.4% |
| 06 | TRABALHO -> Trabalho_Precoce_e_EJA_Noturno | 5.40x | 0.2% | 10.6% |
| 07 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 5.39x | 0.7% | 32.0% |
| 08 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Transferencia_Escolar_Bairro_Vaga | 4.57x | 2.8% | 81.7% |
| 09 | RELACIONAMENTO_NA_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 3.60x | 0.1% | 14.0% |
| 10 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Desastre_Climatico_Enchente_Retorno_Adiado | 3.45x | 1.8% | 40.6% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Afastamento_Medico_Doenca_Aguda | 0.21x | 0.1% | 2.4% |
| 02 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Baixa_Frequencia_Trimestral | 0.34x | 0.1% | 4.7% |
| 03 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Faltas_Intercaladas_Sem_Justificativa | 0.35x | 0.3% | 8.1% |
| 04 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Gravidez_Adolescente_e_Cuidados_Bebes | 0.37x | 0.1% | 3.0% |
| 05 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Comportamento_Indisciplina_Conflito | 0.38x | 0.1% | 3.6% |
| 06 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Baixa_Frequencia_Trimestral | 0.41x | 0.2% | 5.6% |
| 07 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Verificacao_de_Historico_e_Bolsas | 0.41x | 0.2% | 6.1% |
| 08 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Mudanca_de_Cidade_e_Municipio | 0.43x | 0.5% | 3.8% |
| 09 | FALTA_DE_TRANSPORTE_ESCOLAR -> Violencia_Drogas_Rua_e_Fuga | 0.44x | 0.1% | 1.7% |
| 10 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Saude_Mental_Psicologico_e_Depressao | 0.46x | 0.2% | 4.0% |
| 11 | FALTA_DE_TRANSPORTE_ESCOLAR -> Comportamento_Indisciplina_Conflito | 0.46x | 0.3% | 4.3% |
| 12 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Baixa_Frequencia_Trimestral | 0.46x | 0.2% | 6.3% |
| 13 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Dificuldade_Aprendizagem_e_Rotina | 0.47x | 0.3% | 9.6% |
| 14 | FALTA_DE_TRANSPORTE_ESCOLAR -> Saude_Mental_Psicologico_e_Depressao | 0.49x | 0.3% | 4.3% |
| 15 | FALTA_DE_TRANSPORTE_ESCOLAR -> Afastamento_Medico_Doenca_Aguda | 0.49x | 0.3% | 5.7% |

---

## ENSINO FUNDAMENTAL - 4º ANO
**Total de Alunos Únicos:** 4.353

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | NAO_OFERTA_DE_EDUCACAO_ESPECIAL -> Saude_Mental_Psicologico_e_Depressao | 7.29x | 0.2% | 70.0% |
| 02 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Transferencia_Escolar_Bairro_Vaga | 5.23x | 2.4% | 82.4% |
| 03 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Violencia_Drogas_Rua_e_Fuga | 5.08x | 0.5% | 21.7% |
| 04 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 4.38x | 0.4% | 28.4% |
| 05 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 4.35x | 1.6% | 28.2% |
| 06 | RELACIONAMENTO_NA_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 4.11x | 0.3% | 17.6% |
| 07 | RELACIONAMENTO_NA_ESCOLA -> Comportamento_Indisciplina_Conflito | 4.06x | 0.7% | 40.5% |
| 08 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Saude_Mental_Psicologico_e_Depressao | 3.61x | 5.1% | 34.6% |
| 09 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Desastre_Climatico_Enchente_Retorno_Adiado | 3.54x | 1.4% | 36.0% |
| 10 | RELACIONAMENTO_NA_ESCOLA -> Saude_Mental_Psicologico_e_Depressao | 3.52x | 0.6% | 33.8% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Faltas_Intercaladas_Sem_Justificativa | 0.26x | 0.2% | 5.6% |
| 02 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Afastamento_Medico_Doenca_Aguda | 0.27x | 0.1% | 3.0% |
| 03 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Verificacao_de_Historico_e_Bolsas | 0.36x | 0.2% | 5.6% |
| 04 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Comportamento_Indisciplina_Conflito | 0.37x | 0.1% | 3.7% |
| 05 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Baixa_Frequencia_Trimestral | 0.41x | 0.2% | 5.6% |
| 06 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Dificuldade_Aprendizagem_e_Rotina | 0.49x | 0.3% | 9.6% |
| 07 | FALTA_DE_TRANSPORTE_ESCOLAR -> Promessas_Quebradas_de_Retorno | 0.49x | 0.2% | 3.2% |
| 08 | RELACIONAMENTO_NA_ESCOLA -> Baixa_Frequencia_Trimestral | 0.50x | 0.1% | 6.8% |
| 09 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Mudanca_de_Cidade_e_Municipio | 0.51x | 0.6% | 4.1% |
| 10 | FALTA_DE_TRANSPORTE_ESCOLAR -> Direito_ao_Estudo_e_Medidas_da_Secretaria | 0.52x | 0.2% | 2.8% |
| 11 | TRABALHO -> Baixa_Frequencia_Trimestral | 0.54x | 0.1% | 7.3% |
| 12 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Baixa_Frequencia_Trimestral | 0.54x | 0.3% | 7.3% |
| 13 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Verificacao_de_Historico_e_Bolsas | 0.55x | 0.2% | 8.5% |
| 14 | FALTA_DE_TRANSPORTE_ESCOLAR -> Resistencia_a_Atividades_Propostas | 0.57x | 0.2% | 3.2% |
| 15 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Transferencia_Escolar_Bairro_Vaga | 0.58x | 1.3% | 9.1% |

---

## ENSINO FUNDAMENTAL - 5º ANO
**Total de Alunos Únicos:** 4.534

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | GESTACAO -> Violencia_Drogas_Rua_e_Fuga | 7.89x | 0.1% | 38.5% |
| 02 | ENSINO_FUNDAMENTAL_ANOS_FINAIS -> Transferencia_Escolar_Bairro_Vaga | 6.91x | 0.2% | 100.0% |
| 03 | GESTACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 6.25x | 0.1% | 38.5% |
| 04 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 6.15x | 1.2% | 30.0% |
| 05 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 5.77x | 0.4% | 28.1% |
| 06 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Transferencia_Escolar_Bairro_Vaga | 5.48x | 1.9% | 79.3% |
| 07 | NAO_OFERTA_DE_EDUCACAO_ESPECIAL -> Saude_Mental_Psicologico_e_Depressao | 5.02x | 0.1% | 50.0% |
| 08 | VIOLENCIA_ENTORNO_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 4.77x | 0.2% | 23.3% |
| 09 | TRABALHO -> Trabalho_Precoce_e_EJA_Noturno | 4.71x | 0.3% | 17.0% |
| 10 | RELACIONAMENTO_NA_ESCOLA -> Comportamento_Indisciplina_Conflito | 4.63x | 0.7% | 45.7% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Faltas_Intercaladas_Sem_Justificativa | 0.25x | 0.1% | 5.4% |
| 02 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Baixa_Frequencia_Trimestral | 0.41x | 0.1% | 5.4% |
| 03 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Baixa_Frequencia_Trimestral | 0.45x | 0.2% | 6.0% |
| 04 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Dificuldade_Acordar_Faltas_Matutinas | 0.45x | 0.3% | 11.7% |
| 05 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Conflito_Relacionamento_Professores_Turma | 0.46x | 0.2% | 9.0% |
| 06 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Dificuldade_Aprendizagem_e_Rotina | 0.48x | 0.2% | 9.0% |
| 07 | RELACIONAMENTO_NA_ESCOLA -> Transferencia_Escolar_Bairro_Vaga | 0.49x | 0.1% | 7.1% |
| 08 | FALTA_DE_TRANSPORTE_ESCOLAR -> Negligencia_Familiar_e_Drogas_no_Nucleo | 0.50x | 0.1% | 2.8% |
| 09 | FALTA_DE_RECURSOS -> Gravidez_Adolescente_e_Cuidados_Bebes | 0.50x | 0.1% | 3.1% |
| 10 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Dificuldade_Acordar_Faltas_Matutinas | 0.50x | 0.3% | 13.0% |
| 11 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Aprendizagem_e_Rotina | 0.50x | 0.1% | 9.4% |
| 12 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Verificacao_de_Historico_e_Bolsas | 0.50x | 0.2% | 8.1% |
| 13 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Relatorio_Busca_Ativa_Porto_Alegre | 0.53x | 0.3% | 1.6% |
| 14 | SAUDE_FISICA_MENTAL_FAMILIA -> Desinteresse_Geral_e_Desmotivacao | 0.53x | 0.1% | 1.7% |
| 15 | VIOLENCIA_ENTORNO_ESCOLA -> Dificuldade_Acordar_Faltas_Matutinas | 0.54x | 0.1% | 14.0% |

---

## ENSINO FUNDAMENTAL - 6º ANO
**Total de Alunos Únicos:** 6.775

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | GESTACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 8.04x | 0.3% | 39.5% |
| 02 | TRABALHO -> Trabalho_Precoce_e_EJA_Noturno | 6.30x | 0.8% | 29.8% |
| 03 | ENSINO_FUNDAMENTAL_ANOS_FINAIS -> Transferencia_Escolar_Bairro_Vaga | 6.10x | 1.1% | 74.8% |
| 04 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 5.77x | 0.8% | 27.3% |
| 05 | VIOLENCIA_ENTORNO_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 5.45x | 0.7% | 35.0% |
| 06 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 5.10x | 0.3% | 24.1% |
| 07 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Desastre_Climatico_Enchente_Retorno_Adiado | 4.36x | 1.5% | 44.7% |
| 08 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Violencia_Drogas_Rua_e_Fuga | 3.98x | 0.5% | 25.5% |
| 09 | FALTA_DE_RECURSOS -> Dificuldade_Transporte_e_Recursos_Financeiros | 3.75x | 0.4% | 17.7% |
| 10 | RELACIONAMENTO_NA_ESCOLA -> Comportamento_Indisciplina_Conflito | 3.70x | 1.6% | 48.8% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | SAUDE_FISICA_MENTAL_FAMILIA -> Atingimento_Idade_Maioridade_Ensino_Medio | 0.35x | 0.1% | 2.1% |
| 02 | ENSINO_FUNDAMENTAL_ANOS_FINAIS -> Faltas_Intercaladas_Sem_Justificativa | 0.38x | 0.1% | 7.8% |
| 03 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Afastamento_Medico_Doenca_Aguda | 0.44x | 0.1% | 3.8% |
| 04 | RELACIONAMENTO_NA_ESCOLA -> Abandono_Logo_Apos_Matricula | 0.44x | 0.1% | 3.7% |
| 05 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Mudanca_de_Cidade_e_Municipio | 0.45x | 0.5% | 2.9% |
| 06 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Baixa_Frequencia_Trimestral | 0.47x | 0.1% | 6.4% |
| 07 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Desastre_Climatico_Enchente_Retorno_Adiado | 0.48x | 0.1% | 5.0% |
| 08 | TRABALHO -> Saude_Mental_Psicologico_e_Depressao | 0.50x | 0.1% | 4.7% |
| 09 | RELACIONAMENTO_NA_ESCOLA -> Mudanca_de_Cidade_e_Municipio | 0.50x | 0.1% | 3.2% |
| 10 | ENSINO_FUNDAMENTAL_ANOS_FINAIS -> Verificacao_de_Historico_e_Bolsas | 0.51x | 0.1% | 8.7% |
| 11 | VIOLENCIA_ENTORNO_ESCOLA -> Saude_Mental_Psicologico_e_Depressao | 0.52x | 0.1% | 4.9% |
| 12 | SAUDE_FISICA_MENTAL_FAMILIA -> Desinteresse_Geral_e_Desmotivacao | 0.52x | 0.2% | 3.7% |
| 13 | NECESSIDADE_DE_CUIDADOS_FAMILIA -> Atingimento_Idade_Maioridade_Ensino_Medio | 0.54x | 0.2% | 3.3% |
| 14 | NECESSIDADE_DE_CUIDADOS_FAMILIA -> Desinteresse_Geral_e_Desmotivacao | 0.55x | 0.2% | 3.9% |
| 15 | FALTA_DE_RECURSOS -> Promessas_Quebradas_de_Retorno | 0.56x | 0.1% | 4.4% |

---

## ENSINO FUNDAMENTAL - 7º ANO
**Total de Alunos Únicos:** 7.367

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | FILHO_PEQUENO_SEM_CRECHE -> Gravidez_Adolescente_e_Cuidados_Bebes | 8.55x | 0.1% | 39.1% |
| 02 | GESTACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 7.84x | 0.4% | 35.9% |
| 03 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 6.97x | 0.3% | 32.1% |
| 04 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 6.46x | 1.0% | 29.7% |
| 05 | ENSINO_FUNDAMENTAL_ANOS_FINAIS -> Transferencia_Escolar_Bairro_Vaga | 6.12x | 0.9% | 72.8% |
| 06 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Gravidez_Adolescente_e_Cuidados_Bebes | 5.70x | 0.4% | 26.1% |
| 07 | TRABALHO -> Trabalho_Precoce_e_EJA_Noturno | 5.62x | 1.9% | 38.5% |
| 08 | FILHO_PEQUENO_SEM_CRECHE -> Atingimento_Idade_Maioridade_Ensino_Medio | 4.83x | 0.1% | 34.8% |
| 09 | VIOLENCIA_ENTORNO_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 4.40x | 0.4% | 31.4% |
| 10 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Saude_Mental_Psicologico_e_Depressao | 3.75x | 5.2% | 32.4% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | TRABALHO -> Afastamento_Medico_Doenca_Aguda | 0.30x | 0.1% | 2.2% |
| 02 | TRABALHO -> Saude_Mental_Psicologico_e_Depressao | 0.35x | 0.1% | 3.0% |
| 03 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Comportamento_Indisciplina_Conflito | 0.39x | 0.1% | 5.0% |
| 04 | SAUDE_FISICA_MENTAL_FAMILIA -> Trabalho_Precoce_e_EJA_Noturno | 0.46x | 0.1% | 3.1% |
| 05 | SAUDE_FISICA_MENTAL_FAMILIA -> Desinteresse_Geral_e_Desmotivacao | 0.46x | 0.2% | 3.8% |
| 06 | GESTACAO -> Faltas_Intercaladas_Sem_Justificativa | 0.47x | 0.1% | 8.7% |
| 07 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Mudanca_de_Cidade_e_Municipio | 0.47x | 0.5% | 2.9% |
| 08 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Desinteresse_Geral_e_Desmotivacao | 0.50x | 0.1% | 4.1% |
| 09 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Faltas_Intercaladas_Sem_Justificativa | 0.52x | 0.1% | 9.6% |
| 10 | ENSINO_FUNDAMENTAL_ANOS_FINAIS -> Verificacao_de_Historico_e_Bolsas | 0.53x | 0.1% | 8.7% |
| 11 | ENSINO_FUNDAMENTAL_ANOS_FINAIS -> Faltas_Intercaladas_Sem_Justificativa | 0.53x | 0.1% | 9.8% |
| 12 | RELACIONAMENTO_NA_ESCOLA -> Atingimento_Idade_Maioridade_Ensino_Medio | 0.54x | 0.1% | 3.9% |
| 13 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Comportamento_Indisciplina_Conflito | 0.54x | 0.1% | 7.0% |
| 14 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Afastamento_Medico_Doenca_Aguda | 0.55x | 0.1% | 4.1% |
| 15 | FALTA_DE_TRANSPORTE_ESCOLAR -> Promessas_Quebradas_de_Retorno | 0.56x | 0.1% | 4.2% |

---

## ENSINO FUNDAMENTAL - 8º ANO
**Total de Alunos Únicos:** 7.552

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | GESTACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 11.59x | 0.8% | 53.4% |
| 02 | FILHO_PEQUENO_SEM_CRECHE -> Gravidez_Adolescente_e_Cuidados_Bebes | 8.07x | 0.2% | 37.2% |
| 03 | ENSINO_FUNDAMENTAL_ANOS_FINAIS -> Transferencia_Escolar_Bairro_Vaga | 7.46x | 0.8% | 80.0% |
| 04 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 6.85x | 0.2% | 26.5% |
| 05 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 6.79x | 0.6% | 26.3% |
| 06 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Violencia_Drogas_Rua_e_Fuga | 5.01x | 0.6% | 36.1% |
| 07 | TRABALHO -> Trabalho_Precoce_e_EJA_Noturno | 4.54x | 3.7% | 43.5% |
| 08 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Gravidez_Adolescente_e_Cuidados_Bebes | 4.53x | 0.4% | 20.9% |
| 09 | VIOLENCIA_ENTORNO_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 4.32x | 0.4% | 31.2% |
| 10 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Desastre_Climatico_Enchente_Retorno_Adiado | 4.14x | 0.7% | 37.1% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | TRABALHO -> Saude_Mental_Psicologico_e_Depressao | 0.34x | 0.3% | 3.2% |
| 02 | SAUDE_FISICA_MENTAL_FAMILIA -> Desinteresse_Geral_e_Desmotivacao | 0.39x | 0.2% | 3.8% |
| 03 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Faltas_Intercaladas_Sem_Justificativa | 0.39x | 0.1% | 7.0% |
| 04 | ENSINO_FUNDAMENTAL_ANOS_FINAIS -> Dificuldade_Acordar_Faltas_Matutinas | 0.41x | 0.1% | 10.7% |
| 05 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Comportamento_Indisciplina_Conflito | 0.42x | 0.1% | 5.3% |
| 06 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Faltas_Intercaladas_Sem_Justificativa | 0.42x | 0.1% | 7.6% |
| 07 | SAUDE_FISICA_MENTAL_FAMILIA -> Trabalho_Precoce_e_EJA_Noturno | 0.43x | 0.2% | 4.1% |
| 08 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Mudanca_de_Cidade_e_Municipio | 0.44x | 0.5% | 2.9% |
| 09 | TRABALHO -> Afastamento_Medico_Doenca_Aguda | 0.45x | 0.3% | 3.5% |
| 10 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Conflito_Relacionamento_Professores_Turma | 0.49x | 0.2% | 8.2% |
| 11 | VIOLENCIA_ENTORNO_ESCOLA -> Conflito_Relacionamento_Professores_Turma | 0.51x | 0.1% | 8.6% |
| 12 | FALTA_DE_TRANSPORTE_ESCOLAR -> Saude_Mental_Psicologico_e_Depressao | 0.53x | 0.1% | 5.0% |
| 13 | SAUDE_FISICA_MENTAL_FAMILIA -> Abandono_Logo_Apos_Matricula | 0.53x | 0.2% | 4.7% |
| 14 | RELACIONAMENTO_NA_ESCOLA -> Desinteresse_Geral_e_Desmotivacao | 0.54x | 0.1% | 5.2% |
| 15 | VIOLENCIA_ENTORNO_ESCOLA -> Faltas_Intercaladas_Sem_Justificativa | 0.54x | 0.1% | 9.7% |

---

## ENSINO FUNDAMENTAL - 9º ANO
**Total de Alunos Únicos:** 6.703

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | GESTACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 9.96x | 0.8% | 43.7% |
| 02 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 8.40x | 0.6% | 31.3% |
| 03 | ENSINO_FUNDAMENTAL_ANOS_FINAIS -> Transferencia_Escolar_Bairro_Vaga | 8.16x | 0.5% | 76.6% |
| 04 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 8.14x | 0.3% | 30.4% |
| 05 | VIOLENCIA_ENTORNO_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 6.16x | 0.4% | 39.3% |
| 06 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Violencia_Drogas_Rua_e_Fuga | 5.59x | 0.4% | 35.7% |
| 07 | FILHO_PEQUENO_SEM_CRECHE -> Gravidez_Adolescente_e_Cuidados_Bebes | 5.55x | 0.1% | 24.3% |
| 08 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Gravidez_Adolescente_e_Cuidados_Bebes | 5.15x | 0.5% | 22.6% |
| 09 | RELACIONAMENTO_NA_ESCOLA -> Comportamento_Indisciplina_Conflito | 4.36x | 1.0% | 44.4% |
| 10 | ENSINO_FUNDAMENTAL_ANOS_FINAIS -> Mudanca_de_Cidade_e_Municipio | 4.04x | 0.2% | 23.4% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | TRABALHO -> Saude_Mental_Psicologico_e_Depressao | 0.32x | 0.4% | 3.0% |
| 02 | TRABALHO -> Afastamento_Medico_Doenca_Aguda | 0.37x | 0.4% | 2.9% |
| 03 | FALTA_DE_TRANSPORTE_ESCOLAR -> Trabalho_Precoce_e_EJA_Noturno | 0.42x | 0.1% | 5.2% |
| 04 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Baixa_Frequencia_Trimestral | 0.44x | 0.1% | 5.5% |
| 05 | TRABALHO -> Gravidez_Adolescente_e_Cuidados_Bebes | 0.46x | 0.3% | 2.0% |
| 06 | FALTA_DE_RECURSOS -> Conflito_Relacionamento_Professores_Turma | 0.51x | 0.1% | 9.2% |
| 07 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Mudanca_de_Cidade_e_Municipio | 0.51x | 0.5% | 2.9% |
| 08 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Faltas_Intercaladas_Sem_Justificativa | 0.52x | 0.2% | 9.6% |
| 09 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Dificuldade_Aprendizagem_e_Rotina | 0.53x | 0.1% | 6.2% |
| 10 | FALTA_DE_TRANSPORTE_ESCOLAR -> Atingimento_Idade_Maioridade_Ensino_Medio | 0.54x | 0.1% | 6.0% |
| 11 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Trabalho_Precoce_e_EJA_Noturno | 0.54x | 0.1% | 6.7% |
| 12 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Dialogos_Informais_Pedidos_de_Transferencia | 0.54x | 0.1% | 11.4% |
| 13 | GESTACAO -> Faltas_Intercaladas_Sem_Justificativa | 0.55x | 0.2% | 10.1% |
| 14 | SAUDE_FISICA_MENTAL_FAMILIA -> Trabalho_Precoce_e_EJA_Noturno | 0.55x | 0.2% | 6.8% |
| 15 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Trabalho_Precoce_e_EJA_Noturno | 0.55x | 1.2% | 6.8% |

---

## EDUCAÇÃO INFANTIL
**Total de Alunos Únicos:** 9.622

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Violencia_Drogas_Rua_e_Fuga | 7.53x | 0.3% | 20.9% |
| 02 | RELACIONAMENTO_NA_ESCOLA -> Comportamento_Indisciplina_Conflito | 5.17x | 0.2% | 41.3% |
| 03 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Saude_Mental_Psicologico_e_Depressao | 3.79x | 3.0% | 25.2% |
| 04 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 3.52x | 2.5% | 28.7% |
| 05 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 3.49x | 0.7% | 28.4% |
| 06 | PRE_ESCOLA -> Relatorio_Busca_Ativa_Porto_Alegre | 3.47x | 0.7% | 10.9% |
| 07 | TRABALHO -> Trabalho_Precoce_e_EJA_Noturno | 3.39x | 0.6% | 11.7% |
| 08 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Desastre_Climatico_Enchente_Retorno_Adiado | 3.31x | 1.5% | 43.0% |
| 09 | FALTA_DE_POLITICAS_TRANSVERSAIS -> Direito_ao_Estudo_e_Medidas_da_Secretaria | 3.19x | 0.1% | 20.0% |
| 10 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Mudanca_Guarda_Avo_Irmaos | 3.15x | 0.1% | 36.1% |
| 11 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Relatorio_Busca_Ativa_Porto_Alegre | 3.14x | 0.4% | 9.9% |
| 12 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Negligencia_Familiar_e_Drogas_no_Nucleo | 3.10x | 0.2% | 10.8% |
| 13 | PRE_ESCOLA -> Transferencia_Escolar_Bairro_Vaga | 3.02x | 4.9% | 78.8% |
| 14 | GESTACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 2.79x | 0.3% | 47.5% |
| 15 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Afastamento_Medico_Doenca_Aguda | 2.55x | 4.4% | 37.3% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | PRE_ESCOLA -> Baixa_Frequencia_Trimestral | 0.25x | 0.2% | 3.2% |
| 02 | PRE_ESCOLA -> Afastamento_Medico_Doenca_Aguda | 0.27x | 0.2% | 3.9% |
| 03 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Mudanca_de_Cidade_e_Municipio | 0.30x | 0.4% | 3.6% |
| 04 | PRE_ESCOLA -> Faltas_Intercaladas_Sem_Justificativa | 0.33x | 0.3% | 5.1% |
| 05 | PRE_ESCOLA -> Saude_Mental_Psicologico_e_Depressao | 0.35x | 0.1% | 2.4% |
| 06 | PRE_ESCOLA -> Verificacao_de_Historico_e_Bolsas | 0.38x | 0.3% | 4.7% |
| 07 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Afastamento_Medico_Doenca_Aguda | 0.40x | 0.2% | 5.8% |
| 08 | PRE_ESCOLA -> Resistencia_a_Atividades_Propostas | 0.40x | 0.1% | 2.2% |
| 09 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Baixa_Frequencia_Trimestral | 0.45x | 0.2% | 5.8% |
| 10 | PRE_ESCOLA -> Dificuldade_Aprendizagem_e_Rotina | 0.47x | 0.4% | 5.7% |
| 11 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Dialogos_Informais_Pedidos_de_Transferencia | 0.47x | 0.3% | 8.1% |
| 12 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Saude_Mental_Psicologico_e_Depressao | 0.48x | 0.1% | 3.2% |
| 13 | PRE_ESCOLA -> Comportamento_Indisciplina_Conflito | 0.49x | 0.2% | 3.9% |
| 14 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Transferencia_Escolar_Bairro_Vaga | 0.50x | 1.5% | 13.0% |
| 15 | PRE_ESCOLA -> Conflito_Relacionamento_Professores_Turma | 0.50x | 0.5% | 8.2% |

---

## EDUCAÇÃO DE JOVENS E ADULTOS (EJA)
**Total de Alunos Únicos:** 4.510

### 🟢 Correlações Positivas (Atração)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | NAO_OFERTA_DE_EDUCACAO_ESPECIAL -> Saude_Mental_Psicologico_e_Depressao | 15.56x | 0.1% | 55.6% |
| 02 | EJA -> Transferencia_Escolar_Bairro_Vaga | 12.07x | 0.2% | 80.0% |
| 03 | GESTACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 11.66x | 0.8% | 54.3% |
| 04 | RELACIONAMENTO_NA_ESCOLA -> Comportamento_Indisciplina_Conflito | 9.41x | 0.7% | 56.4% |
| 05 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Violencia_Drogas_Rua_e_Fuga | 6.93x | 0.2% | 33.3% |
| 06 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Gravidez_Adolescente_e_Cuidados_Bebes | 6.28x | 0.7% | 29.2% |
| 07 | FILHO_PEQUENO_SEM_CRECHE -> Gravidez_Adolescente_e_Cuidados_Bebes | 6.14x | 0.2% | 28.6% |
| 08 | VIOLENCIA_ENTORNO_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 6.05x | 0.7% | 29.1% |
| 09 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Saude_Mental_Psicologico_e_Depressao | 5.91x | 1.7% | 21.1% |
| 10 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Mudanca_Guarda_Avo_Irmaos | 5.58x | 0.3% | 57.1% |
| 11 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 5.43x | 0.2% | 20.5% |
| 12 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Comportamento_Indisciplina_Conflito | 4.77x | 0.1% | 28.6% |
| 13 | FILHO_PEQUENO_SEM_CRECHE -> Violencia_Drogas_Rua_e_Fuga | 4.45x | 0.1% | 21.4% |
| 14 | SAUDE_FISICA_MENTAL_FAMILIA -> Saude_Mental_Psicologico_e_Depressao | 4.39x | 0.3% | 15.7% |
| 15 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Desastre_Climatico_Enchente_Retorno_Adiado | 4.27x | 1.1% | 51.1% |

### 🔴 Correlações Negativas (Repulsão)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Atingimento_Idade_Maioridade_Ensino_Medio | 0.38x | 0.1% | 5.3% |
| 02 | TRABALHO -> Negligencia_Familiar_e_Drogas_no_Nucleo | 0.43x | 0.6% | 4.3% |
| 03 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Negligencia_Familiar_e_Drogas_no_Nucleo | 0.46x | 0.1% | 4.7% |
| 04 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Relatorio_Busca_Ativa_Porto_Alegre | 0.48x | 0.2% | 2.4% |
| 05 | RELACIONAMENTO_NA_ESCOLA -> Verificacao_de_Historico_e_Bolsas | 0.48x | 0.1% | 9.1% |
| 06 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Resistencia_a_Atividades_Propostas | 0.49x | 0.2% | 3.0% |
| 07 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Dificuldade_Transporte_e_Recursos_Financeiros | 0.50x | 0.2% | 1.9% |
| 08 | GESTACAO -> Atingimento_Idade_Maioridade_Ensino_Medio | 0.50x | 0.1% | 7.1% |
| 09 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Trabalho_Precoce_e_EJA_Noturno | 0.52x | 0.5% | 6.5% |
| 10 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Mudanca_Guarda_Avo_Irmaos | 0.52x | 0.1% | 5.3% |
| 11 | TRABALHO -> Gravidez_Adolescente_e_Cuidados_Bebes | 0.54x | 0.3% | 2.5% |
| 12 | VIOLENCIA_ENTORNO_ESCOLA -> Negligencia_Familiar_e_Drogas_no_Nucleo | 0.54x | 0.1% | 5.5% |
| 13 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Desinteresse_Geral_e_Desmotivacao | 0.55x | 0.5% | 5.7% |
| 14 | GESTACAO -> Conflito_Relacionamento_Professores_Turma | 0.56x | 0.1% | 7.1% |
| 15 | TRABALHO -> Relatorio_Busca_Ativa_Porto_Alegre | 0.56x | 0.4% | 2.8% |
