# Regras de Associação: Fatores de Evasão Escolar (FICAI)

Este documento apresenta os resultados da mineração de Regras de Associação utilizando o algoritmo FP-Growth sobre os dados do sistema FICAI, buscando correlacionar os diagnósticos institucionais com os tópicos textuais extraídos via NLP.

---

## TRÍADE PEDAGÓGICA -> TODOS OS TÓPICOS
**Total de Alunos Únicos:** 89.833

### 🟢 Correlações Positivas (Lift $\geq$ 1.2)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | DISTORSAO_IDADE_ANO -> Atingimento_Idade_Maioridade_Ensino_Medio | 1.88x | 1.88% | 15.0% |
| 02 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Dificuldade_Aprendizagem_e_Rotina | 1.81x | 5.24% | 23.3% |
| 03 | REPROVACAO -> Desinteresse_Geral_e_Desmotivacao | 1.78x | 2.00% | 13.3% |
| 04 | DISTORSAO_IDADE_ANO -> Desinteresse_Geral_e_Desmotivacao | 1.68x | 1.58% | 12.6% |
| 05 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Saude_Mental_Psicologico_e_Depressao | 1.51x | 2.69% | 11.9% |
| 06 | DISTORSAO_IDADE_ANO -> Violencia_Drogas_Rua_e_Fuga | 1.51x | 0.89% | 7.1% |
| 07 | DISTORSAO_IDADE_ANO -> Comportamento_Indisciplina_Conflito | 1.49x | 1.76% | 14.0% |
| 08 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Comportamento_Indisciplina_Conflito | 1.46x | 3.12% | 13.8% |
| 09 | REPROVACAO -> Atingimento_Idade_Maioridade_Ensino_Medio | 1.46x | 1.75% | 11.7% |
| 10 | REPROVACAO -> Comportamento_Indisciplina_Conflito | 1.42x | 2.01% | 13.4% |
| 11 | DISTORSAO_IDADE_ANO -> Trabalho_Precoce_e_EJA_Noturno | 1.42x | 1.74% | 13.9% |
| 12 | DISTORSAO_IDADE_ANO -> Promessas_Quebradas_de_Retorno | 1.40x | 1.22% | 9.7% |
| 13 | REPROVACAO -> Violencia_Drogas_Rua_e_Fuga | 1.37x | 0.96% | 6.4% |
| 14 | REPROVACAO -> Promessas_Quebradas_de_Retorno | 1.35x | 1.40% | 9.4% |
| 15 | DISTORSAO_IDADE_ANO -> Abandono_Logo_Apos_Matricula | 1.33x | 1.45% | 11.6% |
| 16 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Desinteresse_Geral_e_Desmotivacao | 1.32x | 2.23% | 9.9% |
| 17 | REPROVACAO -> Trabalho_Precoce_e_EJA_Noturno | 1.29x | 1.89% | 12.6% |
| 18 | REPROVACAO -> Dificuldade_Aprendizagem_e_Rotina | 1.28x | 2.46% | 16.4% |
| 19 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Promessas_Quebradas_de_Retorno | 1.28x | 1.99% | 8.8% |
| 20 | DISTORSAO_IDADE_ANO -> Dificuldade_Aprendizagem_e_Rotina | 1.27x | 2.05% | 16.3% |
| 21 | DISTORSAO_IDADE_ANO -> Direito_ao_Estudo_e_Medidas_da_Secretaria | 1.24x | 0.97% | 7.7% |
| 22 | DISTORSAO_IDADE_ANO -> Verificacao_de_Historico_e_Bolsas | 1.22x | 2.33% | 18.6% |
| 23 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Resistencia_a_Atividades_Propostas | 1.22x | 1.70% | 7.6% |
| 24 | DISTORSAO_IDADE_ANO -> Busca_por_Atendimento_Domiciliar | 1.20x | 4.81% | 38.4% |

