## Estudo Dirigido 1 – Aprendizado Estatístico (CEFET-MG)

Este repositório contém um notebook em R (`AE_estudodirigido1.ipynb`) que implementa e explora conceitos estatísticos fundamentais por meio de simulações, conforme proposto no Estudo Dirigido 1 da disciplina de **Aprendizado Estatístico** do CEFET-MG.

### 📘 Conteúdo

O notebook cobre os seguintes tópicos:

1. **Simulação de Intervalos de Confiança**

   * Geração de população normal com média 180 e desvio padrão 20.
   * Simulação de milhares de amostras e verificação de cobertura dos ICs.
   * Interpretação de confiança como frequência de cobertura.

2. **Estimadores Não Viciados**

   * Simulação da média amostral como estimador não viciado.
   * Criação de estimador viciado para desvio padrão e comparação.

3. **Teorema Central do Limite**

   * Verificação da distribuição das médias amostrais.
   * Comparação com amostras pequenas (n=10) e grandes (n=100).

4. **Teste de Hipóteses (t-teste)**

   * Comparação entre dois algoritmos (A e B) quanto ao tempo de execução.
   * Verificação de homogeneidade de variâncias (teste F).
   * Aplicação de teste t com e sem variâncias iguais.

5. **Erro Tipo I**

   * Simulação de testes de hipóteses sob H₀ verdadeira.
   * Estimativa empírica da taxa de erro tipo I.

6. **Testes Múltiplos**

   * Comparações 2 a 2 entre três populações com mesma média.
   * Estimativa empírica do erro tipo I em testes múltiplos.

### 🛠️ Requisitos

Para executar o notebook corretamente, é necessário:

* R (≥ 4.0)
* R packages: `IRkernel`, `ggplot2`, `tidyverse`, etc. (dependendo do ambiente)

Você pode configurar o R para ser usado com o Jupyter executando:

```r
install.packages("IRkernel")
IRkernel::installspec()
```

Ou rodar o código diretamente em um script `.R` ou em RStudio.

### 💡 Como rodar

1. Clone este repositório.

2. Abra o notebook `AE_estudodirigido1.ipynb` em seu ambiente Jupyter com R configurado.

3. Execute as células sequencialmente.

### 📊 Resultados

O notebook permite visualizar graficamente conceitos estatísticos por meio de histogramas, densidades, e boxplots. Ele também mostra, por meio de simulações, a importância de considerar o tamanho amostral e os riscos de testes múltiplos.

### 📎 Fonte

Este estudo está baseado no material didático do CEFET-MG para a disciplina de Aprendizado Estatístico ministrada pelo professor Fabio Rocha da Silva.