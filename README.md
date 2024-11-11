# Análise de Marketing Bancário

Entender o perfil e as necessidades dos clientes é muito importante para um negócio. Em muitos casos, esse tipo de análise não só permite oferecer uma experiência personalizada aos consumidores, como também contribui para o direcionamento de campanhas e o desenvolvimento de novos produtos, entre muitas outras possibilidades.

Com isso em mente, este projeto contém uma análise dos dados anônimos de uma campanha de marketing de um banco português, doados para a UC Irvine - Machine Learning Repository. A campanha foi realizada por telefone e tinha como produto um depósito a prazo bancário.

# Objetivos

O projeto tem como objetivos:

*   Entender o perfil dos clientes que aderiram ou não ao produto através da campanha;
*   Entender quais são os fatores associados à maior probabilidade de aquisição do produto;
*   Construir um modelo que prevê se um cliente irá adquirir ou não o produto;
*   Recomendar ações com base na análise dos dados.

# Insights obtidos

Os seguintes insights foram obtidas com a análise realizada:

*   O modelo acertou 66,4% das previsões de clientes que irão adquirir ou não o produto, sendo um resultado positivo;
*   O cliente possuir ou não crédito inadimplente não influencia na chance dele adquirir o produto;
*   A idade do cliente não influencia na chance dele adquirir o produto;
*   Quanto maior o poder aquisitivo do cliente maior a chance dele adquirir o produto. Em média, a diferença no "balance" entre o grupo das pessoas que adquiriram o produto e o grupo que não adquiriu está entre 401 e 599 euros;
*   Clientes com a profissão "retired" têm 67% a mais de chance de adquirir o produto do que clientes com a profissão "blue-collar";
*   Clientes solteiros têm 40% a mais de chance de adquirir o produto do que clientes casados;
*   Clientes com nível de educação "tertiary" têm 45% a mais de chance de adquirir o produto do que clientes com a educação "primary";
*   Clientes que não possuem empréstimo imobiliário têm 84% a mais de chance de adquirir o produto do que clientes que possuem;
*   Clientes que não possuem empréstimo pessoal têm 54% a mais de chance de adquirir o produto do que clientes que possuem;
*   Contatos realizados em março (o melhor mês) têm 7 vezes mais chance de sucesso do que contatos realizados em maio (o pior mês);
*   Clientes que adquiriram o produto de campanhas anteriores têm 9 vezes mais chance de adquirir o produto da campanha atual (em comparação com aqueles que não adquiriram o produto de campanhas anteriores);

# Ações potenciais

A partir das informações acima é possível traçar as seguintes ações:



*   Realizar campanhas focadas no perfil de clientes que possuem maior chance de adquirir o produto. Por exemplo, uma comunicação focada em indíviduos solteiros e com ensino superior, destacando benefícios financeiros do produto a longo prazo;
*   Criar um calendário de campanhas, focando os esforços para esse produto nos meses mais propensos à contratação;
*   Utilizar o modelo para identificar os clientes com maior chance de se interessar pelo produto, potencialmente diminuindo esforços e custos. O modelo também pode ser melhorado utilizando novos dados, buscando outras variáveis e verificando com os times de engenharia se é possível melhorar a taxa de valores "unknowns". Outras técnicas de previsão podem ser mais robustas a depender da necessidade, também sendo benéfico contatar o time de ciência de dados;
*   Possivelmente criar pacotes de produtos recomendados a cada grupo de clientes, o que pode exigir estudos adicionais com outros produtos e/ou estudos de segmentação de clientes;
*   Realizar estudos adicionais com foco nos perfis com baixa probabilidade de adquirir o produto, pois isso pode revelar oportunidades para o negócio. Perguntas do tipo "Nós temos algum produto que atenda esses clientes? Se não, é possível desenvolver um? Qual a necessidade deles?" devem ser feitas.
*   Monitorar o desempenho do produto com indicadores-chave (KPI's) e avaliar os ganhos financeiros após a aplicação dessas ações.

# Conclusão

Em resumo, análises desse tipo fornecem insights valiosos que beneficiam tanto a empresa quanto o cliente. Aplicar uma abordagem orientada por dados no dia a dia do negócio fortalece o relacionamento com o consumidor e aumenta as chances de sucesso de futuras decisões.
