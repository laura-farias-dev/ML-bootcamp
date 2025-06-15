
### 1. O que é Machine Learning?

É um campo da inteligência artificial que dá aos computadores a habilidade de aprender a partir de dados
---

### 2. Explique o conceito de conjunto de treinamento, conjunto de validação e conjunto de teste em machine learning.

- **Conjunto de Treinamento:** Usado para **ensinar** o modelo, permitindo que ele aprenda os padrões nos dados.
-   **Conjunto de Validação:** Usado para **ajustar** os parâmetros do modelo e escolher a melhor versão.
-   **Conjunto de Teste:** Usado para **avaliar** o desempenho final do modelo em dados nunca vistos, simulando seu comportamento no mundo real.

---

### 3. Explique como você lidaria com dados ausentes em um conjunto de dados de treinamento.

Dados ausentes podem prejudicar um modelo. Existem algumas abordagens para lidar com isso, por exemplo:

-   **Remoção:** Simplesmente remover as linhas ou colunas com dados faltantes.
-   **Imputação:** Preencher os valores ausentes usando:
    -   **Estatísticas:** Média, mediana ou moda da coluna.
    -   **Valores Fixos:** Um número como `0` ou uma categoria como `"Desconhecido"`.
    -   **Modelos Preditivos:** Usar outros algoritmos para prever os valores faltantes.

---

### 4. O que é uma matriz de confusão e como ela é usada para avaliar o desempenho de um modelo preditivo?

A **Matriz de Confusão** é uma ferramenta para avaliar o desempenho de um modelo de classificação. Ela mostra os acertos e erros do modelo, comparando as previsões com os valores reais.
A partir dela, conseguimos calcular métricas cruciais como **Acurácia** e **Precisão**, por exemplo.


---

### 5. Em quais áreas (tais como construção civil, agricultura, saúde, manufatura, entre outras) você acha mais interessante aplicar algoritmos de machine learning?

Pra mim, seria na **Saúde.** Ajudar médicos no diagnóstico precoce de doenças, como câncer, analisando exames de imagem. O potencial para salvar vidas é imenso.