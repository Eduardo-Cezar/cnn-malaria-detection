# Detecção de Células Infectadas por Malária usando Redes Neurais Convolucionais (CNN)

Este repositório contém um notebook Python desenvolvido para classificar imagens de células sanguíneas em **infectadas** ou **não infectadas** por malária. O projeto utiliza uma **Rede Neural Convolucional (CNN)** para realizar a classificação, com o objetivo de alcançar alta precisão no diagnóstico precoce da doença.

## Sobre a Malária

A **malária** é uma doença infecciosa causada por parasitas do gênero **Plasmodium**, transmitidos aos seres humanos através da picada de mosquitos **Anopheles** infectados. É uma das doenças mais antigas e graves do mundo, afetando principalmente regiões tropicais e subtropicais, como a África Subsaariana, o Sudeste Asiático e partes da América do Sul.

### Sintomas e Impacto:
- **Sintomas**: Febre alta, calafrios, sudorese, dor de cabeça, náuseas e vômitos são os sintomas mais comuns. Em casos graves, a malária pode levar a complicações como anemia severa, insuficiência renal e até a morte.
- **Impacto Global**: A malária é uma das principais causas de mortalidade em países em desenvolvimento, especialmente entre crianças menores de 5 anos e mulheres grávidas. Segundo a Organização Mundial da Saúde (OMS), houve **241 milhões de casos de malária** e **627 mil mortes** em 2020.

### Diagnóstico e Tratamento:
- **Diagnóstico**: O diagnóstico precoce é crucial para o tratamento eficaz da malária. Tradicionalmente, o diagnóstico é feito através da análise microscópica de amostras de sangue, onde se busca identificar os parasitas da malária.
- **Tratamento**: O tratamento envolve o uso de medicamentos antimaláricos, como a cloroquina e a artemisinina. No entanto, o sucesso do tratamento depende de um diagnóstico rápido e preciso.

### Como o Algoritmo Pode Ajudar?
O algoritmo desenvolvido neste projeto utiliza **Redes Neurais Convolucionais (CNNs)** para classificar imagens de células sanguíneas em **infectadas** ou **não infectadas** por malária. Essa abordagem pode ajudar no diagnóstico precoce e automatizado da doença, oferecendo várias vantagens:

1. **Diagnóstico Rápido**: O algoritmo pode analisar imagens de células sanguíneas em segundos, acelerando o processo de diagnóstico em comparação com métodos tradicionais, como a microscopia.
2. **Precisão**: Com uma acurácia de **97,5%**, o algoritmo pode reduzir erros de diagnóstico, especialmente em regiões onde há escassez de profissionais treinados.
3. **Escalabilidade**: O modelo pode ser implementado em dispositivos móveis ou sistemas de saúde digitais, permitindo o diagnóstico em áreas remotas e de difícil acesso.
4. **Redução de Custos**: A automação do diagnóstico pode reduzir os custos associados ao treinamento de técnicos e ao tempo de análise manual.

### Como Funciona o Algoritmo?
O algoritmo utiliza uma **Rede Neural Convolucional (CNN)** para processar as imagens de células sanguíneas. A CNN é composta por várias camadas que extraem características das imagens, como bordas, texturas e padrões específicos associados à infecção por malária. Após o treinamento, o modelo é capaz de classificar as células em **infectadas** ou **não infectadas** com alta precisão.

## Descrição do Projeto

O projeto utiliza um conjunto de dados de imagens de células sanguíneas, onde cada imagem é classificada como **infectada** ou **não infectada** por malária. A arquitetura inicial é uma **Rede Neural Convolucional (CNN)**, que foi otimizada através da variação de hiperparâmetros, como o número de camadas, quantidade de neurônios e funções de ativação.

### Métricas Utilizadas:
- **Acurácia**: Para avaliar a precisão do modelo na classificação das células.
- **Função de Perda**: Para monitorar o desempenho do modelo durante o treinamento.

## Estrutura do Código

O notebook está organizado da seguinte forma:

1. **Introdução**: Apresentação do problema e dos dados.
2. **Metodologia**:
   - Carregamento e pré-processamento das imagens.
   - Definição da arquitetura inicial da CNN.
   - Treinamento do modelo.
3. **Otimização**:
   - Modificação 1: Adição de novas camadas de convolução, max pooling e dropout.
   - Modificação 2: Ajuste do número de neurônios na última camada convolucional.
4. **Resultados**: Comparação da acurácia antes e após as otimizações.
5. **Discussão**: Análise dos resultados e possíveis melhorias.

## Resultados

O modelo inicial, sem modificações, alcançou uma **acurácia de aproximadamente 93%**. Após as otimizações, o modelo final obteve uma **acurácia de 97,5%**, demonstrando uma melhoria significativa no desempenho.

### Comparação de Desempenho:
- **Modelo Inicial (CNN Base)**: Acurácia de **93%**.
- **Modelo Otimizado (Modificação 1)**: Acurácia de **97%**.
- **Modelo Final (Modificação 2)**: Acurácia de **97,5%**.

## Discussão dos Resultados

A otimização da arquitetura da CNN, através da variação do número de camadas, neurônios e funções de ativação, resultou em uma melhoria significativa na acurácia do modelo, alcançando **97,5%**. No entanto, é importante considerar o risco de **overfitting**, especialmente quando se busca melhorias adicionais no desempenho.