### 🔴 Correlações Negativas (Lift $\leq$ 0.8)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | DISTORSAO_IDADE_ANO -> Gravidez_Adolescente_e_Cuidados_Bebes | 0.58x | 0.51% | 4.1% |
| 02 | REPROVACAO -> Transferencia_Escolar_Bairro_Vaga | 0.59x | 1.13% | 7.5% |
| 03 | REPROVACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 0.59x | 0.62% | 4.2% |
| 04 | REPROVACAO -> Mudanca_de_Cidade_e_Municipio | 0.60x | 0.63% | 4.2% |
| 05 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Mudanca_de_Cidade_e_Municipio | 0.65x | 1.02% | 4.5% |
| 06 | DISTORSAO_IDADE_ANO -> Transferencia_Escolar_Bairro_Vaga | 0.65x | 1.04% | 8.3% |
| 07 | DISTORSAO_IDADE_ANO -> Afastamento_Medico_Doenca_Aguda | 0.67x | 0.75% | 6.0% |
| 08 | DISTORSAO_IDADE_ANO -> Mudanca_de_Cidade_e_Municipio | 0.69x | 0.60% | 4.8% |
| 09 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Transferencia_Escolar_Bairro_Vaga | 0.69x | 1.96% | 8.7% |
| 10 | REPROVACAO -> Afastamento_Medico_Doenca_Aguda | 0.70x | 0.94% | 6.2% |
| 11 | REPROVACAO -> Dificuldade_Transporte_e_Recursos_Financeiros | 0.75x | 0.58% | 3.9% |
| 12 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Gravidez_Adolescente_e_Cuidados_Bebes | 0.78x | 1.24% | 5.5% |

---

## TRÍADE PEDAGÓGICA -> TÓPICOS (SEM BUROCRÁTICOS)
**Total de Alunos Únicos:** 89.833

### 🟢 Correlações Positivas (Lift $\geq$ 1.2)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | DISTORSAO_IDADE_ANO -> Atingimento_Idade_Maioridade_Ensino_Medio | 1.88x | 1.92% | 15.3% |
| 02 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Dificuldade_Aprendizagem_e_Rotina | 1.80x | 5.35% | 23.6% |
| 03 | REPROVACAO -> Desinteresse_Geral_e_Desmotivacao | 1.78x | 2.03% | 13.6% |
| 04 | DISTORSAO_IDADE_ANO -> Desinteresse_Geral_e_Desmotivacao | 1.68x | 1.61% | 12.8% |
| 05 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Saude_Mental_Psicologico_e_Depressao | 1.51x | 2.75% | 12.1% |
| 06 | DISTORSAO_IDADE_ANO -> Violencia_Drogas_Rua_e_Fuga | 1.50x | 0.90% | 7.2% |
| 07 | DISTORSAO_IDADE_ANO -> Comportamento_Indisciplina_Conflito | 1.48x | 1.79% | 14.2% |
| 08 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Comportamento_Indisciplina_Conflito | 1.46x | 3.18% | 14.0% |
| 09 | REPROVACAO -> Atingimento_Idade_Maioridade_Ensino_Medio | 1.46x | 1.78% | 11.9% |
| 10 | REPROVACAO -> Comportamento_Indisciplina_Conflito | 1.42x | 2.05% | 13.7% |
| 11 | DISTORSAO_IDADE_ANO -> Trabalho_Precoce_e_EJA_Noturno | 1.41x | 1.77% | 14.1% |
| 12 | DISTORSAO_IDADE_ANO -> Promessas_Quebradas_de_Retorno | 1.40x | 1.24% | 9.9% |
| 13 | REPROVACAO -> Violencia_Drogas_Rua_e_Fuga | 1.36x | 0.98% | 6.5% |
| 14 | REPROVACAO -> Promessas_Quebradas_de_Retorno | 1.35x | 1.43% | 9.5% |
| 15 | DISTORSAO_IDADE_ANO -> Abandono_Logo_Apos_Matricula | 1.32x | 1.47% | 11.7% |
| 16 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Desinteresse_Geral_e_Desmotivacao | 1.32x | 2.28% | 10.1% |
| 17 | REPROVACAO -> Trabalho_Precoce_e_EJA_Noturno | 1.29x | 1.92% | 12.9% |
| 18 | REPROVACAO -> Dificuldade_Aprendizagem_e_Rotina | 1.28x | 2.51% | 16.8% |
| 19 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Promessas_Quebradas_de_Retorno | 1.27x | 2.03% | 9.0% |
| 20 | DISTORSAO_IDADE_ANO -> Dificuldade_Aprendizagem_e_Rotina | 1.26x | 2.08% | 16.6% |
| 21 | DISTORSAO_IDADE_ANO -> Direito_ao_Estudo_e_Medidas_da_Secretaria | 1.23x | 0.99% | 7.9% |
| 22 | DISTORSAO_IDADE_ANO -> Verificacao_de_Historico_e_Bolsas | 1.22x | 2.38% | 18.9% |
| 23 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Resistencia_a_Atividades_Propostas | 1.22x | 1.74% | 7.7% |

