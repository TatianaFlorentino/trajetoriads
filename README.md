![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/ebdb52e2-b29d-4855-aaec-72429a6a667a)

## Desenvolvedores
| [<img src="https://avatars.githubusercontent.com/tatianaflorentino?v=4" width=115><br><sub>Tatiana Florentino</sub>](https://github.com/TatianaFlorentino) | 

<hr>


### Tópicos 

- [Desenvolvedores](#desenvolvedores)

- [Status do Projeto](#status-do-projeto)

- [Conjunto de Dados](#conjunto-de-dados)

- [Tratamento Dados](#tratamento-de-dados)

- [Power BI](#Power-BI)

- [Descrição do projeto](#descrição-do-projeto)

- [Funcionalidades](#funcionalidades)

- [Aplicação](#aplicação)

- [Ferramentas utilizadas](#ferramentas-utilizadas)

- [Acesso ao projeto](#acesso-ao-projeto)

- [Abrir e rodar o projeto](#abrir-e-rodar-o-projeto)

- [Etapas do Projeto](tapas-projeto)



## Status do Projeto

<p align="center">
   <img src="http://img.shields.io/static/v1?label=STATUS&message=CONCLUIDO&color=RED&style=for-the-badge" #vitrinedev/>
</p>


## Conjunto de Dados

Durante meu Case recebi um conjunto de dados para explorar minhas habilidades de análise de dados usando o Power BI. 
Em resumo, o conjunto de dados consiste em vinte e duas (12) colunas e mais de 3211 linhas rotuladas como ( ID_Pedido, Data_Pedido, ID_Representante, Nome_Representante, Regional, ID_Produto, 
Nome_Produto, Valor_Produto, Quantidade_Vendida, Valor_Total_Venda, Nome_Cliente, Cidade_Cliente, Estado_Cliente)
Abaixo o head dataframe


## Tratamento de Dados
Conforme discutido anteriormente em meu projeto anterior, a importância da limpeza de dados não pode ser exagerada para se obter um resultado adequado na visualização. 
Meu procedimento de limpeza no Excel consiste em excluir espaços em branco e duplicatas e convertê-los em uma tabela com formatação de cores.

## Power BI
Depois de iniciar meu Power BI Desktop, que baixei de seu site, 
carreguei os dados no programa aplicativo usando a opção obter dados, onde posso usar a consulta avançada para fazer algumas alterações adicionais, 
como agrupar colunas relevantes 
(ID_Pedido, Data_Pedido, ID_Representante, Nome_Representante, Regional, ID_Produto, Nome_Produto, Valor_Produto, Quantidade_Vendida, Valor_Total_Venda, Nome_Cliente,
 Cidade_Cliente, Estado_Cliente, entre outras colunas agrupadas), adicionando e excluindo colunas quando apropriado, identificando chaves primárias 
(ou seja, aquela com o valor mais baixo em cada grupo), e assim por diante .

## Descrição do projeto 

<p align="justify">
 Projeto em desenvolvimento de um case para mostrar habilidades no uso do power bi da microsoft tem referência a visualização dos dados. O Logo da empresa aqui é ficticio 
O relatório permitirá o monitoramento diário, contínuo das vendas, possibilitando que gestores,  acompanhem as vendas por representante, regional, estado, produtos mais vendidos, clientes em potencial.

![Descrição do case, Você recebeu uma base de dados de Vendas, do ano de 2020, de uma empresa que vende equipamentos eletrônicos para alguns grandes clientes corporativos. 
Você tem o desafio de analisar estas bases de dados e construir um relatório que responda as seguintes perguntas:
* Qual a receita obtida por vendedor? 
* Qual a receita obtida por cada regional? 
* Qual a receita obtida por cada cliente? 
* O gerente da empresa, também informou que gostaria de ter as informações acima, segmentadas em cada um dos estados, para uma análise mais profunda. Por fim,
 o gerente informou ainda que não tem tanto conhecimento nas possibilidades do Power BI, 
mas que gostaria de ter mais visões interessantes sobre os dados da empresa. Como você criaria este relatório em Power BI?
</p>

## Funcionalidades

:heavy_check_mark: `Visualização 1:` Plotar gráfico com receita obtida por vendedor

:heavy_check_mark: `Visualização 2:` Plotar gráfico com receita obtida por cada regional

:heavy_check_mark: `Visualização 3:` Plotar gráfico com receita obtida por cada cliente

:heavy_check_mark: `Visualização 4:` Plotar gráfico com receita obtida por produto

## Aplicação

<div align="center">

![Power BI Emulator](https://github.com/TatianaFlorentino/trajetoriads/blob/main/img/Case_PowerBI.gif)

</div>

###

## Ferramentas utilizadas

![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/d4273efa-33f5-406c-9d46-5bf8c72b8561)
![image](https://github.com/TatianaFlorentino/trajetoriads/assets/41309689/b8bb1483-546e-4a55-84cd-7ac3c845c4d6)



## Tecnologias-utilizadas

</a>![image](https://github.com/TatianaFlorentino/Classificacao/assets/41309689/13d6998e-8c41-4a99-b6d0-d76a5c8cda94)</a>

###

## Acesso ao projeto

Planilha excel está em csv, converta em xls para trabalhar no power bi [baixá-lo](https://github.com/TatianaFlorentino/trajetoriads/blob/main/1%20-%20Base%20de%20Dados.csv).

Você pode [acessar o código fonte do power bi, famoso  pbix](https://github.com/TatianaFlorentino/trajetoriads/blob/main/Case_Vendas.pbix)  

Plano de Fundo [baixá-lo](https://github.com/TatianaFlorentino/trajetoriads/blob/main/Plano%20de%20Fundo%20-%20Dashboard%20de%20Vendas%20(PC).pptx).

## Abrir e rodar o projeto

Após baixar o projeto, você pode abrir com o `Power BI Destop`. Para isso, na opção de arquivo clique em:importar


- Procure o local onde você baixou o projeto e o selecione;
- Por fim clique em `OK`.

Melhore essa visualização colocando tooltip, outros gráficos, boa sorte! 🏆 

## Etapas do Projeto

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









