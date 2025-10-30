# Dados-Abertos---ANEEL

Scripts para conseguir dados filtrados, consequentemente análises profundas e construir gráficos;

A aquisição de dados foi validade diretamente no banco de dados da ANEEL, ao aplicar os filtros desejados
na site, foram exatamente os mesmos ao realizar o download pelos códigos em Python.

Diferença em banco de dados:
- Se os separadores das colunas, em .csv, forem em " , " (vírgula), utilizar código ELEKTRO;
- Se as colunas interessadas em separação estiverem separadas por " / " (barras), utilizar código ELEKTRO;

- Se os separadores das colunas, em .csv, forem em " ; " (ponto e vírgula), utilizar código EMS;
- Se as colunas interessadas em separação estiverem separadas por " - " (traço/hífen), utilizar código EMS;
