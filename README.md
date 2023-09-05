#  Projeto de Acompanhamento de Vendas  em Power BI

Supondo que um gerente ou analista de vendas foi solicitado a apresentar à alta administração, às partes interessadas ou a outras partes relevantes um relatório de vendas 
Você recebeu uma base de dados de Vendas, do ano de 2020, de uma empresa que vende equipamentos eletrônicos para alguns grandes clientes corporativos.
Você tem o desafio de analisar estas bases de dados e construir um relatório que responda as seguintes perguntas:
•	Qual a receita obtida por vendedor?
•	Qual a receita obtida por cada regional?
•	Qual a receita obtida por cada cliente?
O gerente da empresa, também informou que gostaria de ter as informações acima, segmentadas em cada um dos estados, para uma análise mais profunda.
Por fim, o gerente informou ainda que não tem tanto conhecimento nas possibilidades do Power BI, mas que gostaria de ter mais visões interessantes sobre os dados da empresa.
Como você criaria este relatório em Power BI?

No contexto de se tornar um analista de dados, o Microsoft Excel não é a única ferramenta utilizada para análise e visualização, existe outras líderes no mercado como Tableau, Qlik, Datastudio e no próprio python onde podemos elaborar relatórios; 
O Microsoft Power Business Intelligence (Power BI) também é uma ferramenta crucial usada por analistas de dados. Power BI é um aplicativo de software de visualização de dados interativo desenvolvido pela Microsoft com foco principal em business intelligence. É um componente da Microsoft Power Platform. O Power BI é um conjunto de serviços de software, aplicativos e conectores que trabalham juntos para transformar fontes de dados diferentes em insights coesos, visualmente imersivos e interativos. Os dados podem ser obtidos lendo diretamente de um banco de dados, uma página da web ou arquivos estruturados como planilhas, CSVs, XMLs e JSONs. (Do Microsoft Power BI (2023, 3 de fevereiro)) Microsoft Power BI

**NO CONJUNTO DE DADOS**
Durante meu Case recebi um conjunto de dados para explorar minhas habilidades de análise de dados usando o Power BI. 
Em resumo, o conjunto de dados consiste em vinte e duas (10) colunas e mais de 5.000 linhas rotuladas como ID de linha, ID do pedido, Data do pedido, Data de envio, Modo de envio, ID do cliente, Nome do cliente, Segmento, País, Cidade, Estado, Postal Código, região, ID do produto, categoria, subcategoria, nome do produto, vendas, quantidade, desconto, lucro e margem de lucro. Abaixo o head dataframe

**LIMPAR O CONJUNTO DE DADOS**
Conforme discutido anteriormente em meu projeto anterior, a importância da limpeza de dados não pode ser exagerada para se obter um resultado adequado na visualização. Meu procedimento de limpeza no Excel consiste em excluir espaços em branco e duplicatas e convertê-los em uma tabela com formatação de cores.
**Baixando PoweR BI ou Atualizando**
Depois de iniciar meu Power BI Desktop, que baixei de seu site, carreguei os dados no programa aplicativo usando a opção obter dados, onde posso usar a consulta avançada para fazer algumas alterações adicionais, como agrupar colunas relevantes (como localização , cidade, estado, região, código postal, país, entre outras colunas agrupadas), adicionando e excluindo colunas quando apropriado, separando tabelas de fatos de tabelas de dimensão, identificando chaves primárias (ou seja, aquela com o valor mais baixo em cada grupo), e assim por diante .

Segue o link para baixar o power bi

Figure 1: Tabela e Data view

Depois de importar meu conjunto de dados para o Power BI, consegui ver o link entre minha tabela de fatos e minha tabela de dimensões usando a visualização do modelo.

Figura 2: Visualização da tabela e suas respectivas colunas a modelagem não era complexa com  relação entre tabelas de fatos e dimensões



**ANÁLISE DE DADOS**

Como a visualização às vezes é chamada de “a face de todo estudo”, muito trabalho foi dedicado a ela, inclusive em termos de formatação de página, formatação visual, layout visual e muitas outras áreas.

Página de visão geral: esta página exibe vendas totais de mais de dois milhões com lucro total de mais de duzentos mil em quarenta e nove estados, em três categorias de produtos.


Figura 3: página Visão geral

Desconto Regional: Os clientes da região Centro tiveram mais descontos, seguidos pelos da região Leste, Oeste e Sul.


Coloquei alguns tooltip para evoluir com algumas visões do meu case.


Figura 4: Desconto por região no gráfico de barras

Lucro Categórico: Os produtos vendidos foram categorizados em três; Tecnologia, material de escritório, Móveis com 50,79, 42,77 e 6,44 com percentual de lucro respectivamente.
 

Figura 7: Gráfico de oferta regional em áreas empilhadas

Lucro por cidade: Nova York, Los Angeles, Seattle, São Francisco e Detroit assumiram a liderança das cidades em lucro.

Recomendações: Devem ser atribuídas mais ofertas de descontos aos clientes ocidentais, de modo a aumentar as vendas, embora obtenham mais fornecimentos, o que também é uma forma de realizar mais vendas.

Em resumo, estando no século 21, a tecnologia, especialmente o telefone, mostrou que pode ser a linha de frente para outros produtos, realizando cerca de 33.000 vendas. Cerca de 20,5% de lucro foi obtido no oeste, principalmente na cidade de Nova York, mesmo com menor quantidade ofertada.




