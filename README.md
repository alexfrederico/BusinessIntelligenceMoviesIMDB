<img src="https://i.ibb.co/gSy2YgL/dataset-cover.jpg" alt="Metadata on over 45,000 movies. 26 million ratings from over 270,000 users." title="The Movies Dataset" />

***

# Business Intelligence: Movies IMDB

## O Business Intelligence (BI) oferece o apoio para as decisões de forma inteligente, por meio de um processo de captação de dados, apresentando seus resultados em relatórios analíticos, resumos, painéis gráficos e mapas, visando fornecer aos utilizadores informações detalhadas sobre o estado do negócio, ou seja, na produção de filmes.

<img src="https://img.shields.io/github/repo-size/alexfrederico/BusinessIntelligenceMoviesIMDB?style=plastic" alt="Metadata on over 45,000 movies. 26 million ratings from over 270,000 users." title="The Movies Dataset" />

Tabela de conteúdos
=================
<!--ts-->
   * [QlikSense](#qliksense)
   * [Business Intelligence](#business-intelligence)
   * [ETL](#etl)
   * [MovieIMDB](#Movieimdb)
<!--te-->

## QlikSense

é uma ferramenta de visualização de informações que explora profundamente todos os dados e revela suas conexões de modo simples e instantâneo, entregando conhecimento acerca das oportunidades de negócio.

O QlikSense é baseado em tecnologia patenteada chamada Associative Query Logic (AQL). AQL permite que o mesmo funcione com milhões de células e ainda responda a consultas em menos de um segundo. As associações de alta velocidade ocorrem quando o usuário clica nos vários objetos da pasta e a exibição é atualizada imediatamente.

Além de eliminar a necessidade de pré-agregar dados para a maioria dos aplicativos, o QlikSense executa cálculos dinamicamente, permitindo que qualquer usuário se torne um trabalhador do conhecimento sofisticado.

## Business Intelligence

análise de dados e apresentar informações acionáveis para ajudar executivos, gerentes e outros usuários finais corporativos a tomar decisões de negócios bem informadas. Utilizando ampla variedade de ferramentas, aplicativos e metodologias que possibilitam às organizações coletarem dados de sistemas internos e fontes externas, preparando-os para análise e desenvolvendo consultas em relação a eles.

## ETL

Essa sigla significa Extração, Transformação e Carga (em inglês Extract, Transform and Load) e trata da sistematização do tratamento e limpeza dos dados oriundos dos diversos sistemas organizacionais.

A etapa de extração pode ser entendida como a fase onde os dados são extraídos dos OLTPs e conduzidos para a staging area (área de transição ou área temporária), onde são convertidos para um único formato. A conversão se faz necessária devido a heterogeneidade existente nas informações oriundas desses sistemas, sendo essencial a conformação prévia para o tratamento adequado.

Após a extração, teremos subsídios para iniciar a etapa de transformação e limpeza dos dados. Nessa fase são corrigidos, padronizados e tratados os desvios e inconsistências, transformando os dados de acordo com as regras do negócio.

A etapa de carga ocorre em sequência com a de transformação. Assim que são efetuados os tratamentos necessários nos dados, a carga no DW é iniciada. Essa fase se resume na persistência dos dados na base consolidada.

## MovieIMDB

O aplicativo MovieIMDB foi proposto para demonstrar como é feita a codificação dentro da ferramenta e mostrar através de um exemplo um aplicativo com gráficos dinâmicos que se adaptam conforme seus filtro. Esse aplicativo é uma demonstração das infinitas possibilidades de aplicativos e gráficos que podem ser criados no QlikSense.

Através do aplicativo MovieIMDB é possível sanar dúvidas de negócio, como:
- Quais Países possuem mais filmes
- Quais os filmes com pontuação mais alta
- Qual o elenco e equipe técnica proporciona mais receita
- Qual o gênero que necessita de maior orçamento
- Qual a imagem do ator, diretor, filme, etc
- Quais as melhores palavras para atrair mais público
- Qual diretor se adequa melhor ao filme que será produzido
- Como produzir filmes com maior receita
- ...

Na imagem abaixo é possível ver o aplicativo e suas ferramentas de análise (não há filtros selecionando)

<img src="https://i.ibb.co/LRGDY1G/all.png" title="Gráficos do aplicativo sem filtros" />

Foi feito utilizando tabela, filtro, nuvem de palavras, gráfico de mídia, mapa e gráfico de linhas.

Na imagem abaixo é possível ver como os gráficos se modificam após a seleção de alguns filtros.

<img src="https://i.ibb.co/MBZshSv/hayao.png" title="Gráficos do aplicativo com filtros" />

A extração de dados de fontes externas (como o CSV), a transformação e processamento dos dados para atender às necessidades de negócios e o Carregamento desses dados é feito, único e exclusivamente, no QlikSense.


