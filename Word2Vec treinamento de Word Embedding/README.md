# Criação de um modelo de classificação de categorias de títulos de textos utilizando Spacy, Word2Vec, Gensim e disponibilização de uma aplicação web utilizando Flask

Dados

- [Treinamento](https://caelum-online-public.s3.amazonaws.com/1638-word-embedding/treino.csv)

- [Teste](https://caelum-online-public.s3.amazonaws.com/1638-word-embedding/teste.csv)




1. Explorando o Spacy

- O que é o Spacy;
- Como o Spacy se organiza;
- O que é a estrutura de dados DOC;
- Como instalar e usar os dados modelos linguísticos em português do Spacy.

2. Pré-processamento com Spacy

- Tratamento dos dados para treinar um modelo Word2Vec;
- Como usar o Doc dos Spacy para ajudar no pré-processamento dos dados;
- Como paralelizar o pré-processamento com o Spacy (nlp.pipe).

3. Hiperparâmetros do Word2Vec

- O que são Hiperparâmetros;
- Como os alguns Hiperparâmetros influenciam no modelo;
- A criar o vocabulário para treinamento do modelo Word2Vec.

4. Treinamento do Word2Vec

- Como treinar seu modelo Word2Vec;
- A fazer uma avaliação qualitativa dos modelos;
- O workflow de treinamento do seu modelo Word2Vec.
> Primeiro, configuramos o modelo. Depois, construímos o vocabulário a partir do corpus e, por fim, treinamos a representação Word2Vec.

5. Vetorizando dados de treino-teste

- Função responsável pelo tratamento e tokenização dos textos;
- Função que combina os vetores de cada palavra e cria uma representação vetorial para a frase;
- Função que cria a representação vetorial de toda base de dados.
- Como otimizar o tempo de pré-processamento desabilitando notações e parser na criação do objeto Doc do Spacy;
- Como criar as funções para o desenvolvimento do modelo de classificação;
- E a preparar os dados para criação os dados para a classificador.

6. Treino e integração do classificador

- Como treinar o classificador de títulos;
- Como salvar seu modelo de classificação em um arquivo pickle;
- Como disponibilizar o modelo de classificação em uma aplicação web.

Referências

[[1] Spacy](https://spacy.io/)

[[2] Matemática que está por trás do modelo Word2Vec, no paper original do Tomas Mikolov.](https://arxiv.org/pdf/1301.3781.pdf)

[[3] Embbeding Project do Tensorflow explora de forma visual uma representação Word2Vec.](https://projector.tensorflow.org/)