### 🔴 Correlações Negativas (Lift $\leq$ 0.8)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | DISTORSAO_IDADE_ANO -> Gravidez_Adolescente_e_Cuidados_Bebes | 0.57x | 0.52% | 4.1% |
| 02 | REPROVACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 0.59x | 0.63% | 4.2% |
| 03 | REPROVACAO -> Transferencia_Escolar_Bairro_Vaga | 0.59x | 1.15% | 7.7% |
| 04 | REPROVACAO -> Mudanca_de_Cidade_e_Municipio | 0.60x | 0.64% | 4.2% |
| 05 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Mudanca_de_Cidade_e_Municipio | 0.65x | 1.04% | 4.6% |
| 06 | DISTORSAO_IDADE_ANO -> Transferencia_Escolar_Bairro_Vaga | 0.65x | 1.06% | 8.4% |
| 07 | DISTORSAO_IDADE_ANO -> Afastamento_Medico_Doenca_Aguda | 0.67x | 0.76% | 6.1% |
| 08 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Transferencia_Escolar_Bairro_Vaga | 0.68x | 2.00% | 8.8% |
| 09 | DISTORSAO_IDADE_ANO -> Mudanca_de_Cidade_e_Municipio | 0.68x | 0.61% | 4.8% |
| 10 | REPROVACAO -> Afastamento_Medico_Doenca_Aguda | 0.70x | 0.95% | 6.4% |
| 11 | REPROVACAO -> Dificuldade_Transporte_e_Recursos_Financeiros | 0.74x | 0.59% | 4.0% |
| 12 | DIFICULDADE_ENSINO_APRENDIZAGEM -> Gravidez_Adolescente_e_Cuidados_Bebes | 0.78x | 1.27% | 5.6% |

---

## DIAGNÓSTICOS (SEM TRÍADE) -> TÓPICOS (SEM BUROCRÁTICOS)
**Total de Alunos Únicos:** 89.833

