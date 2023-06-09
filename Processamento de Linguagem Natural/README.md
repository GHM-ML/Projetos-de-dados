# Processamento de Linguagem Natural
Envolve a compreensão de linguagem humana pela máquina por meio de um algoritmo.
## Índice
- 1 - [ENEM 2021](https://github.com/GHM-ML/Projetos-de-dados/tree/main/ENEM%202021)

- 2 - [Imersão dados Alura](https://github.com/GHM-ML/Projetos-de-dados/tree/main/Imersao-dados-Alura)
 
- 3 - **Processamento de Linguagem Natural** 

    - 3.1 - [Predição de gênero musical](https://github.com/GHM-ML/Projetos-de-dados/tree/main/Processamento%20de%20Linguagem%20Natural/Predi%C3%A7%C3%A3o%20de%20g%C3%AAnero%20musical)

    - 3.2 - [Tweets de desastre](https://github.com/GHM-ML/Projetos-de-dados/tree/main/Processamento%20de%20Linguagem%20Natural/Tweets%20de%20desastre)
   
- 4 - [Trabalhos graduação](https://github.com/GHM-ML/Projetos-de-dados/tree/main/Trabalhos-graduacao)


## Conceitos:
- Tokenização - decompõe uma string em um conjunto de tokens. Neste caso, separa a string em uma lista de palavras.

- Stopwords (ou palavras de parada) - palavras sem significado e irrelevantes, melhor removê-las.

- Vetorização - essencialmente, converte dados de texto em dados numéricos, que são o tipo que o modelo consegue interpretar. Há várias técnicas, dentre as quais:

  - TF-IDF, sigla composta que representa um método que une dois conceitos:
    1. TF (Term Frequency) - frequência de uma palavra, em relação ao total de palavras do documento:
     
       - Quanto mais vezes uma palavra aparecer em um documento, maior o valor de TF. 
    
    2. IDF (Inverse Document Frequency) - Inverso da Document Frequency:
    
       - DF (Document Frequency): Frequência com que uma palavra está contida num documento, em relação ao total de documentos.
       - A ideia de usar o inverso (IDF) é que, quanto maior a frequência de uma palavra no total dos documentos, menos importante ela é para um só.
      
Uma palavra rara, então, aumenta o valor de IDF e,uma comum, diminui-o.

Usa-se o log para diminuir a escala da razão IDF.

**Se o valor de TF - IDF é o produto das partes, quanto maior os dois forem, mais o total vale.**
