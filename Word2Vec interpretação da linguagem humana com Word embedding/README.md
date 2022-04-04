## Bases de dados

[Treinamento](https://caelum-online-public.s3.amazonaws.com/1638-word-embedding/treino.csv)

[Teste](https://caelum-online-public.s3.amazonaws.com/1638-word-embedding/teste.csv)





1. One-hot encode

- Representação de palavras como um vetor;

- Criação de vetores de palavras com Sklearn.


2. Word2Vec: primeiro contato

- Conceituação de Word2Vec;

- Principais diferenças entre Word2Vec e representações tradicionais;

- Como transformar um arquivo .txt em um modelo Word2Vec com Gensim;

- Representações de palavras em 300 dimensões.


3. Explorando melhor o Word2Vec

- o que está por trás das 300 dimensões;

- a relacionar palavras;

- vieses nas representações Word2Vec.


4. Combinando vetores

- fluxo para combinar vetores de palavras;

- tokenizar texto removendo as pontuações;

- método para realizar a combinação dos vetores de palavras;

- inspeção de artigos para corrigir erros da vetorização de textos;

- apeimoramento da função de vetorização de texto.


5. Classicando com Word2wec

- como criar as matrizes de vetores dos dados de treino e teste;

- classificação de múltiplas classes com __Regressão logística__;

- como usar o __Classification report__;

- o que são Precision e Recall;

- a diferença entre a macro média e a média ponderada;

- como classificar e comparar modelos com o Dummy classifier.


6. Classicação com Word2vec Skip-gram

- como adaptar as funções para classificar usando o Skipgram;

- a comparar os resultados entre __Skipgram e CBOW__;

- algumas particularidades de Skipgram e CBOW.



Referências

[[1] StatQuest: regressão logística](https://youtu.be/yIYKR4sgzI8)

[[2] Scikit learn, 3.3. Metrics and scoring: quantifying the quality of predictions](https://scikit-learn.org/stable/modules/model_evaluation.html#model-evaluation)






