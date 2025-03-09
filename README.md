
## Sobre a empresa
![image](https://github.com/user-attachments/assets/2492cb8d-688e-4c82-8a3a-cce848ff7135)

O iFood, líder no mercado de delivery online na América Latina, é uma empresa brasileira de tecnologia que conecta milhões de consumidores a restaurantes, mercados, farmácias e outros estabelecimentos. Através de um aplicativo intuitivo e eficiente, o iFood revolucionou a forma como as pessoas pedem comida e outros produtos, oferecendo conveniência, variedade e agilidade. A empresa investe continuamente em tecnologia e inovação para aprimorar a experiência de seus usuários, expandir seus serviços e fortalecer seu ecossistema, que inclui restaurantes parceiros e entregadores.
## Conjunto de dados

Neste desafio, o conjunto de dados em análise é composto por informações detalhadas sobre clientes do iFood, abrangendo seus perfis demográficos, preferências de produtos, histórico de campanhas de marketing (sucessos e fracassos) e desempenho dos canais de comunicação utilizados. 

## Objetivo
O objetivo principal é realizar uma análise exploratória minuciosa desses dados, utilizando a linguagem Python como ferramenta fundamental para compreender as características dos clientes e extrair insights relevantes sobre seus comportamentos e preferências.

## Insights Obtidos
Obtivemos insights a respeito do perfil de cliente e de gastos:

**Perfil do Cliente:**

**Renda:** A maioria dos clientes possui renda familiar anual entre 30.000 e 80.000, com distribuição simétrica e sem outliers. O coeficiente de variação indica uma dispersão moderada em torno da média (40%).

**Educação:** Predominância de clientes com ensino superior completo (Graduation), com baixa representatividade de clientes com apenas o ensino básico.

**Estado Civil:** Clientes casados (Married) e em união estável (Together) são maioria.

**Relação Estado Civil x Filhos:** A quantidade de filhos é similar entre os diferentes estados civis, com exceção de divorciados (Divorced), que tendem a ter um filho.

**Gastos:**

**Gastos x Filhos:** Clientes com 0 ou 1 filho apresentam maiores gastos (expenses) em média e mediana, seguidos por clientes com 3 e 2 filhos, respectivamente. Outliers superiores são observados nos grupos com 2 e 3 filhos, e em menor grau no grupo com 1 filho. Clientes sem filhos exibem uma distribuição mais próxima da normal.

**Gastos x Renda:** Existe uma correlação positiva e forte (0.82) entre renda (Income) e gastos (expenses), indicando que clientes com maior renda tendem a gastar mais na plataforma.

## Conclusão
A análise exploratória forneceu insights importantes sobre o perfil do cliente e seus gastos, o que pode auxiliar na tomada de decisões estratégicas, como campanhas de marketing segmentadas e personalização de ofertas.
## Ferramentas utilizadas
1. Pandas (pd);
2. NumPy (np);
3. Matplotlib (plt).
