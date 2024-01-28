## Cluster - ml_cluster_facebook

### Instalação de Pacotes

Para executar este código, é necessário instalar os seguintes pacotes no Python:

!pip install scikit-learn matplotlib pycaret pandas

## Resumo `<br>`

Este código implementa um modelo de clusterização utilizando o algoritmo K-Means em um conjunto de dados do Facebook. Ele realiza as seguintes etapas:

1. Carrega dados do Facebook.
2. Pré-processa os dados, normalizando as variáveis 'num_likes', 'num_comments' e 'num_shares' usando a escala Min-Max.
3. Aplica o algoritmo K-Means para agrupar os dados em três clusters.
4. Gera um gráfico de dispersão que visualiza os clusters com base nas variáveis 'num_likes' e 'num_shares'.
5. Calcula as estatísticas médias (média de 'num_likes', 'num_comments' e 'num_shares') para cada cluster e imprime o resultado.

O modelo ajuda a identificar padrões de comportamento nos dados do Facebook, agrupando os dados em clusters e fornecendo estatísticas médias para cada grupo, facilitando a interpretação e análise dos diferentes perfis de interação na plataforma.
