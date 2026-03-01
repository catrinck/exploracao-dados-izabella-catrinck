# Previsão do Tempo da Amazônia  
## Previsão do Tempo – Histórico (Março 2025)

## Exploração Estatística

Neste notebook foi realizada uma análise exploratória de dados meteorológicos referentes ao mês de março de 2025, com o objetivo de investigar padrões climáticos associados ao período conhecido como inverno amazônico.

Foram utilizadas as bibliotecas Python `pandas`, `numpy` e `matplotlib` para manipulação, análise e visualização dos dados. Inicialmente, o conjunto de dados foi carregado e inspecionado. Importante salientar que nenhuma valor nulo foi encontrado no dataset, demonstrando pureza nos dados.

Em seguida, foram calculadas estatísticas descritivas das principais variáveis climáticas, incluindo média, mediana, moda, valores mínimo e máximo, desvio padrão, variância, quartis e intervalo interquartil (IQR).

Também foram geradas visualizações gráficas — histogramas, boxplots e gráficos de série temporal — para analisar a distribuição dos dados, identificar possíveis outliers e observar o comportamento das temperaturas e velocidades do vento ao longo do tempo.

Por fim, os resultados estatísticos e gráficos foram interpretados para verificar se os padrões observados são compatíveis com as características típicas do inverno amazônico.

**Nome do Dataset:**  
Previsão do Tempo da Amazônia: Previsão do Tempo – Histórico (Mar 2025)

**Link:**  
https://dados.gov.br/dados/conjuntos-dados/previsao-climatica-do-censipam

**Órgão responsável:**  
Ministério da Defesa

**Descrição:**  
Dados relacionados ao histórico de previsão do tempo da Amazônia disponibilizados pelo CENSIPAM/MD, referentes ao mês de março de 2025.

### Estrutura do Dataset

- **Número de colunas:** 10  
- **Número de registros:** 9123

## Variáveis-chave analisadas

Para investigar o comportamento climático do mês de março de 2025, foram selecionadas variáveis meteorológicas diretamente relacionadas à caracterização do inverno amazônico:

**Temperatura Mínima (°C):**  
Representa a menor temperatura registrada no dia. Essa variável é importante para avaliar a estabilidade térmica noturna e a influência da cobertura de nuvens, comum em períodos chuvosos.

**Temperatura Máxima (°C):**  
Indica a maior temperatura diária observada. Permite analisar o aquecimento diurno e verificar a amplitude térmica diária, que tende a ser menor durante o inverno amazônico devido à nebulosidade frequente.

**Velocidade do Vento Mínima (km/h):**  
Refere-se à menor intensidade do vento registrada no dia, auxiliando na análise da estabilidade atmosférica e das variações locais das condições climáticas.

**Velocidade do Vento Máxima (km/h):**  
Corresponde ao maior valor diário da velocidade do vento, permitindo identificar possíveis episódios de maior instabilidade atmosférica.

**Condição Climática:**  
Variável categórica que descreve o estado do tempo (ex.: nublado, chuva, trovoadas). É fundamental para identificar a frequência de precipitações e confirmar características típicas do período chuvoso amazônico.
