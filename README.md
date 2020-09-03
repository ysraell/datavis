# Trilha 1: Titanic

### Proposta:

Mostrar que é possível ordenar os passageiros por risco de vida com base no acidente ocorrido com o navio de passageiros britânico RMS Titanic, no dia 15 de abril de 1912. Deve-se utilizar apenas recursos baseados em gráficos (comuns na visualização de dados).

### Fundo conceitual:

Poucos dias após o acidente ocorrido com o navio de passageiros britânico RMS Titanic, no dia 15 de abril de 1912, um novo navio de mesmo modelo fará uma viagem com mesmo local de partida e mesmo local de destino. Uma seguradora foi contratada para oferecer um seguro individual para os passageiros. Um consultor dessa seguradora solicitou a algumas *startups* de ciência de dados que descobrissem quais são os principais fatores entre os que sobreviveram e os que não sobreviveram. 

#### Base de dados: 

- [CSV Aqui](titanic.csv)

- Kaggle, 'Titanic: Machine Learning from Disaster': https://www.kaggle.com/c/titanic/data

- Stanford, CS109, 'A Titanic Probability': https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/problem12.html

--------------------

# Trilha 2: E-mail marketing
## Contexto

### Introdução:
Uma montadora de veículos possui duas linhas de carros, uma popular e outra de luxo. O gerente de marketing tem como plano fazer uma envio massivo de mensagens eletrônicas (*E-mail marketing*) divulgando essas linhas de carros. Objetivando maior assertividade e menor custo, o gerente conclui que seria interessante divulgar a linha de luxo para o público que recebe mais de \$50k/ano e a linha popular para quem recebe menos. Ao verificar sua base de dados de clientes descobre que não possui o quanto cada um recebe por ano, todavia possui diversas outras informações compatíveis com a base de dados disponível do censo do ano passado (1994) do *US Census Bureau*. Não há garantia de que sejam as mesmas pessoas, mas os campos (colunas) são os mesmos. 

Considerando que cada mensagem deve divulgar apenas uma linha de carros, o orçamento para envio ainda precisa de aprovação, que um indivíduo pode receber apenas uma mensagens, o acesso a base de clientes é restrito e a limitação de grupos de envio é de até 2, o gerente precisa saber como gerar os dois agrupamentos para que a relação entre acertos (divulgação da linha de carros certa para o indivíduo com renda anual de acordo) e envios seja alta.

### Proposta:

O gerente solicita (a diversas *startups* de ciência de dados) que, com base no censo do ano passado, quais filtros devem ser usados para cada grupo, com até 2 grupos, de tal forma que a divulgação das linhas de carros tenha maior acerto com menos envios. 

### Gerente (público alvo):

Recém formado tecnólogo em [marketing pela UniRitter](https://www.uniritter.edu.br/graduacao/marketing)


#### Referências:

- [CSV Aqui](adult.csv)

- Adult Census Income: Predict whether income exceeds \$50K/yr based on census data. Access: https://www.kaggle.com/uciml/adult-census-income

- Whose income will exceed 50K? Access: https://www.kaggle.com/jiashenliu/who-can-earn-more-than-50k-per-year

--------------------

# Trilha 3: Inadimplência no Cartão de Crédito.

### Introdução:

Com a maior popularização dos produtos como serviço (*as a service*), a automatização de crédito não ficaria de fora dessa. Com efeito, temos a modalidade de crédito como serviço (*credit as a service*), a qual fornece ao cliente um crédito de forma automatizada (sem intervenção humana). Nisso, abre-se um problema: como oferecer à financeira um nível de segurança adequado para o sistema automatizado de aprovação de crédito (segurança quanto ao risco de inadimplência)?

No contexto apresentado, um gerente de uma financeira solicita a uma consultoria em ciência de dados uma forma de atribuir uma pontuação de risco de inadimplência de acordo, apenas, com o sexo, com o nível educacional, com o status matrimonial e com a idade. Tal forma poderá ser usada no sistema autônomo de crédito.

### Dados:

[Default Payments of Credit Card Clients in Taiwan from 2005](https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset#UCI_Credit_Card.csv)

Arquivo: UCI_Credit_Card.csv (~2,8 MB).

#### Referências:

[Default of credit card clients Data Set.](https://archive.ics.uci.edu/ml/datasets/default+of+credit+card+clients)

--------------------

# Trilha Final: Análise de serviço de suporte.

Um time de suporte possui 3 níveis de especialidade, e cada qual com seu grau de eficiência. Nos últimos dias houve um incremento significativo de clientes e de chamados. Você é um candidato à vaga de cientista de dados e lhe foi solicitada uma avaliação do histórico do suporte oferecendo insights nos quais serão tomadas ações para melhorar o atendimento dado pelo time de suporte.

Entrega: gerar insights sobre o histórico, como, por exemplo: quando um técnico de nível 1 era promovido, a demanda diminuía; um técnico de nível 3 é mais barato que 3 de nível 1 etc.

*Público-alvo:* diretor de TI (aka Cliente).

## Alguns pontos interessantes:

- 1) O Cliente não acredita que vale a pena ter mais de um nível 3 de forma permanente, houve um momento em que tivemos dois ao mesmo tempo, mas era temporário apenas para substituição. Será que com uma boa argumentação, não é possível fazer o Cliente mudar de ideia?
- 2) Todos os casos de saída de técnicos ocorreram por pedido do próprio técnico.
- 3) Até o momento, o limite de level 1 é de 8, do level 2 é 6 e do level 3 é 1. Vale a pena mudar esses limites? O Cliente acredita que não, mas você consegue fazê-lo mudar de ideia?
- 4) O Cliente espera insights especificamente lógicos com base nos dados, podendo considerar todos dados disponíveis.
- 5) Não há técnicos de nível 2 ou 3 contratados, a única forma de consegui-los é promovendo os de nível menor.

## Dados:

- 1) Disponíveis em `trilha_final3.csv`.
- 2) Os dados foram gerados por meio de uma simulação Gerador-Destruidor (simulando um negócio genérico como o de chamados no atendimento de suporte). Confiram o notebook Jupyter: `Trilha_Final_Simulador.ipynb`.
- 3) São as colunas:
- `qtd_D`: quantidade de chamados em atendimento não finalizados no mesmo dia.
- `qtd_G`: quantidade de chamados abertos ainda não atendidos.
- `qtd_dia`: quantidade de chamados abertos no dia.
- `n_L1`: quantidade de técnicos de nível 1.
- `n_L2`: quantidade de técnicos de nível 2.
- `n_L3`: quantidade de técnicos de nível 3.
- `des_dia_1`: quantidade chamados fechados pelos técnicos de nível 1.
- `des_dia_2`: quantidade chamados fechados pelos técnicos de nível 2.
- `des_dia_3`: quantidade chamados fechados pelos técnicos de nível 3.
- `n_Geradores`: quantidade de clientes.
- `custo_dia`: custo total no dia.
- `renda_dia`: renda no dia.
- `data`: data.
- 4) Alguns parâmetros adicionais:
- Custo diário do técnico de nível 1: '3000/20'
- Custo diário do técnico de nível 2: '4000/20'
- Custo diário do técnico de nível 3: '5500/20'
- Custo para subir do nível 1 para o nível 2: '3000'
- Custo para subir do nível 2 para o nível 3: '7000'
- 5) No valor `renda_dia` já é considerado o desconto de os outros custos da empresa, portanto ele pode ser considerado integralmente para custear o serviço de suporte. Todavia, uma proposta enxuta, que evite a explosão de chamados e acrescente o menor custo possível, é desejada.

--------------------
