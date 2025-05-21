# Análisis Causal de la Mortalidad de Renacuajos de Rana Carrizo

## Descripción
Breve resumen del proyecto:  
- Réplica y extensión del análisis de *Statistical Rethinking* (McElreath, cap. 13) sobre los datos experimentales de Vonesh & Bolker (2005) de *Hyperolius spinigularis* (“reedfrogs”).  
- Comparación de tres niveles de pooling (total, none, partial) y extensión a un modelo jerárquico con covariables (depredadores y tamaño).  
- Enfoque bayesiano y análisis causal mediante DAG.


## Principales resultados
Modelo 1: subajuste, predicciones en la media global.
Modelo 2: sobreajuste, alta varianza en tanques pequeños.
Modelo 3: equilibrio óptimo con shrinkage adaptativo.
Modelo 4: cuantifica efectos de depredadores (βₚ<0) y tamaño (βₛ≈0) y mejora la interpretación causal.

## Referencias
Vonesh, J. R., & Bolker, B. M. (2005). Compensatory larval responses and trade-offs associated with predator-induced hatching plasticity. Ecology, 86(6), 1580–1591.

McElreath, R. (2020). Statistical Rethinking: A Bayesian Course with Examples in R and Stan. Chapman & Hall/CRC.