### 🟢 Correlações Positivas (Lift $\geq$ 1.2)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | NAO_OFERTA_DE_EDUCACAO_ESPECIAL -> Saude_Mental_Psicologico_e_Depressao | 7.84x | 0.10% | 63.2% |
| 02 | GESTACAO -> Gravidez_Adolescente_e_Cuidados_Bebes | 6.72x | 0.52% | 48.2% |
| 03 | VIOLENCIA_ENTORNO_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 6.41x | 0.31% | 30.8% |
| 04 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Transferencia_Escolar_Bairro_Vaga | 6.22x | 0.77% | 80.5% |
| 05 | PRE_ESCOLA -> Transferencia_Escolar_Bairro_Vaga | 6.08x | 0.53% | 78.7% |
| 06 | ENSINO_FUNDAMENTAL_ANOS_FINAIS -> Transferencia_Escolar_Bairro_Vaga | 5.94x | 0.28% | 76.9% |
| 07 | FALTA_DE_TRANSPORTE_ESCOLAR -> Dificuldade_Transporte_e_Recursos_Financeiros | 5.44x | 1.26% | 29.0% |
| 08 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Violencia_Drogas_Rua_e_Fuga | 5.38x | 0.39% | 25.8% |
| 09 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Dificuldade_Transporte_e_Recursos_Financeiros | 5.28x | 0.43% | 28.1% |
| 10 | RELACIONAMENTO_NA_ESCOLA -> Comportamento_Indisciplina_Conflito | 4.72x | 0.75% | 45.4% |
| 11 | FILHO_PEQUENO_SEM_CRECHE -> Gravidez_Adolescente_e_Cuidados_Bebes | 4.40x | 0.16% | 31.6% |
| 12 | TRABALHO -> Trabalho_Precoce_e_EJA_Noturno | 4.39x | 4.77% | 43.9% |
| 13 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Saude_Mental_Psicologico_e_Depressao | 4.10x | 4.53% | 33.0% |
| 14 | RELACIONAMENTO_NA_ESCOLA -> Violencia_Drogas_Rua_e_Fuga | 4.04x | 0.32% | 19.4% |
| 15 | PRE_ESCOLA -> Mudanca_de_Cidade_e_Municipio | 3.77x | 0.18% | 26.7% |
| 16 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Desastre_Climatico_Enchente_Retorno_Adiado | 3.73x | 1.12% | 39.8% |
| 17 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Gravidez_Adolescente_e_Cuidados_Bebes | 3.46x | 0.35% | 24.8% |
| 18 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Mudanca_de_Cidade_e_Municipio | 3.08x | 0.21% | 21.8% |
| 19 | FALTA_DE_RECURSOS -> Dificuldade_Transporte_e_Recursos_Financeiros | 3.08x | 0.37% | 16.4% |
| 20 | FILHO_PEQUENO_SEM_CRECHE -> Mudanca_Guarda_Avo_Irmaos | 2.65x | 0.17% | 32.6% |
| 21 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Afastamento_Medico_Doenca_Aguda | 2.52x | 3.12% | 22.8% |
| 22 | VIOLENCIA_ENTORNO_ESCOLA -> Comportamento_Indisciplina_Conflito | 2.51x | 0.24% | 24.1% |
| 23 | SAUDE_FISICA_MENTAL_FAMILIA -> Saude_Mental_Psicologico_e_Depressao | 2.49x | 0.88% | 20.1% |
| 24 | NECESSIDADE_DE_CUIDADOS_FAMILIA -> Mudanca_Guarda_Avo_Irmaos | 2.38x | 1.63% | 29.3% |
| 25 | FALTA_DE_TRANSPORTE_ESCOLAR -> Transferencia_Escolar_Bairro_Vaga | 2.35x | 1.32% | 30.4% |
| 26 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Mudanca_Guarda_Avo_Irmaos | 2.31x | 0.40% | 28.4% |
| 27 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Violencia_Drogas_Rua_e_Fuga | 2.27x | 0.15% | 10.9% |
| 28 | FALTA_DE_ACESSO_A_TRANSPORTE_PUBLICO -> Transferencia_Escolar_Bairro_Vaga | 2.24x | 0.44% | 29.0% |
| 29 | SUSPEITA_DE_VIOLENCIA_DOMESTICA -> Negligencia_Familiar_e_Drogas_no_Nucleo | 2.23x | 0.18% | 12.2% |
| 30 | RELACIONAMENTO_NA_ESCOLA -> Saude_Mental_Psicologico_e_Depressao | 2.17x | 0.29% | 17.5% |

