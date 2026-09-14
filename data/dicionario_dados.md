# Dicionário de Dados (Metadados)

**Fonte:** Microdados do Censo da Educação Superior 2024 — Inep
**Arquivo de origem:** `MICRODADOS_CADASTRO_CURSOS_2024.CSV` (delimitado por `;`, 720.349 registros, 223 colunas, todas as IES do Brasil)
**Filtro aplicado:** `CO_IES` = 322 (Universidade Paulista) + `CO_CINE_AREA_GERAL` = Computação e Tecnologias da Informação e Comunicação (TIC)
**Resultado do filtro:** 1.651 registros (76 presencial + 1.575 EAD), 7 cursos distintos, presentes em 491 municípios e nas 27 unidades federativas do país

## Arquivos filtrados disponíveis nesta pasta

- `unip_tic_completo.csv` — recorte UNIP + TIC com as 223 colunas originais da base do Inep (1.651 linhas)
- `unip_tic_variaveis_selecionadas.csv` — mesmo recorte, apenas com as 18 variáveis abaixo (mais leve para análise)

## Variáveis selecionadas

| Variável | O que representa |
|---|---|
| NU_ANO_CENSO | Ano de referência do Censo |
| CO_IES | Código da Instituição de Ensino Superior |
| CO_CURSO | Código de identificação do curso |
| NO_CURSO | Nome do curso |
| CO_CINE_AREA_GERAL | Código da área geral do curso segundo a CINE Brasil |
| NO_CINE_AREA_GERAL | Nome da área geral segundo a CINE Brasil |
| NO_CINE_ROTULO | Classificação do curso segundo a CINE Brasil |
| TP_GRAU_ACADEMICO | Grau acadêmico do curso |
| TP_MODALIDADE_ENSINO | Modalidade de ensino do curso (1 = Presencial, 2 = EAD) |
| TP_DIMENSAO | Dimensão geográfica do registro (sede/polo) |
| NO_REGIAO | Região geográfica |
| SG_UF | Unidade Federativa |
| NO_MUNICIPIO | Município |
| QT_VG_TOTAL | Quantidade total de vagas |
| QT_INSCRITO_TOTAL | Quantidade de inscritos |
| QT_ING | Quantidade de ingressantes |
| QT_MAT | Quantidade de matrículas |
| QT_CONC | Quantidade de concluintes |

18 variáveis selecionadas das 223 originais, relacionadas à identificação dos cursos, modalidade de ensino, localização geográfica e indicadores de oferta e de estudantes. Detalhes da comparação Presencial x EAD estão no documento da Etapa 1 (`docs/Projeto_I_MACKENZIE_Etapa1.docx`, seção 3.4).
