# Projeto: Implementação e Análise do Algoritmo de K-means para Reconhecimento de Atividades Humanas
ResTIC36 - Residência em Software Trilha 3 - Ciência de dados

## Autores:

*[Grupo 95]*
- Vinícius de Oliveira Souza
- Sanley Pires


---

## Descrição:

Este projeto teve como objetivo implementar e analisar o algoritmo de K-means para a tarefa de
Reconhecimento de Atividades Humanas (HAR) utilizando o dataset "Human Activity Recognition 
Using Smartphones".

O projeto envolveu as seguintes etapas:
 1. Análise Exploratória dos Dados: Foi realizada uma análise exploratória para entender a 
estrutura dos dados, incluindo a verificação das dimensões do dataset, tipos de dados, matriz 
de correlação e redução de dimensionalidade com PCA.
 2. Implementação do K-means: O algoritmo de K-means foi implementado para agrupar as 
atividades humanas em clusters.
 3. Escolha do Número de Clusters: O número ideal de clusters foi determinado utilizando o 
método do cotovelo e o Silhouette Score.
 4. Avaliação do Modelo: A qualidade dos clusters foi avaliada usando métricas como 
Silhouette Score e Inércia.
 5. Otimização e Ajustes: O modelo foi otimizado com a normalização dos dados e a seleção 
de features.
 6. Relacionando Clusters e AVDs: Os clusters foram relacionados às atividades para entender 
a relação entre eles.

 Os resultados indicaram que o K-means foi capaz de identificar clusters significativos nas 
atividades humanas. As métricas de avaliação mostraram que o modelo teve um bom desempenho, e 
os gráficos demonstraram a coesão e separação dos clusters

---

## Tecnologias utilizadas:

- python 🐍
- pandas 🐼
- matplotlib 🎨
- seaborn 📈
- scikit-learn 🛠️
- numpy 🔢

## Estrutura dos arquivos:

- A pasta /src contém o código-fonte em fomrato de notebook .ipynb
- A pasta /docs contém o relatório do projeto
- A pasta raíz / contém o arquivo README.md e o dataset baixado


## Como executar:

- Clique no link e abra o notebook no Colab Open In Colab

- No Colab, salve uma cópia no seu Drive ou faça o download do notebook para sua máquina (trabalhar offline)

- No ambiente de execução, seja no Colab ou no seu editor, execute as células em sequência ou execute tudo de uma vez.

- As dependências e bibliotecas serão instaladas e carregadas no início.
- O dataset será baixado, no segundo momento.
- Os resultados e gráficos serão mostrados abaixo das devidas células.

Enjoy!