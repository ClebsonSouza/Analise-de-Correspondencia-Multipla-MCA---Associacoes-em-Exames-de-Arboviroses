### Revelando Associações em Exames de Arboviroses com Análise de Correspondência Múltipla

A Análise de Correspondência Múltipla (MCA) é uma ferramenta poderosa para a análise exploratória de dados categóricos. Sua capacidade de transformar dados complexos em representações visuais intuitivas a torna essencial em diversas áreas de pesquisa e aplicação prática, auxiliando na descoberta de padrões e associações significativas.

No contexto desse projeto de análise de exames de arboviroses (Dengue, Zika e Chikungunya), a MCA foi utilizada para descobrir padrões e associações entre os resultados dos exames e o tempo de recebimento (diferença entre data de coleta e data de recebimento).

#### 1 - Transformação dos Dados:

As variáveis categóricas, como resultados dos exames (positivo/negativo) e status de recebimento (diferentes intervalos de tempo), foram transformadas em uma matriz binária, facilitando a análise conjunta.

#### 2 - Matriz de Contingência:

Construímos uma matriz de contingência para capturar as frequências de coocorrência das categorias das variáveis envolvidas.

#### 3 - Cálculo das Inércias:

Calculamos a inércia, que mede a variância explicada pelas principais dimensões da MCA. Essas dimensões nos ajudam a identificar as relações mais significativas nos dados.

#### 4 - Decomposição em Componentes Principais:

A MCA decompôs a matriz de dados em componentes principais, maximizando a variância explicada e permitindo uma visualização clara das associações entre variáveis.

#### 5 - Plotagem das Dimensões:

As categorias das variáveis foram plotadas em um espaço bidimensional. No gráfico resultante, categorias próximas indicam maior similaridade ou associação.
