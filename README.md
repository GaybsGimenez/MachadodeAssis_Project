# MachadodeAssis_project
Estudo das bibliotecas NLTK e scpaCy, corpora Machado

# O que foi feito/estudado aqui: 

## Pré-processamento do texto: limpeza do corpus com NLTK
- seleção apenas de caracteres não aufa-numéricos e padronição para todas as letras em minúsculo 
- remoção de stopwords
- junção dos tokens novamente em formato de texto
- tokenização
- contagem de frequência
  - plotagem do gráfico de frequência

## Concordânciador simples
- divisão com método split, array de strings
- concordance()

## Similaridade
- tmos uma lista de palavras que tendem a ocorrer no mesmo contexto 
  - Nesse caso, o contexto são apenas as palavras que ocorrem frequentemente de qualquer lado da palavra.

## Bigramas
Um bigrama ou digrama é uma sequência de dois elementos adjacentes de uma sequência de tokens, que normalmente são letras, sílabas ou palavras.

São palavras no texto que possuem um sentido único estando juntas, podendo até ocorrer separadas, mas com um sentido quando juntas.

- analisar a ocorrência das palavras ao longo de todo o texto - posição da lista em que a palavra aparece

# COMPARANDO COM OUTRA COMPORA DO MESMO AUTOR

# Pos-tagging: 
etiquetagem morfossintática de cada palavra desse corpora

## Gráficos
biblioteca: matplotlib.pyplot - estatistica descritiva
- Gráfico de barras simples

## Dicionário de ocorrência

## Identificar entidades nomeadas(NER) - com spacy
