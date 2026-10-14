# Análise dos Cursos de Tecnologia da UNIP: Presencial x EAD

Projeto da disciplina **Projeto I** — curso de Tecnologia em Banco de Dados, Universidade Presbiteriana Mackenzie.

## Objetivo

Analisar e comparar os cursos de graduação da área de Computação e Tecnologias da Informação e Comunicação (TIC) da **Universidade Paulista (UNIP)** nas modalidades **presencial** e **EAD**, considerando oferta, distribuição geográfica e distribuição dos estudantes, a partir dos **Microdados do Censo da Educação Superior 2024** (Inep). O estudo está relacionado ao ODS 4 — Educação de Qualidade.

## Sumário

- [Objetivo](#objetivo)
- [Integrantes](#integrantes---grupo-6)
- [Estrutura do repositório](#estrutura-do-repositório)
- [Fonte de dados](#fonte-de-dados)
- [Andamento do projeto](#andamento-do-projeto)

## Integrantes - Grupo 6

| Nome | RA | E-mail |
|---|---|---|
| Barbara Angélica Viana Moreira | 10754628 | barbara.29avm@gmail.com |
| Felipe Oliveira Rodrigues | 10781797 | felipeorodrigues3@gmail.com |
| Rusivel Samuel Vieira de Farias | 10776024 | rusivelf@gmail.com |
| Thiago Costa Ribeiro Moura Martins | 10773524 | thcosta.dados@outlook.com |

## Estrutura do repositório

```
Dados--mackenzie/
├── README.md
├── docs/          -> documentos entregáveis de cada etapa (Word/PDF), versões mantidas
│   ├── A1_Projeto_Aplicado_Etapa1.docx/.pdf   -> entrega da Etapa 1
│   └── A2_Projeto_Aplicado_Etapa1_e_Etapa2.docx/.pdf -> entrega da Etapa 2 (Etapa 1 + Etapa 2)
├── data/          -> dicionário de dados / metadados e a base filtrada (UNIP + TIC)
└── src/           -> notebook Jupyter da Análise Exploratória de Dados (Python)
```

## Fonte de dados

- **Origem:** Microdados do Censo da Educação Superior 2024 — Instituto Nacional de Estudos e Pesquisas Educacionais Anísio Teixeira (Inep), Portal de Dados Abertos.
- **Arquivo:** `MICRODADOS_CADASTRO_CURSOS_2024` (CSV, delimitado por `;`, 720.349 registros, 223 colunas, todas as IES do Brasil).
- **Recorte aplicado:** `CO_IES` = 322 (Universidade Paulista) + área de Computação e Tecnologias da Informação e Comunicação (TIC), segundo a classificação CINE Brasil → **1.651 registros** (76 presencial + 1.575 EAD), 7 cursos distintos, em 490 municípios e nas 27 unidades federativas do país.
- Os arquivos filtrados (`unip_tic_completo.csv` e `unip_tic_variaveis_selecionadas.csv`) e o dicionário de variáveis estão em [`data/`](data/dicionario_dados.md).
- A Análise Exploratória de Dados completa (medidas estatísticas, distribuição, correlações, outliers) está em [`src/analise_exploratoria_unip_tic.ipynb`](src/analise_exploratoria_unip_tic.ipynb).

## Andamento do projeto

- [x] **Etapa 1** — Metas e milestones (definição de grupo, tema, objetivos, cronograma e identificação da base de dados)
- [x] **Etapa 2** — Definição do produto (proposta analítica, pipeline de dados e Análise Exploratória de Dados em Python)
- [ ] **Etapa 3** — Storytelling (apresentação dos resultados analíticos)
- [ ] **Etapa 4** — Encerramento (ajustes finais e apresentação)
