# Atentados nas escolas norte-americanas
![Capa do Projeto](https://static01.nyt.com/images/2022/05/25/us/25texas-shooting-1/merlin_207508098_e5a8e48e-f224-44fa-89e9-1a77cd6d7c90-videoSixteenByNine3000.jpg)


# Sumário
* [Sumário](#sumário)
* [Introdução](#introdução)
* [Metodologia](#metodologia)


# Introdução
 Sabemos que os Estados Unidos é o país com o maior arsenal de armas de fogo em mãos de civis do mundo, equivalente a pouco mais de 40% de todas as armas que hoje circulam em nosso planeta (UOL, 2018), e com toda essa facilidade ao acesso a esses armamentos, surge um dos maiores problemas que o país enfrenta atualmente. Os atentados com armas de fogo em Escolas Americanas.

## 1.1. Objetivos
 Temos como intuito neste projeto acadêmico, realizar Análise Exploratória dos Dados do dataset [School Shooting Data](https://github.com/cnnlabs/cnn-school-shooting-data) a fim de transmitir a causa motivadora de tais atentados. Serão tratadas e respondidas os seguintes questionamentos neste projeto:

 * 1.Quais 3 os Estados e Cidades mais perigosos de acordo com número de mortes, vítimas ou quantidade de atentados?
 * 2.Os atentados ocorrem em maior quantidade no subúrbio ou nas áreas urbanas?
 * 3.Em qual ano ocorreram mais atentados e se o número está aumentando ou não?

 ## 1.2. Fonte de Dados
 A fonte de dados utilizada está disponível no Kaggle (https://www.kaggle.com/datasets/sujaykapadnis/school-shooting-data) e no Github da CNNlabs (https://github.com/cnnlabs/cnn-school-shooting-data). Os dados foram compilados pela prória CNNlabs de diversas fontes abertas e foram certificados pelo "MIT license".

## 1.3. Escopo do Projeto
 O escopo deste projeto se limita às análises dos seguintes pontos:
* A identificação das principais características dos eventos, tais como localização, número de vítimas, número de feridos.
* Identificação de padrões e tendências como a localidade e região da cidade onde ocorreram os eventos.

A análise de fatores de causa dos eventos, tipo de armamento, políticas ligadas ao porte de armas, histórico de saúde mental, histórico de vida dos atiradores não farão parte do escopo deste projeto.

## 1.4. Método de Análise
 Através do dataset, será realizada uma análise exploratória de dados através do Power BI.

## 1.5. Organização do Relatório
 O relatório final da análise dos dados está dividido da seguinte forma:
1. Introdução;
2. Objetivos;
3. Metodologia;
4. Análise e Consolidação;
5. Conclusão;
6. Referências.

# Metodologia
![Atentados nas escolas norte-americanas](https://github.com/davidallanr/grupo4A3BigData/assets/135774372/38832cb7-ffa3-48fe-86f8-e3ea25cef841)
   
    +------------------------------------------------------------------------+
    |                            Dicionário de dados                         |
    +-----------------+-----------------+--------------------------+---------+
    | Nome do campo   | Tipo de dados   | Descrição do campo       | Fonte   |
    +-----------------+-----------------+--------------------------+---------+
    | year            | text            | Ano da ocorrência        | CNN Labs|
    +-----------------+-----------------+--------------------------+---------+
    | city            | text            | Cidade da ocorrência     | CNN Labs|
    +-----------------+-----------------+--------------------------+---------+
    | state           | text            | Estado da ocorrência     | CNN Labs|
    +-----------------+-----------------+--------------------------+---------+
    | urbanrural      | text            | Se a ocorrência se passa | CNN Labs|
    |                 |                 | em área urbana, rural    |         |
    |                 |                 | ou subúrbio              |         |
    +-----------------+-----------------+--------------------------+---------+
    | killed          | whole number    | Quantidade de mortos     | CNN Labs|
    +-----------------+-----------------+--------------------------+---------+
    | injuried        | whole number    | Quantidade de feridas    | CNN Labs|
    +-----------------+-----------------+--------------------------+---------+
    | victims         | whole number    | Quantidade de vítimas    | CNN Labs|
    +-----------------+-----------------+--------------------------+---------+

## 2. Conclusão
 Com base nas perguntas previamente apresentadas e com a análise feita conforme a metodologia selecionada, conclui-se que em primeiro lugar, os três estados mais perigosos podem ser considerados Connecticut, Flórida e Texas. Assim, também entende-se que as ocorrências de tiroteios em escolas foram em sua maioria nas áreas urbanas. Por fim, nota-se um aumento significativo no número de ocorrências ao longo dos anos.
 Demais análises, que buscam responder cada uma das questões previamente levantadas podem ser encontradas no [Relatório](https://github.com/thuurtx/AtentadoEscolasEUA/blob/main/Relatorio_Final.pdf) e no [Pbix](https://github.com/thuurtx/AtentadoEscolasEUA/blob/main/AtentadosEscolasAmericanas.pbix).
 
