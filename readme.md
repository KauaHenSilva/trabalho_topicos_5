## 1. Dados
- Faça o download da base de dados (utilize `sklearn.datasets` em Python ou um arquivo `.csv`).
> Feito usando curl no kelle
- Carregue os dados para análise.
> Feito usando pandas

## 2. Análise de Dados
- Desenvolva visualizações dos dados.
> Boxplot, scatter plot, 
- Encontre correlações entre as variáveis.
  - Responda: As características são altamente correlacionadas? Justifique.
  - Qual a predominância de malignos e benignos?

## 3. Cenários de Classificação
- Divida os experimentos em dois cenários:
  - Dados normalizados
  - Dados não normalizados
- Execute todo o processo separadamente para cada cenário.

## 4. Validação Cruzada
- Utilize validação hold-out (80% treino, 20% teste).
- Utilize validação cruzada com K=5.
- Utilize Leave-One-Out Cross Validation (LOOCV).

## 5. Aplicação do Algoritmo ID3
- Aplique o algoritmo ID3 na classificação dos dados.
- Avalie o desempenho utilizando todas as métricas estudadas.
- Compare os resultados entre os cenários e técnicas de validação.

## 6. Elaboração do Relatório
- Prepare uma apresentação (máximo 10 min por dupla) abordando:
  - Descobertas da análise exploratória
  - Classificação com ID3 nos cenários previstos
  - Estruture em introdução, desenvolvimento e conclusão
- Envie slides e código-fonte via SIGAA até 13/10.
- Apresentações em sala no dia 14/10.