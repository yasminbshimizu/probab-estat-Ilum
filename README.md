# probab-estat-Ilum
 Códigos desenvolvidos ao longo da disciplina de Probabilidade e Estatística ministrada pelo Prof. Dr. Daniel Cassar, no segundo período de Ciência e Tecnologia na Ilum.

<img aling="center" width=900 src="./logos ilum cnpem mcti mec.png">

## ÍNDICE
* [Descrição do projeto](#descrição-do-projeto)
  - [Probabilidade e Estatística](#probabilidade-e-estatística)
  - [Os códigos](#os-códigos)
  - [Monstros da Semana](#monstros-da-semana)
  - [Criatura Lendária](#criatura-lendária)
* [Informações técnicas](#informações-técnicas)
* [Agradecimentos](#agradecimentos)
<br>

## Descrição do projeto
### Probabilidade e Estatística
A **disciplina de Probabilidade e Estatística**, ministrada pelo Prof. Dr. Daniel Roberto Cassar, possui carga horária de 30h, com 2h semanais ao longo de todo o semestre. As aulas consistem em exposições teóricas pelo professor, com exemplos práticos e exercícios semanais para consolidar o conteúdo abordado em sala, utilizando de uma abordagem computacional para tal. Desse modo, os temas abordados foram: 
 1. Estatística descritiva;
 2. População, amostra e correlação;
 3. Simulação e experimentos computacionais;
 4. Probabilidade;
 5. Probabilidade condicional;
 6. Distribuições de probabilidades discretas;
 7. Distribuições de probabilidades contínuas;
 8. Função de distribuição acumulada e momento, e outras distribuições de probabilidade;
 9. Teste de hipótese: introdução e simulação;
 10. Teste de hipótese com simulção;
 11. Testes de hipótese pareado e sem simulação;
 12. Teste de hipótese usuais.

### Os códigos
Neste repositório, encontram-se os códigos desenvolvidos semanalmente pela autora com base nas atividades passadas pelo professor (os "Monstros da semana"), além da última prova realizada como avaliação da disciplina ("Criatura lendária"). Todas as tarefas foram avaliadas ao longo do semestre, sendo que todos os monstros foram aprovados, e a criatura lendária recebeu pontuação máxima.

### Monstros da Semana
Os **Monstros da Semana** são atividades individuais semanais propostas pelo professor para consolidar os conceitos abordados em sala de aula. Foram realizados doze Monstros ao longo da disciplina, sendo eles:
 1. **Estatística descritiva**: análise exploratória de um conjunto de dados, utilizando estatísticas descritivas e suas representações gráficas.
 2. **A média das médias**: análise de propriedades do cálculo da média de amostras em comparação à sua população.
 3. **Meu computador, meu laboratório**: desenvolvimento de um experimento computacional partindo de uma situação hipotética.
 4. **Provavelmente relevante**: resolução de 5 exercícios sobre probabilidade.
 5. **To Bayes or not to Bayes**: considerando uma situação hipotética em que há dois eventos complementares $E_1$ e $E_2$, em que $E_1$ apresenta maior confiabilidade; foi feito o cálculo da probabilidade a posteriori de $E_1$ acontecer, utilizando o Teorema de Bayes.
 6. **Somando variáveis aleatórias**: abordagem de propriedades da soma de variáveis aleatórias.
 7. **Mister Bin(omial)**: estudo acerca de *pmf's* (função de massa de probabilidade).
 8. **Provavelmente re-relevante**: resolução de 3 exercícios sobre probabilidade.
 9. **Exercícios sobre distribuições - Goblin**: Resolução de 5 exercícios envolvendo *pdf* (função de densidade de probabilidade), *cdf* (função de distribuição acumulada), e  estatísticas de uma variável aleatória $X$.
 10. **Teste de Hipótese**: realização de um teste de hipótese partindo de uma distribuição normal.
 11. **O andar do bêbado**: simulação de sorteio aleatório de direções, com plotagem de gráficos e cálculo da distância da posição obtida da origem a cada sorteio.
 12. **O problema de Monty Hall**: simulação computacional do problema de Monty Hall, calculando a probabilidade de ganhar um prêmio no programa hipotético da questão.

### Criatura Lendária
A **Criatura Lendária** trata-se da avaliação final da disciplina de Probabilidade e Estatística, e consiste em uma avaliação em caderno Jupyter com três testes de hipótese a serem realizados, além de uma questão bônus para busca de outros testes de hipótese usuais. Os testes de hipótese realizados envolviam:
 1. Média da variável aleatória em questão, utilizando o `ttest1_samp` do módulo `scipy`.
 2. Teste de independência qui-quadrado entre duas variáveis aleatórias, utilizando o `scipy`.
 3. Comparação entre médias de quatro variáveis aleatórias através da *Análise de variância de um fator* (ANOVA) e do *teste da diferença honesta significativa de Tukey* (teste de Tukey-Kramer), utilizando as funções `f_oneway` e `tukey` do `scipy`.
 4. **Bônus**: Estudo do **teste de normalidade D'agostino-Pearson**, em comparação ao *teste de normalidade de Shapiro-Wilk*, ambos importados do `scipy`.

## Informações técnicas
* Linguagem de programação
  - Python 3.9
* Software
  - Jupyter Notebook
* Bibliotecas
  - Os
  - Pandas
  - Statistics
  - Matplotlib
  - Seaborn
  - Numpy
  - Random
  - Scipy
  - Scikit_posthoc
  - Itertools
<br>

## Agradecimentos

Agradeço, principalmente, ao Prof. Dr. Daniel Roberto Cassar, que ministrou as aula da disciplina, e propôs orientou na execução das atividades desenvolvidas. Agradeço também aos estagiários Duanny Onório e Eduardo de Moraes, que auxiliaram respondendo dúvidas ao longo do semestre, além dos colegas de classe pela parceria durante o desenvolvimento das resoluções ao longo do semestre. Por fim, agradeço à Ilum Escola de Ciência, que possibilitou o desenvolvimento de tal projeto.

<img aling="center" width=900 src="./logos ilum cnpem mcti mec.png">
