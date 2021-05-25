<p align="center">
  <img src="https://github.com/RogerioOMDS/Alura-Word2vec-Interpretacao/blob/master/logo2.png" width="100" height="100" />
</p>

Curso realizado na Alura para entender melhor o funcionamento e a utilização do Word2vec e do processo de Word Embedding para a realizaçãoo de alguns projetos pessoais.

O projeto consistiu em fazer uma classificação de notícias jornalísticas (colunas, esportes, mercado, cotidiano, mundo, ilustrada). Para isso, fez-se o processo de word Embedding, ou seja, transformou-se as palavras em vetores, com isso, palavras semelhantes se localizam em locais semelhantes do espaço vetorial. Isso permite o agrupamento de frases que apresentam significados semelhantes, o que permite a classificação.

Para este processo de word Embedding, utilizou-se um modelo já treinado do NILC - Núcleo Interinstitucional de Linguística Computacional e duas técnicas diferentes:

 - CBOW (Continuous Bag of Words), que tenta prever a palavra buscada a partir de um contexto;
 - Skipgram, que tenta prever o contexto dada uma palavra.

Para o modelo de Aprendizagem de Máquina que classificou as frases (notícias jornalísticas) foi utilizado uma simples Regressão Logística.

Os pacotes utilizados em python foram:
 - Pandas (leitura do banco de dados);
 - Sklearn (Modelos de Aprendizagem de Máquina);
 - Gensim (Para leitura do modelo pré-treinado de word Embeddings do NILC);
 - String (Para retirada das pontuações);
 - nltk (Para transformar textos em lista de palavras - processo chamado de tokenização);
 - numpy (estruturação de matrizes e vetores);

E a baixo o certificado da alegria :)

<p align="center">
  <img src="https://github.com/RogerioOMDS/Alura-Word2vec-Interpretacao/blob/master/word2vec.png" width="500" height="300" />
</p>
