#  Projeto de Acompanhamento de Vendas  em Power BI

![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/1d174595-e9a1-4b09-a294-f625e95a8da8)

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
Em resumo, o conjunto de dados consiste em vinte e duas (12) colunas e mais de 3211 linhas rotuladas como ( ID_Pedido, Data_Pedido, ID_Representante, Nome_Representante, Regional, ID_Produto, 
Nome_Produto, Valor_Produto, Quantidade_Vendida, Valor_Total_Venda, Nome_Cliente, Cidade_Cliente, Estado_Cliente)
 Abaixo o head dataframe

**LIMPAR O CONJUNTO DE DADOS**
Conforme discutido anteriormente em meu projeto anterior, a importância da limpeza de dados não pode ser exagerada para se obter um resultado adequado na visualização. Meu procedimento de limpeza no Excel consiste em excluir espaços em branco e duplicatas e convertê-los em uma tabela com formatação de cores.

**Baixando PoweR BI ou Atualizando**
Depois de iniciar meu Power BI Desktop, que baixei de seu site, carreguei os dados no programa aplicativo usando a opção obter dados, onde posso usar a consulta avançada para fazer algumas alterações adicionais, como agrupar colunas relevantes (ID_Pedido, Data_Pedido, ID_Representante, Nome_Representante, Regional, ID_Produto, Nome_Produto, Valor_Produto, Quantidade_Vendida, Valor_Total_Venda, Nome_Cliente, Cidade_Cliente, Estado_Cliente, entre outras colunas agrupadas), adicionando e excluindo colunas quando apropriado, identificando chaves primárias (ou seja, aquela com o valor mais baixo em cada grupo), e assim por diante .

Figure 1: Tabela e Data view
![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/c4318156-3b16-4218-89fc-f68000a8c54f)

Depois de importar meu conjunto de dados para o Power BI, consegui ver o link entre minha tabela usando a visualização do modelo.
Figura 2: Visualização da tabela e suas respectivas colunas a modelagem não era complexa com  relação entre tabelas de fatos e dimensões
![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/6f7192e9-7a0b-4481-b6e5-b40ea52ecd57)

Usei Base_Dados como referência para usar para achar as respostas das inferências.

**ANÁLISE DE DADOS**
Criei um layout para apresentação dos dashboards 

![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/14a87544-43c5-46ee-8d86-e2a5ca4388da)

Figura 3: página Visão geral

Foco em responder a primeira inferência >  Qual a receita obtida por vendedor ? : Fiz a escolha do gráfico de barras clusterizado, obtendo dados da coluna Valor Total Venda e Nome Representante

![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/afaeb129-6f5b-4671-b96c-54de04604690)

Seguindo  a segunda inferência > Qual a receita obtida por cada regional? Fiz a escolha do gráfico de rosca, obtendo os dados da coluna Valor Total Venda e Regional

![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/37bbd14c-3a3b-40a1-ac64-87462be5e21b)

Continuando a responder a terceira inferência > Qual a receita obtida por cada cliente? Fiz a escolha do gráfico coluna empilhada  obtendo os dados Valor Total Venda e Cliente

![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/4ed02ac3-8543-46e3-9b0a-8fe61efe61bf)

Como gráfico adicional para responder informações acima citadas, segmentadas em cada um dos estados, para uma análise mais profunda. Por fim, o gerente informou ainda que não tem tanto conhecimento nas possibilidades do Power BI, então foi adicionado "segmentação de dados para filtrar estado do cliente"

![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/85b06676-adce-4c84-b2c9-47650e5b3f94)

Para responder mais questionamentos adicionado um gráfico de dispersão obtendo os dados de valor total de venda, quantidade venda, nome do produto 

![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/99934a74-f2a3-4542-9284-3d72679fec4a)

Figura 4: Adicionei 3 visualizações tipo "cartões"  para representar Receita Total, Total itens vendidos, quantidade de pedidos
![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/bade5d22-eb43-4c2e-8ed3-f14df6bb17f7)

Como a visualização às vezes é chamada de “a face de todo estudo”, muito trabalho foi dedicado a ela, inclusive em termos de formatação de página, formatação visual, layout visual e muitas outras áreas.
Página de visão geral: esta página exibe vendas responde todas as perguntas do case com layout bacana!

 ![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/a6e4357b-169c-4f64-a971-ad8c1e07c150)

Recomendações Futuras: Devem ser atribuídas posteriormente alguns tooltips para detalhar informações de produtos, representante






