

## 1. Otimizando a análise

- O conceito de tokenização por pontuação.

- Como usar a biblioteca NLTK para realizar a tokenização por pontuação.

- Como analisar a word cloud e pareto, os comparando


## 2. Melhorando a visualização do pareto

- A alterar a lista de stop words.

- A realizar o tratamento para remover pontuação de um texto.


## 3. Normalização de textos

- Remover acentos com a biblioteca unidecode, para normalizar o texto.

- Modificar as stop words para remoção de acentos.

- A transformar todos os caracteres em minúsculo, normalizando o texto.


## 4. Evitando flexões e derivações nas palavras

- O conceito de stemming.

- Como evitar flexões e derivações de palavras com stemming.

- Como aplicar stemming usando NLTK.

- O que é RSLP, algoritmo para realizar stemming em português.


## 5. TF-IDF e Ngrams: técnicas mais avançadas

- O conceito de TF-IDF e Ngrams.

- Como criar o representação TF-IDF com SKlearn.

- Como criar os Ngrams com NLTK.

- Como aplicar Ngrams usando SKlearn.

- Os cuidados que se deve ter ao usar o Ngrams.


### Gerando tokens com pontuação

````python
from nltk import tokenize
frase = "Os cursos da escola são ótimos, além de ótimos, têm alunos ótimos!"
token_espaco = tokenize.WhitespaceTokenizer()
token_pontuacao = tokenize.WordPunctTokenizer()

token_1 = token_espaco.tokenize(frase)
token_2 = token_pontuacao.tokenize(frase)
````
````text

[“Os”, “cursos”, “da”, “escola”, “são”, “ótimos,”, “além”, “de”, “ótimos,”, “têm”, “alunos”, “ótimos!”] - WhitespaceTokenizer();

[“Os”, “cursos”, “da”, “escola”, “são”, “ótimos”, “,”, “além”, “de”, “ótimos”, “,”, “têm”, “alunos”, “ótimos”, “!”] - WordPunctTokenizer();

Comparando as saídas dos diferentes algoritmos o mais adequado a se escolher é o WordPunctTokenizer, visto que na primeira opção de método a palavra “ótimos” tem duas variações (“ótimos,”, “ótimos!”) e no segundo método há somente uma variação da mesma palavra.
````