# 🎓 Fatec PLN Codes

Este repositório contém os códigos e materiais desenvolvidos durante as aulas de Processamento de Linguagem Natural (PLN) na **FATEC Mauá**, sob as orientações do professor [Rodolfo Lovera](https://github.com/rodolfo-lovera).

## 📌 Funcionalidades

Este repositório abrange os seguintes tópicos no contexto de PLN:

- **Fundamentos de PLN:** Tokenização, segmentação e semântica;
- **Pré-processamento de texto:** Limpeza, normalização, remoção de stopwords, stemming e lematização;
- **Representação de texto:** Técnicas de Bag of Words, TF-IDF e embeddings (Word2Vec, GloVe, FastText).

## 🚀 Tecnologias e Ferramentas

- **Linguagem:** Python
- **Bibliotecas:** spaCy, NLTK, Gensim, re e scikit-learn
- **Ambiente:** Jupyter Notebook (Google Colab)

## 🗂️: Estrutura do Repositório e Descrição das Aulas

Cada pasta do repositório representa uma aula e contém um arquivo de Jupyter Notebook criado pelo Google Colab com as atividades práticas realizadas no dia. Abaixo segue um resumo dos desenvolvimentos de cada aula:

- **Aula 2 - Fundamentos da linguística:** Fundamentos de PLN com exemplos práticos de tokenização (divisão de texto em unidades menores), segmentação e semântica. Utiliza as bibliotecas **spaCy**, **NLTK**, e **Gensim** para analisar texto em inglês e português (spaCy), tokenizar sentenças e palavras (NLTK) e treinar modelos Word2Vec para vetorização semântica (Gensim). Os exemplos incluem processamento de textos e construção de modelos semânticos simples.

- **Aula 3 - Bibliotecas e Corpora:** Uso da biblioteca **NLTK** para manipulação de corpora (Machado e Brown), contagem e análise de frequências de palavras, remoção de stopwords (palavras irrelevantes) e tokenização de duas formas diferentes (`word_tokenize` e `TweetTokenizer`). Os exemplos no código demonstram técnicas básicas para análise de texto em PLN.

- **Aula 4 - Limpeza de dados textuais:** Limpeza e normalização de dados textuais para remoção de ruído (eliminação de caracteres especiais e normalização de letras), tokenização, filtro de stopwords e stemming e lematização (redução e normalização de palavras às suas formas básicas). Inclui exemplos práticos de um processo completo para preparar textos em PLN utilizando essas técnicas.

- **Aula 5 - Representação de texto:** Representação de texto com **Bag of Words** (BoW) utilizando `CountVectorizer` para criar uma matriz de frequência de palavras a partir de textos, comparação entre as representações BoW e TF-IDF utilizando `TfidfVectorizer` para calcular frequências ponderadas de palavras e a combinação do processo de limpeza de dados e a representação BoW para gerar uma matriz vetorizada de textos processados (aulas 4 e 5). O código inclui exemplos práticos para cada um dos cenários, utilizando as bibliotecas **scikit-learn**, **NLTK** e **re**.

- **Aula 6 - Representação de texto com Embeddings:** Técnicas de embeddings de texto com **Word2Vec**, **GloVe** e **FastText** para representar palavras de forma vetorizada e analisar relações semânticas. Os processos incluem o treinamento de embeddings a partir de frases simples em português para calcular similaridades entre palavras (Word2Vec), utilização de embeddings pré-treinados em inglês para identificar a relação entre palavras e listar termos semanticamente próximos (GloVe) e embeddings pré-treinados em português para avaliar a similaridade entre as palavras mais próximas (FastText).

- **Aula 7 - Modelagem de Tópicos com Latent Dirichlet Allocation (LDA):** Utilização do modelo LDA para análise de tópicos em corpora textuais. Inclui o pré-processamento de textos com NLTK, como tokenização, remoção de stopwords e lematização. O corpus **Reuters** é utilizado como exemplo para treinar o modelo LDA e identificar tópicos ocultos nos documentos. O código também demonstra a criação de um dicionário, a conversão dos textos para o formato Bag of Words (BoW), e o treinamento do modelo LDA com 5 tópicos. Além disso, é mostrada a visualização interativa dos tópicos utilizando a biblioteca `pyLDAvis`. Um segundo exemplo usa um conjunto de dados em português para ilustrar a criação de um dicionário, o treinamento do modelo LDA com 3 tópicos e a visualização dos resultados.

  *PS: Explicações mais detalhadas sobre o código podem ser encontradas dentro do próprio Notebook da aula correspondente.*

- **Aula 8  - Introdução a ML para PLN:** Aborda a classificação de textos utilizando métodos probabilísticos e modelos de machine learning. O código inclui um corpus simples com rótulos de sentimento onde são calculadas as probabilidades a priori e condicionais para classificar novos textos com base em palavras. Além disso, são treinados modelos de **Naive Bayes** e **SVM** usando a técnica TF-IDF para representar os textos numericamente, e as performances dos modelos são avaliadas com o relatório de classificação. O exemplo demonstra o uso de scikit-learn para pré-processamento de texto e treinamento de modelos.

  *PS: Explicações mais detalhadas sobre o código podem ser encontradas dentro do próprio Notebook da aula correspondente.*

## ⚙️ Como Executar os Códigos do Repositório

Recomenda-se a utilização da plataforma [Google Colab](https://colab.google/) para a execução dos notebooks. Para executar os códigos presentes no repositório:

- Acesse um dos notebooks dentro das pastas do repositório;
- No topo do notebook, clique em **Open in Colab**;
- Clique no botão de play à esquerda dos trechos de código;
- Se solicitado, fazer login com uma conta do Google.

Com o login realizado, você pode executar o código já escrito ou realizar alterações temporárias para testar as funcionalidades. Caso queira salvar uma cópia do código para você:

- No topo superior esquerdo, clique em **Copiar para o Drive**.

Com uma cópia salva no Google Drive, quaisquer alterações que você realizar serão salvas automaticamente na sua conta do Google.

💻 Desenvolvido por Caroline Dainezi.
