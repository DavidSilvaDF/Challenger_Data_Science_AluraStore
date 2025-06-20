#  Como abrir e executar o projeto.

- Todo o projeto foi desenvolvido em **Python 3** e **Google Colab** (https://colab.research.google.com).
- As fontes dos dados foram planilhas de uma loja fictícia com o nome Alura Store com o CEO Sr João.
- As planilhas a mim compartilhada teve a finalidade de treinamento de análise de dados com a linguagem Python.
- A Conclusão do projeto encontra- se no final desta apresentação.


### 1. Clonar o repositório (se estiver usando GitHub)
```bash
git clone https://github.com/DavidSilvaDF/Challenger_Data_Science_AluraStore
```
### 2. Acessar o Colab
- Abrir o arquivo `AluraStoreBr.ipynb` no **Google Colab**. 
- Certifique-se de ter instalado as bibliotecas necessárias:
  - `pandas`
  - `matplotlib`
  - `numpy`
  - `seaborn` 

Você pode instalar bibliotecas no Colab com o comando "!pip install conforme o exemplo abaixo:
```python
!pip install pandas matplotlib seaborn
```

### 3. Executar o Notebook
- Excutar todas as células do notebook em sequência.
- Os gráficos serão exibidos automaticamente.

---

# 🗂️ Estrutura do Projeto

	- Análise de desempenho;
	- Métricas.
	- Faturamento.
	- Análise por categoria.
	- Conclusão.

---

## 📋 Propósito da Análise
O propósito final foi avaliar os conhecimentos em Python e colocar em prática os conhecimentos adquiridos até então, fazendo a análise de dados na loja da Alura Store, cujo o CEO é o senhor João.

---

# 📊 Análise de Desempenho das Lojas — Alura Store

O contexto deste, é fazer as análises de dados, com a linguagem de programação na qual poderemos sinalizar o senhor João quais das quatro lojas que poderá ser vendida para futuros investimentos. Para isso além de fazermos os cálculos ainda foi demostrado em gráficos para melhor visualização e melhor tomada de decisão. 
Levando em consideração, as métricas utilizadas como faturamento total, categorias de produtos com mais e menos vendas, avaliação média dos clientes em cada loja, custo médio de frete; com base nessas informações, foi obtidos os resultados, analisados e assim poderemos recomendar a loja para ser vendida sem prejuízos.

---

## 📊 Gráficos e Insights

- Gráfico pizza demostrando a venda geral e a participação de cada loja. 
- Loja com maior venda é a Loja 1 com o total de venda R$ 1,534,509.12 que representa 26,1% do geral de vendas e a Loja com menor venda é a Loja 4 com a venda de R$ 1,384,497.58 na qual representa 23,6% 


![Exibe gráfico faturamento por Loja](images/faturamento_loja.png)



## Vendas por categoria:

- Ao analisarmos cada categorias podemos analisar que a Loja 4 vende bem em alguns setores, mas ao analisarmos detalhadamente, no faturamento total, a mesma tem uma venda significativamente menor conforme a imagem abaixo:


![Exibe gráfico Vendas por categoria](images/Vendas_categoria.png)


A diferença de vendas entre as Lojas 1 e 4 é de R$150.011,54 

![Exibe tabela em excel](images/Tabela_excel_vendas.png)

-As maiores vendas das categorias estão destacadas na cor azul e as vendas de menor valor estão destacadas de vermelho, e a ultima coluna destacando quais as lojas de maior e menor vendas.

-A Loja 1 vende R$150.011,54 a mais que a Loja 4. pois é uma diferença muito significativa, que no final de um ano de R$1.800.138,48 que representa 8,33% de venda a mais que a venda mensal da Loja 1 na qual é a loja de maior venda entre as quatro lojas.


## Avaliação de clientes por loja.


Ao analisarmos a comparação de avaliação dos clientes de cada loja, percebemos que o senhor João tem uma equipe bem treinada, onde ao meu ver segue um padrão onde as avaliações dos clientes são bem parecidas com a média geral de 4,02.


![Exibe gráfico Avaliação de média por categoria](images/Avaliacao_media_loja.png)

Avaliação média por loja:
- Loja 1: 3.98
- Loja 2: 4.04
- Loja 3: 4.05
- Loja 4: 4.00

Embora que as avaliações de clientes são muito significativa, neste caso expecífico não é um ponto crucial para que seja realizado a venda da loja

## Produtos mais e menos vendidos.

![Exibe gráfico Avaliação de média por categoria](images/produtos_mais_e_menos_vendidos.png)

- Ao analisar os produtos mais e menos vendidos, vemos que na Loja 1 temos produtos como guardarroupas a venda é bem significativa (60x) enquanto o Celular ABXY (33x). Conhecendo o mercado de vendas, a venda de celular tinha que ser bem mais acentuada comparando com o guardarroupa. Porém a margem de venda é bem maior a do gaurdarroupa trazendo a venda bem mais saudável.

- Analisando a Loja 4 o produto mais vendido foi a cama box (62x) e menos vendido a Guitarra (33x), porém a guitarra a recorrência de vendas é bem menor que a de um celular (comparando a Loja 1) e a cama box a recorrência de venda também é menor que um guardarroupa (comparando a Loja 1).


## Frete médio por loja.


- Levando em consideração que a visualmente não é tão perceptível a diferença. Pois a diferença é de somente R$3,41 (três reais e quarenta e um centavos), mas a loja 4 está com a menor venda e assim comparando a loja 4, o frete é maior que a da loja 1 

![Exibe a média do Frete por Loja](images/frete_medio_loja.png)


## 🔍 **Principais Insights**:

- A **Loja 4** apresentou o menor faturamento total.
- Categorias de maior faturamento foram **Eletrônicos** e **Eletrodomésticos** para todas as lojas.

---

##  Conclusão:

Levando em consideração a todos os dados acima citado, conclui-se que a Loja 4 do senhor João deverá ser vendida, para que o ele possa dar prosseguimento no seu investimento, pois a loja 4 tem a menor venda e o seu lucro menor que as demais lojas.