### Information Retrieval: 
encontrar informaçãoes relevantes em grandes volumes de dados com base em uma query. 

#### Três componentes:

`Indexing`: como criar um catálogo gigante e bem organizado. Isso envolve dividir o documento em partes menores como palavras e frases.

`querying`:processo de buscar no índice

`ranking`: não basta apenas encontrar os documentos que correspondem a busca, precisam estar ordenados por relevância.

#### Processo passo a passo:
- Data collection
- preprocessing
- indexing
- query
- ranking
- retrieval

#### Tokenization: 
Dividir em partes menores: word tokenization, sentence tokenizattion e character tokenization

#### Boolean Retrieval Model
Retorna apenas o que foi filtrado. Ou atende os critérios ou não. Faz uso de AND, OR, NOT.

#### Vector Space Model
Mais flexível, classifica os produtos que estão combinando com o filtro por relevância.

#### Probabilistic Retrieval Model
Ele ve a probabilidade de você gostar com base no perfil de pessoas similares. Sabe o que tá em alta e prevê, porém precisa de muito dado. 

#### VSM - Vector Space Model
Modelo que representa documentos e consultas como vetores no espaço multidimensional.

#### TF-IDF 
Uma técnica dentro de VSM que mede quanto uma palavra é importante comparado ao conjunto. 

Obs: importante passar colocar os dados todos em letras minísculas para se tratado igual semânticamente. (Casa != de casa)








