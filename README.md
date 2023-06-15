# Otimização de Markowitz

A otimização de Markowitz é um método utilizado para construir carteiras de investimentos eficientes e balanceadas, levando em consideração o retorno esperado e o risco associado a cada ativo. Desenvolvido pelo economista Harry Markowitz, o modelo de otimização de Markowitz baseia-se na ideia de que um investidor racional deve buscar maximizar o retorno de sua carteira para um determinado nível de risco ou minimizar o risco para um determinado nível de retorno.

## Fatores Necessários

Existem alguns fatores necessários para realizar a otimização de Markowitz de forma adequada. Em primeiro lugar, é essencial ter acesso a dados históricos de preços ou retornos dos ativos considerados na carteira. Esses dados são utilizados para estimar a matriz de covariância, que captura as relações de interdependência entre os ativos. Também é necessário definir um horizonte de tempo relevante para a análise, pois a volatilidade e a correlação dos ativos podem variar ao longo do tempo.

Além disso, a fronteira eficiente é um conceito fundamental na otimização de Markowitz. Ela representa o conjunto de todas as combinações de ativos que oferecem o maior retorno esperado para um determinado nível de risco, ou o menor risco para um determinado nível de retorno. A fronteira eficiente é construída através da combinação de diferentes proporções de alocação de ativos em uma carteira, variando a exposição a cada ativo.

## Simulações
Outro elemento importante na otimização de Markowitz são as simulações, permitindo explorar diferentes cenários e aprimorar as decisões de investimento. Essas simulações são utilizadas para lidar com as limitações e incertezas inerentes à abordagem de Markowitz, proporcionando uma visão mais realista e robusta.

Após gerar os cenários de retornos, é possível aplicar a otimização de Markowitz a cada cenário, construindo uma carteira eficiente para cada um deles. Isso resulta em um conjunto de diferentes alocações de ativos, cada uma correspondendo a um cenário específico. Em seguida, é possível analisar e avaliar as características e o desempenho dessas carteiras em diferentes condições de mercado.

É importante ressaltar que as simulações na otimização de Markowitz envolvem uma dose de subjetividade e dependem das suposições e premissas adotadas. Ao utilizar o retorno e a volatilidade histórica para projetar o futuro, a otimização desconsidera os ciclos do mercado. Assim, os resultados das simulações não devem ser considerados como predições infalíveis do futuro, mas sim como ferramentas que auxiliam na análise e no processo de tomada de decisão.

## Considerações Finais

Existem maneiras de mitigar as dificuldades apresentadas pelo modelo, impondo restrições que podem ajudar a lidar com certos desafios. Por exemplo, é possível impor restrições de exposição mínima e máxima por ativo, bem como restrições de turnover. No entanto, é importante reconhecer que essas restrições podem ser arbitrárias e muitas vezes refletem os vieses do investidor - exatamente os vieses que se busca evitar por meio de uma alocação sistemática.

Em resumo, embora a otimização de Markowitz seja uma abordagem valiosa para a construção de carteiras eficientes, é importante ter em mente suas limitações e considerar outras análises e abordagens complementares para tomar decisões de investimento mais robustas. A combinação da otimização de Markowitz com análises fundamentais, técnicas e fatores macroeconômicos pode fornecer uma visão mais abrangente e precisa do mercado e ajudar a mitigar os riscos associados a essa abordagem.

## Observações

* As ações escolhidas são dos EUA pois o mercado americano é mais "normal" que o brasileiro;
* O período escolhido para análise foi de 01/01/2015 a 31/12/2022;
* Foi utulizado retorno logarítmico para facilitar o cálculo da matriz de covariância e dos retornos esperados;
* Quanto maior o número de simulações mais preciso vai ser a otmização;
* Quanto maior o número de Ativos maior deverá ser o número de simulações feitas;

