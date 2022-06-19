# ANOVA_analise_variancia

ANOVA (Análise de Variância) é um teste estatístico utilizado para verificar se as "MÉDIAS" de dois ou mais grupos são significativamente diferentes entre si. Normalmente a ANOVA será aplicada para comparar mais de 2 grupos.  ANOVA é semelhante ao teste t, a diferença é que se você quiser comparar mais de dois grupos irá usar ANOVA.

Assim como a maioria dos testes estatísticos, a parte técnica não é o problema pois implementamos ANOVA com uma linha de código em R. O maior desafio está na definição das hipóteses  e  na  interpretação  do  resultado.

Estudo de caso: Uma empresa farmacêutica testou três formulações de um medicamento para  alívio  da  dor  para  quem  sofre  de  dor  de  cabeça(especificamente enxaqueca). Para  o experimento, 27 voluntários foram selecionados e 9 foram aleatoriamente designados para uma das três formulações do medicamento.

Os indivíduos foram instruídos a tomar o medicamento durante o próximo episódio de enxaqueca e relatar sua dor em uma escala de 1 a 10 (10 sendo a dor mais forte).Vamos criar uma massa de dados de teste simulando esses resultados.

Precisamos comparar se todos os três medicamentos  geram o mesmo efeito ou não. Ou seja:

•Se a MÉDIA de cada grupo é a mesma ou muito similar, significa que todos os três medicamentos são eficazes.

•Se a MÉDIA é diferente, significa que de três, apenas um ou dois medicamentos são eficazes.

Com base na resposta que desejamos obter, vamos definir as hipóteses para o teste estatístico:

•H0 (Hipótese Nula) = A MÉDIA dos grupos é a mesma.

•Ha (Hipótese Alternativa) = A MÉDIA de todos os grupos não é a mesma. 

ANOVA será usada como teste estatístico neste cenário. Nosso objetivo é rejeitar ou não a H0 (Nunca devemos dizer que aceitamos ou não. Devemos dizer que falhamos ou não em rejeitar a H0). 

O resultado da ANOVA será interpretado com base no valor-p. Valor-p a probabilidade de que a estatística do teste assuma um valor extremo em relação ao valor observado quando H0 é verdadeira.

Regra geral de interpretação (considerando o valor-p de 0.05):

•Valor-p baixo (menor que 0.05): Forte evidência empírica contra H0 (rejeitamos a H0). Isso indica probabilidade inferior a 5% de que a H0 está correta.

•Valor-p alto (maior que 0.05): Pouca ou nenhuma evidência empírica contra H0 (falhamos em rejeitar a H0).

•Valor-p exatamente igual a 0.05 – O Cientista de Dados decide se rejeita ou não a H0 ou se refaz o teste.


ESPAÑOL:
ANOVA (Análisis de Varianza) es una prueba estadística utilizada para verificar si los "PROMEDIOS" de dos o más grupos son significativamente diferentes entre sí. Normalmente se aplicará ANOVA para comparar más de 2 grupos. ANOVA es similar a la prueba t, la diferencia es que si desea comparar más de dos grupos, utilizará ANOVA.

Como con la mayoría de las pruebas estadísticas, la parte técnica no es el problema ya que implementamos ANOVA con una línea de código en R. El mayor desafío está en definir las hipótesis e interpretar el resultado.

Estudio de caso: una compañía farmacéutica probó tres formulaciones de un medicamento para el alivio del dolor para quienes sufren de dolor de cabeza (específicamente migraña). Para el experimento, se seleccionaron 27 voluntarios y 9 fueron asignados al azar a una de las tres formulaciones de medicamentos.

Se instruyó a los sujetos para que tomaran el medicamento durante su próximo episodio de migraña y para que reportaran su dolor en una escala de 1 a 10 (siendo 10 el dolor más fuerte). Vamos a crear una masa de datos de prueba que simulen estos resultados.

Necesitamos comparar si los tres medicamentos tienen el mismo efecto o no. O sea:

•Si el PROMEDIO de cada grupo es igual o muy similar, significa que los tres medicamentos son efectivos.

• Si el PROMEDIO es diferente, significa que de tres, solo uno o dos medicamentos son efectivos.

Con base en la respuesta que queremos obtener, definamos las hipótesis para la prueba estadística:

•H0 (Hipótesis Nula) = El PROMEDIO de los grupos es el mismo.

•Ha (Hipótesis Alternativa) = El PROMEDIO de todos los grupos no es el mismo.

ANOVA se utilizará como prueba estadística en este escenario. Nuestro objetivo es rechazar o no rechazar H0 (Nunca debemos decir que lo aceptamos o no. Debemos decir que fallamos o no rechazar H0).

El resultado de ANOVA se interpretará en función del valor p. P-valor la probabilidad de que el estadístico de prueba tome un valor extremo con respecto al valor observado cuando H0 es verdadera.

Regla general de interpretación (considerando el p-valor de 0,05):

•Valor p bajo (menos de 0,05): fuerte evidencia empírica en contra de H0 (rechazamos H0). Esto indica menos del 5% de probabilidad de que la H0 sea correcta.

•Valor p alto (superior a 0,05): Poca o ninguna evidencia empírica en contra de H0 (no logramos rechazar H0).

• Valor P exactamente igual a 0,05: el científico de datos decide si rechaza o no el H0 o vuelve a realizar la prueba.



