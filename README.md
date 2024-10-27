# Socioeconomic Situation and Health Indicators - Data Lakehouse Project

Projeto realizado para a Unidade Curricular de Engenharia de Dados para Apoio à Tomada de Decisão. Este projeto prático tem como objetivo implementar e estruturar dados sobre um determinado tema em um Data Lakehouse, bem como realizar uma análise analítica desses dados.

## Tema Central do Projeto

O projeto aborda a **Situação Socioeconômica de uma População e seu Impacto nos Indicadores de Saúde Correspondentes**. O tema foi desenvolvido utilizando um conjunto de dados central e quatro conjuntos adicionais, todos relacionados ao conjunto de dados principal. Os temas abordados são:

1. **Estatísticas Populacionais (conjunto de dados central)**
2. **Álcool** - Impacto do consumo de álcool no mundo
3. **Covid-19** - Mortes e casos relatados de Covid-19 por país
4. **Desemprego** - Taxa de desemprego ao longo dos últimos 31 anos
5. **Salário Mínimo**

## Estrutura do Projeto

O projeto é composto por várias etapas de processamento de dados, incluindo:

1. **Análise de Qualidade dos Dados** - Avaliação da qualidade dos conjuntos de dados relacionados aos diferentes temas e identificação de possíveis objetivos de análise.
2. **Implementação do Data Lakehouse** - Utilização de uma metodologia de três camadas DeltaLake:
   - **Bronze**: Armazenamento dos dados brutos.
   - **Silver**: Limpeza e transformação dos dados.
   - **Gold**: Dados prontos para análise e geração de insights.
3. **Desenvolvimento de Dashboards** - Três dashboards foram criados para analisar e interpretar os dados de forma mais eficiente e intuitiva, com foco nos respectivos temas.

## Estrutura do Repositório

O repositório contém as seguintes pastas e arquivos:

- **/data**: Contém os arquivos CSV utilizados no projeto.
- **/code**: Código fonte para o processamento de dados e análise.
- **/notebooks**: Notebooks com a documentação das etapas de análise e desenvolvimento.
- **/dashboards**: Arquivos relacionados aos dashboards criados.
- **README.md**: Este arquivo, com a documentação do projeto.

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/usuario/repositorio.git
   cd repositorio
