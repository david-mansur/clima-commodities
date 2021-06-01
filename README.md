# O IMPACTO DAS CONDIÇÕES CLIMÁTICAS NO VALOR DE COMERCIALIZAÇÃO DE COMMODITIES PRODUZIDAS NO BRASIL

Este projeto tem como proposta analisar o quanto as alterações no clima, impactam no valor de venda de algumas destas commodities agrícolas, são elas: Soja, Milho e Boi Gordo. Estas commodities foram selecionadas devido a sua relevância no mercado produtor e de consumo, ao modo que estes também são ativos listados na B3, a bolsa de valores do Brasil.

Serão analisados dados climáticos provenientes de estações climáticas do Instituto Nacional de Meteorologia (INMET) em localizações próximas aos principais pólos produtivos de cada commodities selecionada e valores de cotação para comercialização destas commodities seguindo os parâmetros do Centro de Estudos Avançados em Economia Aplicada (Cepea) da Escola Superior de Agricultura Luiza de Queiroz (Esalq) da Universidade de São Paulo (USP).

A metodologia aplicada pelo Cepea-Esalq-USP utiliza os seguintes parâmetros para cotação, são as seguintes:

###	Soja
Característica | Valor
--- | ---
Especificação do Produto | Soja brasileira em grão a granel tipo exportação
Moeda/Unidade de Medida | Dólares Americanos (USD) por saca de 60kg
Região de Referência | Produto posto no porto de Paranaguá, estado do Paraná, nas condições Entregue no Local (DAP) no pátio ou Livre ao Longo do Navio (FAZ) em armazéns/silos que efetuem carregamento de navios via corredor de exportação no Porto de Paranaguá
Código Ativo B3 | SFI


###	Milho
Característica | Valor
--- | ---
Especificação do Produto | Milho amarelo semi-duro, tipo 2, de odor e aspectos normais, em bom estado de conservação, livre de bagas de mamona e outras sementes prejudiciais e insetos vivos, duro ou semiduro, com umidade de até 14%, teor de impurezas máximo de 1% na peneira 3mm, máximo de 6% de grãos ardidos ou brotados e livre de grãos mofados e até 12% de grãos quebrados, partidos ou chochos
Moeda/Unidade de Medida	| Reais brasileiros (BRL) por saca de 60kg
Região de Referência | A região de referência é Campinas, no estado de São Paulo, base para o Indicador ESALQ/BM&FBOVESPA. O preço para a região de Campinas-SP se refere a compras e vendas ou a ofertas de compra e de venda para o produto originado em qualquer região do País posto em qualquer um dos 162 municípios indicados na metodologia completa, listada no anexo X
Código Ativo B3	| CCM

###	Boi Gordo
Característica | Valor
--- | ---
Especificação do Produto | Bovinos machos, com 16 (dezesseis) arrobas líquidas ou mais de carcaça e idade máxima de 42 (quarenta e dois) meses, de acordo com as especificações do contrato futuro de boi gordo da B3.
Moeda/Unidade de Medida | Reais brasileiros (BRL) por arroba
Região de Referência | A região onde está localizado o animal transacionado. Para o Indicador, são cinco: Araçatuba, Presidente Prudente, Bauru, São José do Rio Preto e Vale do Paraíba.
Código Ativo B3 | BGI


As áreas de plantação e cultivo do milho e soja e da criação de gado estão dispostas em diferentes localidades de uma mesma região, onde podem ocorrer diferentes estados climáticos ao mesmo tempo, além disso devido a característica de negociação e formação de preço de cada commodities selecionada, a salientar as diferentes regiões de referência, serão utilizadas múltiplas estações de meteorologia do INMET como referência para obtenção dos dados meteorológicos. 
São elas:

### Soja: 
A região de referência é a de escoamento, no Porto de Paranaguá/PR, desta forma não deve ser feita a captura dos dados meteorológicos desta localização.
A Empresa Brasileira de Pesquisa Agropecuária (Embrapa) define que o estado do Mato Grosso (MT), é o maior produtor de soja do Brasil. Sendo assim, serão analisados dados de todas as estações de meteorologia automáticas do INMET presentes neste estado, totalizando 39 estações.

Código | Estação	Localização Estação
--- | ---
A908 | AGUA BOA
A908 | AGUA BOA
A924 | ALTA FLORESTA
A909 | ALTO ARAGUAIA
A934 | ALTO TAQUARI
A910 | APIACAS
A927 | BRASNORTE
A941 | CACERES
A905 | CAMPO NOVO DOS PARECIS
A912 | CAMPO VERDE
A926 | CARLINDA
A913 | COMODORO
A918 | CONFRESA
A919 | COTRIGUACU
A901 | CUIABA
A930 | GAUCHA DO NORTE
A906 | GUARANTA DO NORTE
A932 | GUIRATINGA
A933 | ITIQUIRA
A914 | JUARA
A920 | JUINA
A928 | NOVA MARINGA
A929 | NOVA UBIRATA
A915 | PARANATINGA
A937 | PONTES E LACERDA
A935 | PORTO ESTRELA
A923 | PRIMAVERA DO LESTE
A916 | QUERENCIA
A907 | RONDONOPOLIS
A944 | ROSARIO OESTE
A903 | S.J. DO RIO CLARO
A936 | SALTO DO CEU
A931 | SANTO ANTONIO DO LESTE
A921 | SAO FELIX DO ARAGUAIA
A942 | SAO JOSE DO XINGU
A911 | SAPEZAL
A943 | SERRA NOVA DOURADA
A917 | SINOP
A904 | SORRISO
A902 | TANGARA DA SERRA
A922 | VILA BELA DA SANTISSIMA TRINDADE

Tabela I – Relação de Estações Meteorológicas analisada para a Soja

###	Milho: 
A região de referência para o Milho é a de Campinas/SP, dispondo de 162 munícipios, entretanto todos circundando a cidade referência em até cerca de 100km de raio ao em torno da referência. O INMET possui 7 estações automáticas implantadas dentro deste raio.

Código | Estação	Localização Estação
--- | ---
A174 | BARRA BONITA
A711 | BRAGANÇA PAULISTA
A738 | CASA BRANCA
A739 | ITAPIRA
A726 | PIRACICABA
A744 | SÃO CARLOS
A713 | SOROCABA

Tabela II – Relação de Estações Meteorológicas analisada para o Milho

###	Boi Gordo: 
A região de referência para formação de cotação de preços são as cidades de Araçatuba, Presidente Prudente, Bauru, São José do Rio Preto e Vale do Paraíba. No perímetro destas cidades o INMET possui 13 estações automáticas de coleta de informações do clima e que serão base para o estudo.

Código | Estação	Localização Estação
--- | ---
A736 | ARIRANHA
A741 | BARRA BONITA
A748 | BARRETOS
A705 | BAURU
A764 | BEBEDOURO
A769 | CACHOEIRA PAULISTA
A737 | IBITINGA
A735 | JOSÉ BONIFÁCIO
A707 | PRESIDENTE PRUDENTE
A718 | RANCHARIA
A740 | SÃO LUIZ DO PARAITINGA
A728 | TAUBATÉ
A734 | VALPARAÍSO

Tabela III – Relação de Estações Meteorológicas analisada para o Boi Gordo

O período desta análise é de 01 de setembro de 2018 até 31 de maio de 2021, totalizando assim 1005 dias para exploração.

O objetivo desta análise é identificar quais as condições e como alterações climáticas podem alterar as cotações de valor para negociação da soja, do milho e boi gordo.
