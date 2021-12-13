# Fundamentos de ETL com Python 🐍

Curso oferecido para a DIO sobre ETL utilizando a linguagem Python e as bibliotecas pandas e pandera.

> ### Objetivo do curso
> Contexto do processo de ETL (Extract, Transform, and Load)
>
> ### Competências atendidas
> - Conhecimento do processo de ETL de ponta-a-ponta
> - Bibliotecas do Python para ETL
>
> ### Pré-requisito
> - Conhecimento da linguagem de programação Python
>
> ### Percurso
> 1. Aula → Introdução ao ETL
> 2. Aula → Projeto ETL - Ambiente e definição
> 3. Aula → Projeto ETL - Desenvolvimento


## Introdução ao ETL

### Definição

<p align="center">
  <img src="https://www.dadosaleatorios.com.br/post/etl-data-store/ETL_Fluxo.gif" alt="etl" width="600px" />
</p>

* **Extract** → os dados são extraídos de diferentes fontes de dados
* **Transform** → propagados para a área de preparação de dados, onde são transformados e limpos.
* **Load** → Carregados em outra fonte de dados (data warehouse, data lake, ...)

O processo de ETL é feito de modo a tornar os **dados íntegros, consistentes, válidos** para que a tomada de decisão final seja adequada e certeira.

### Por que precisamos?
Tudo começa a partir da necessidade de tomada de decisão dos gestores organizacionais.

Como os gestores tomam uma decisão? analisando dados - eles relacionam dados para gerar informação útil a tomada de decisão.

No entanto, como juntar dados de diferentes fontes de informação?
Relacionar dados de ERP, CRM, sites, planilhas, e de outras fontes, de modo consistente, organizado e confiável para tomar decisão.

Os dados podem ser extraídos em lotes (Batch) ou em tempo real. E após serem transformados serão carregados na base de dados de consolidação.


### Visão geral sobre ETL

Dentro do processo de 

<p align="center">
  <img src="http://2.bp.blogspot.com/-dSnbfUATfoU/U7opdrbBKTI/AAAAAAAACkU/EAnBsiIyPaY/s1600/ETL-process-flow.jpeg" alt="etl process flow" width="600px" />
</p>

* Data Sources → as diferentes fontes de dados que armazenam os dados que vão ser extraídos e carregados para dentro do contexto da empresa (Data Warehouse, Data lake, ...)
* Processo maior de ETL → Transformação:
    * Data Validation 
    * Data Cleaning
    * Data Transforming
    * Data Aggregating
    * Data Summarization
    * Data Normalization
    * Data Loading
* Data flow/Pipeline → segmentação do processo

### Ferramentas

#### Para saber mais

* https://airflow.apache.org/
* https://luigi.readthedocs.io/en/stable/
* https://www.bonobo-project.org/
* http://bubbles.databrewery.org/
* https://petl.readthedocs.io/en/stable/
* https://pandas.pydata.org/

### Referências
