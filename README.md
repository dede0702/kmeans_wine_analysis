# K-means Wine Analysis

Este projeto tem como objetivo agrupar vinhos com características químicas similares utilizando o algoritmo de K-means. O agrupamento é feito com base em diversas propriedades químicas dos vinhos, permitindo uma análise mais detalhada de seus diferentes tipos.

## Descrição do Projeto

Neste projeto, aplicamos o algoritmo de K-means para realizar a clusterização de vinhos, baseando-se em atributos como teor alcoólico, acidez, e outros elementos químicos presentes no dataset. Além disso, utilizamos os métodos Elbow e Silhouette Score para determinar o número ideal de clusters.

## Dataset

O dataset utilizado contém diversas variáveis químicas dos vinhos, entre elas:
- Alcohol
- Malic Acid
- Ash
- Alcalinity of Ash
- Magnesium
- Total Phenols
- Flavanoids
- Nonflavanoid Phenols
- Proanthocyanins

O dataset está disponível no arquivo `wines.csv` neste repositório.

## Estrutura do Projeto

O projeto está estruturado em um único notebook que contém os seguintes passos:

1. Pré-processamento dos dados:
   - Remoção de dados nulos (se existirem)
   - Padronização dos dados utilizando `StandardScaler`

2. Aplicação do algoritmo K-means:
   - Uso dos métodos Elbow e Silhouette para identificar o número de clusters ideal.
   - Ajuste do modelo K-means e criação dos clusters.

3. Análise dos Grupos:
   - Comparação entre os clusters, com análise de variáveis como teor alcoólico e acidez.
   - Visualização da distribuição de características dentro de cada cluster.

## Requisitos

Para rodar este projeto, você precisará das seguintes bibliotecas Python:

- `pandas`
- `sklearn`
- `matplotlib`

Você pode instalar todas as dependências executando o seguinte comando:

```bash
pip install -r requirements.txt
```

## Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/kmeans-wine-analysis.git
   ```
   
2. Navegue até o diretório do projeto:
   ```bash
   cd kmeans-wine-analysis
   ```

3. Instale as dependências listadas em `requirements.txt`.

4. Execute o notebook `kmeans_wine_analysis.ipynb` para rodar a análise.

## Contribuições

Contribuições são bem-vindas! Se você tiver alguma ideia ou melhoria, fique à vontade para abrir uma issue ou enviar um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

Com esse README, seu repositório será organizado e fácil de entender por outros desenvolvedores e colaboradores!