### 🔴 Correlações Negativas (Lift $\leq$ 0.8)
| # | Regra de Associação (Diagnóstico -> Tópico Textual) | Lift | Suporte | Confiança |
|:---:|:---|:---:|:---:|:---:|
| 01 | TRABALHO -> Saude_Mental_Psicologico_e_Depressao | 0.36x | 0.32% | 2.9% |
| 02 | TRABALHO -> Afastamento_Medico_Doenca_Aguda | 0.38x | 0.37% | 3.4% |
| 03 | SAUDE_FISICA_MENTAL_FAMILIA -> Desinteresse_Geral_e_Desmotivacao | 0.38x | 0.13% | 2.9% |
| 04 | SAUDE_FISICA_MENTAL_FAMILIA -> Trabalho_Precoce_e_EJA_Noturno | 0.41x | 0.18% | 4.1% |
| 05 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Afastamento_Medico_Doenca_Aguda | 0.46x | 0.12% | 4.1% |
| 06 | FALTA_DE_TRANSPORTE_ESCOLAR -> Desinteresse_Geral_e_Desmotivacao | 0.51x | 0.17% | 3.9% |
| 07 | FALTA_DE_RECURSOS -> Trabalho_Precoce_e_EJA_Noturno | 0.51x | 0.12% | 5.1% |
| 08 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Mudanca_de_Cidade_e_Municipio | 0.51x | 0.50% | 3.6% |
| 09 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Faltas_Intercaladas_Sem_Justificativa | 0.56x | 0.14% | 10.3% |
| 10 | NECESSIDADE_DE_CUIDADOS_FAMILIA -> Desinteresse_Geral_e_Desmotivacao | 0.57x | 0.24% | 4.3% |
| 11 | FALTA_DE_TRANSPORTE_ESCOLAR -> Trabalho_Precoce_e_EJA_Noturno | 0.57x | 0.24% | 5.6% |
| 12 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Atingimento_Idade_Maioridade_Ensino_Medio | 0.59x | 0.13% | 4.8% |
| 13 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Trabalho_Precoce_e_EJA_Noturno | 0.60x | 0.82% | 6.0% |
| 14 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Dificuldade_Acordar_Faltas_Matutinas | 0.60x | 0.14% | 15.1% |
| 15 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Comportamento_Indisciplina_Conflito | 0.62x | 0.17% | 6.0% |
| 16 | GESTACAO -> Faltas_Intercaladas_Sem_Justificativa | 0.63x | 0.13% | 11.7% |
| 17 | TRABALHO -> Transferencia_Escolar_Bairro_Vaga | 0.63x | 0.89% | 8.2% |
| 18 | TRABALHO -> Gravidez_Adolescente_e_Cuidados_Bebes | 0.63x | 0.49% | 4.5% |
| 19 | TRABALHO -> Dificuldade_Aprendizagem_e_Rotina | 0.64x | 0.91% | 8.4% |
| 20 | SAUDE_FISICA_MENTAL_ESTUDANTE -> Transferencia_Escolar_Bairro_Vaga | 0.64x | 1.14% | 8.3% |
| 21 | FALTA_DE_TRANSPORTE_ESCOLAR -> Violencia_Drogas_Rua_e_Fuga | 0.65x | 0.13% | 3.1% |
| 22 | FALTA_DE_RECURSOS -> Atingimento_Idade_Maioridade_Ensino_Medio | 0.65x | 0.12% | 5.3% |
| 23 | FALTA_DE_TRANSPORTE_ESCOLAR -> Saude_Mental_Psicologico_e_Depressao | 0.67x | 0.23% | 5.4% |
| 24 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Baixa_Frequencia_Trimestral | 0.67x | 0.12% | 9.0% |
| 25 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Dialogos_Informais_Pedidos_de_Transferencia | 0.67x | 0.36% | 12.8% |
| 26 | MATERNIDADE_PATERNIDADE_ADOLESCENTE -> Dificuldade_Aprendizagem_e_Rotina | 0.68x | 0.12% | 8.9% |
| 27 | SAUDE_FISICA_MENTAL_FAMILIA -> Atingimento_Idade_Maioridade_Ensino_Medio | 0.68x | 0.24% | 5.5% |
| 28 | TRABALHO -> Negligencia_Familiar_e_Drogas_no_Nucleo | 0.68x | 0.41% | 3.7% |
| 29 | ATINGIDO_POR_CALAMIDADE_PUBLICA -> Faltas_Intercaladas_Sem_Justificativa | 0.68x | 0.36% | 12.7% |
| 30 | ENSINO_FUNDAMENTAL_ANOS_INICIAIS -> Conflito_Relacionamento_Professores_Turma | 0.69x | 0.12% | 12.3% |
