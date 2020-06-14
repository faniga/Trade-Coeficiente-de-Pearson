 Este programa em python tem como objetivo descobrir correlação entre duas bases de dados utilizando o coeficiente de Pearson afim de prevermos valores futuros. Primeiro conside uma base de dados target, como por exemplo, o preço do bitcoin em relação ao dolar na corretora binance(BTCUSDT) no intervalo de 30 minutos. Considere então uma outra base de dados(preditiva) de mesmo intervalo de outra criptomoeda da binance, porém muito maior e que não contenha os ultimos 30 valores(ETHBTC). O programa então percorre por toda a base de dados preditiva e tenta encontrar o melhor pedaço desta base(de mesmo tamanho da base target) que tenha a melhor correlação entre a base de dados target. Para isto usamos um laço de repetição e o coeficiente de Pearson. Em seguinda é plotado uma gráfico de ambas as bases juntas(entre o pedaço encontrado e target). Os valores posteriores entre a intersecção das bases de dados preditiva e target é a previsão.

 O programa em si faz oque foi descrito acima porém com varios pares de criptomoedas. O processo é lento. Não recomendo fazer previsões para coeficiente <= 0.93. Ideal seria >= 0.97.
