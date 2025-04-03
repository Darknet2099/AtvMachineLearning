 # AtvMachineLearning 
Para esta atividade, selecionei a Database 'Atmospheric and Oceanic Dynamics'(*), que compila e formata dados climáticos de várias fontes verificadas para analisar o nível global do mar. Este dataset foi escolhido devido à sua abundância de dados e também pelo fato de que a elevação do nível do oceano se torna cada vez mais preocupante.

*https://www.kaggle.com/datasets/muhammadzakria2001/atmospheric-and-oceanic-dynamics/data 
## Tipos de Dados
- Date (Data) datetime64[ns]   
- GMSL (Church & White 2011) (aumento do nível do mar causado por mudanças climáticas) float 64 
- Long-run CO2 concentration (Concentração de gás carbônico á longo prazo) float 64  
- CO2 Global Emissions (Emissão global de gás carbônico) float 64 
- Long-run N2O concentration (Emissão de nitrogênio a longo prazo)  float 64 
- Per-capita N2O emissions in CO2 equivalents (Emissões per capita de N2O em equivalentes de CO2) float 64 
- Per-capita CH4 emissions in CO2 equivalents  (Emissões per capita de CH4 em equivalentes de CO2) float 64 
- Global land avg temp. anomaly (relative to 1961-90 average) (Anomalia da temperatura média global da terra (em relação à média de 1961-90)) float 64  
- Global Sea surface temp. anomaly (relative to 1961-90 average) (Anomalia da temperatura média da superfície do mar global (em relação à média de 1961-90)) float 64 
- Artic Sea Ice Extent Avg (Extensão Média do Gelo Marinho do Ártico) float 64  
- Antartica Sea Ice Extent Avg (Extensão Média do Gelo Marinho da Antártica) float 64 
## Proposta de técnica de Machine Learning
Para essa atividade, a técnica de Clustering foi escolhida devido à sua capacidade de agrupar dados semelhantes sem a necessidade de rótulos prévios. Isso é Bastante útil para identificar padrões e grupos dentro dos dados climáticos, que podem não ser imediatamente óbvios. O Clustering permite segmentar períodos de tempo com características climáticas semelhantes, ajudando a entender melhor as tendências e anomalias no comportamento do clima global.
# Objetivos possíveis de análise
## Objetivo Principal
- Identificação de Padrões Temporais: Agrupar períodos de tempo com características climáticas semelhantes para identificar padrões recorrentes.
Neste objetivo, faremos a utilização da técnica de Clustering para agrupar dados climáticos em períodos de tempo que apresentam características semelhantes. Isso Implica que, ao analisar a base de dados "Atmospheric and Oceanic Dynamics", você buscará identificar intervalos de tempo que compartilham padrões climáticos comuns, como aumento do nível do mar, anomalias de temperatura, concentrações de gases de efeito estufa, e extensão do gelo marinho. Ao agrupar esses períodos, Conseguimos: Detectar tendências climáticas, Entender ciclos climáticos e prever padrões futuros.
## Objetivos Secundários
- Anomalias Climáticas: Detectar anomalias climáticas que se desviam significativamente dos padrões normais, o que pode indicar eventos extremos ou mudanças climáticas acentuadas.
- Impacto das Emissões de Gases de Efeito Estufa: Analisar como as concentrações e emissões de gases de efeito estufa (CO2, N2O, CH4) influenciam a elevação do nível do mar e as anomalias de temperatura.
- Compreensão da Extensão do Gelo Marinho: Investigar como a extensão do gelo marinho no Ártico e na Antártica se correlaciona com outras variáveis climáticas.




