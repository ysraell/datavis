# Trilha 1: Titanic

### Proposta:

Mostrar que é possível ordenar os passeiros por risco de vida com base no acidente ocorrido com o navio de passageiros britânico RMS Titanic, no dia 15 de abril de 1912. Deve-se utilizar apenas recursos baseados em gráficos (comuns na visualização de dados).

### Fundo conceitual:

Poucos dias após o acidente, um novo navio de mesmo modelo fará uma viagem com mesmo local de partida e mesmo local de destino. Uma seguradora foi contratada para oferecer um seguro individual para os passageiros. Um consultor dessa seguradora solicitou a algumas *startups* de ciência de dados que elaborassem um modelo que ordene os passageiros do Titanic em ordem de risco de vida e, a partir disso, mostrar quais características são mais discriminates para isso. O consultor quer ver quais são as tais características e um resumo do modelo (com as equações mais relevantes).

### Entregável:

- Se apresentação em telas (*slides*): uma tela de apresentação geral do grupo, uma tela para cada gráfico, uma tela para o resumo do modelo usado.
- Se painel (*dashboard*): um painel com os gráficos e uma tela com o resumo modelo usado.

#### Base de dados: 

- Kaggle, 'Titanic: Machine Learning from Disaster': https://www.kaggle.com/c/titanic/data

- Stanford, CS109, 'A Titanic Probability': https://web.stanford.edu/class/archive/cs/cs109/cs109.1166/problem12.html

## Especificações.

1) Um dos integrantes deve mandar o material (sem os dados) produzido por e-mail para o professor copiando todos os demais integrantes. Deve constar no corpo do e-mail o nome completo.

--------------------

# Trilha 2: E-mail marketing
## Contexto

### Introdução:
Uma montadora de veículos possui duas linhas de carros, uma popular e outra de luxo. O gerente de marketing tem como plano fazer uma envio massivo de mensagens eletrônicas (*E-mail marketing*) divulgando essas linhas de carros. Objetivando maior assertividade e menor custo, o gerente conclui que seria interessante divulgar a linha de luxo para o público que recebe mais de \$50k/ano e a linha popular para quem recebe menos. Ao verificar sua base de dados de clientes descobre que não possui o quanto cada um recebe por ano, todavia possui diversas outras informações compatíveis com a base de dados disponível do censo do ano passado (1994) do *US Census Bureau*. Não há garantia de que sejam as mesmas pessoas, mas os campos (colunas) são os mesmos. 

Considerando que cada mensagem deve divulgar apenas uma linha de carros, o orçamento para envio ainda precisa de aprovação, que um indivíduo pode receber até duas mensagens, o acesso a base de clientes é restrito e a limitação de grupos de envio é de até 6, o gerente precisa saber como gerar os agrupamentos para que a relação entre acertos (divulgação da linha de carros certa para o indivíduo com renda anual de acordo) e envios seja alta.

### Proposta:

O gerente solicita (a diversas *startups* de ciência de dados) que, com base no censo do ano passado, quais filtros devem ser usados para cada grupo, com até 6 grupos, de tal forma que a divulgação das linhas de carros tenha maior acerto com menos envios. 

### Entrega:

Os grupos e os filtros. Exemplo 1, são propostos 3 grupos: 1) idade abaixo de 30, 2) entre 30 e 60 e 3) maior que 60. Exemplo 2, 6 grupos, semelhante ao exemplo 1, adicionando o filtro por sexo. Os grupos são mutualmente exclusivos.

### Justificativa:

A justificativa deve ser feita via apresentação de um painel de gráficos (*dashboard*), explicando de forma objetiva porque os filtros entregues atendem ao requerido. Pode ser usado o recurso de paneis progressivos (*storyboard*), convergindo no painel principal.

### Gerente (público alvo):

Recém formado tecnólogo em marketing pela UniRitter: https://www.uniritter.edu.br/graduacao/marketing

## Especificações.

- 1) Apresentar na forma de painel de gráficos (*dashboard*).
- 2) Apresentar e justificar apenas os resultados.
- 3) Não precisa explicar os métodos utilizados, mas deve, no mínimo, justificar o uso (durante a apresentação dos resultados).
- 4) O painel para apresentação (e possíveis painéis progressivos) deve ser estático e gerado em PDF.
- 5) O painel (em PDF) deve ser finalizado e enviado para o professor até às **18:00** do dia da apresentação. Para os casos de envio após 19:00, o conceito da atividade será divido por 2.
- 6) O tempo de apresentação será de 10 minutos por grupo de alunos. Para cada 1 minuto excedente será descontado 1/10 do conceito da atividade, com o máximo de 5 minutos. O limite é de 15 minutos seguida de interrupção imediata.
- 7) É reservado 5 minutos para que o gerente (cliente) faça perguntas e as respostas sejam dadas (ou seja, o tempo não sofre pausa).
- 8) Nenhuma observação será feita pelo professor no dia da apresentação.
- 9) Os grupos devem ser organizar para realizar as apresentações com início às 19:00.
- 10) O professor deixará o computador da sala com as apresentações prontas a partir das 19:00.
- 11) O intervalo de tempo entre o fim de uma apresentação e o início de outra será arbitrado pelo gerente (cliente).
- 12) Apenas um integrante do grupo apresenta;
- 13) os demais integrantes podem responder quando o gerente fizer perguntas.
- 14) Salvo os itens 10 e 11, a organização e as trocas de apresentação devem ser gerenciadas pelos próprios alunos.
- 15) Casos de ausências devem ser justificados (sem a necessidade de comprovantes ou atestados diversos) por e-mail.
- 16) Todos os grupos devem apresentar no dia da apresentação, podendo o professor arbitrar por transferir algum grupo para a aula seguinte.
- 17) Antecipações serão permitidas e terão por feito nulo os itens 6 e 7, sendo os tempos, então, arbitrados com maior flexibilidade pelo professor no momento da apresentação.
- 18) É arbitrado ao professor modificar, anular e adicionar itens em qualquer tempo.
- 19) É dispensada análise além dos dados disponibilizados. Não discorra sobre detalhes do contexto proposto que vão além dos dados e do que é solicitado. A analise deve ser totalmente orientado aos dados fornecidos.
- 20) Não será avaliado pelo professor (e tão pouco verificado) os grupos de filtros propostos, mas, sim, as justificativas e a forma como foram apresentadas.
- 21) Não há um desempenho mínimo de assertividade dos filtros, todavia não apresente resultados triviais.

## Recomendações.

- 1) Não use blocos de textos e não leia durante a apresentação.
- 2) Use até 6 quadros ou blocos de gráfico(s) (frames) até dois quadros progressivos (*storyboard*) por quadro.
- 3) Não conte a história do trabalho prévio, foque apenas em mostrar e justificar os resultados.
- 4) Ensaie a apresentação com um cronômetro com alarme.
- 5) Escreva os tópicos a serem tratados com um resumo das explicações e verifique se está coerente com o que é mostrado e se contribui como justificativa. Não há a necessidade de explicar o que deu errado previamente ou demais detalhes da análise que não sirvam como justificativa direta para os resultados.
- 6) Não há a necessidade se implementar um método específico para geração dos grupos, todavia, devido ao tamanho reduzido da base, com uma avaliação gráfica geral seguida de extração de *features* já se consegue um bom resultado com justificativa coerente.
- 7) Sendo redundante: o objetivo não é ganhar o primeiro lugar num desafio do *Kaggle*, mas é o de fazer uma apresentação clara, objetiva e coerente. Não importa a qualidade do resultado quando a forma como esse é apresentado é inadequada.
- 8) Não fique em dúvida, fale com o professor ou com os colegas. Mande e-mail para o professor com a dúvida quando não estiver em aula.

## Material de apoio.

### Programas para montar o painel:

#### Tableau
- Tableau cursos rápidos: https://www.tableau.com/pt-br/learn
- Tableau Public, versão gratuita: https://public.tableau.com/pt-br/s/
- Tableau Desktop por 14 dias: https://www.tableau.com/pt-br/products/trial
- Udacity Data Visualization in Tableau Free course:
https://www.udacity.com/course/data-visualization-in-tableau--ud1006

#### Qlik Sense
- Qlik Sense, versões Cloud e Desktop: https://www.qlik.com/pt-br/products/qlik-sense
- Cursos gratuito: https://qcc.qlik.com/course/view.php?id=279
#### MS Power BI

- Curso gratuito da DSA, Microsoft Power BI para Data Science: https://www.datascienceacademy.com.br/pages/todos-os-cursos-dsa

Referências retiradas do cap. 6 do curso citado acima:
- Dicas para construir um Dashboard eficiente https://powerbi.microsoft.com/pt-br/documentation/powerbi-service-tips-for-designing-a-great-dashboard/

- Painéis no Power BI https://powerbi.microsoft.com/pt-br/documentation/powerbi-service-dashboards/

### É apresentada uma forma de criar três grupos de filtro baseado em idade (sem justificativa) no notebook `Trilha2`.

#### Referências:

- Adult Census Income: Predict whether income exceeds \$50K/yr based on census data. Access: https://www.kaggle.com/uciml/adult-census-income

- Whose income will exceed 50K? Access: https://www.kaggle.com/jiashenliu/who-can-earn-more-than-50k-per-year

--------------------

# Trilha 3: Inadimplência no Cartão de Crédito.

### Introdução:

Com a maior popularização dos produtos como serviço (*as a service*), a automatização de crédito não ficaria de fora dessa. Com efeito, temos a modalidade de crédito como serviço (*credit as a service*), a qual fornece ao cliente um crédito de forma automatizada (sem intervenção humana). Nisso, abre-se um problema: como oferecer à financeira um nível de segurança adequado para o sistema automatizado de aprovação de crédito (segurança quanto ao risco de inadimplência)?

No contexto apresentado, um gerente de uma financeira solicita a uma consultoria em ciencia de dados uma forma de atribuir uma pontuação de risco de inadimplência de acordo, apenas, com o sexo, com o nível educacional, com o status matrimonial e com a idade. Tal forma poderá ser usada no sistema autônomo de crédito.

### Proposta:

Porduzir um painel (*dashboard*), com *storyboard* (painéis progressivos) **NÃO opcional**, com o qual justifica-se a forma utilizada de pontuação. A pontuação deve discriminar os clientes com diferentes características. Não há restrição em relação aos valores absolutos da pontuação. O cliente não está interessado em detalhes de inadimplência (quantas parcelas em atraso, tempo de atraso de pagamento etc.).

### Dados:

[Default Payments of Credit Card Clients in Taiwan from 2005](https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset#UCI_Credit_Card.csv)

Arquivo: UCI_Credit_Card.csv (~2,8 MB).

## Especificações.

- 1) Apresentar na forma de painel de gráficos (*dashboard*) **com *storyboard* **.
- 2) Apresentar e justificar apenas os resultados.
- 3) Não precisa explicar os métodos utilizados, mas deve, no mínimo, justificar o uso (durante a apresentação dos resultados).
- 4) O painel para apresentação e possíveis painéis progressivos (*storyboard*) podem ser estático ou dinâmico.
- 5) O painel **em PDF** deve ser enviado para o professor até às **18:00** do dia da apresentação. Envios posteriores serão desconsiderados e a apresentação será cancelada, tendo como efeito o trabalho não entregue e com nota zero. O envio deve ser feito para o professor e para todos os integrantes do grupo no mesmo envio.
- 6) O tempo de apresentação será de 10 minutos por grupo de alunos. Para cada 1 minuto excedente será descontado 1/10 do conceito da atividade, com o máximo de 5 minutos. O limite é de 15 minutos seguida de interrupção imediata.
- 7) É reservado 5 minutos para que o gerente (cliente) faça perguntas e as respostas sejam dadas (ou seja, o tempo não sofre pausa).
- 8) Nenhuma observação será feita pelo professor no dia da apresentação.
- 9) Os grupos devem se organizar para realizar as apresentações com início às 19:00.
- 10) O intervalo de tempo entre o fim de uma apresentação e o início de outra será arbitrado pelo gerente (cliente).
- 11) Apenas um integrante do grupo apresenta;
- 12) os demais integrantes podem responder quando o gerente fizer perguntas.
- 13) Salvo os itens 10 e 11, a organização e as trocas de apresentação devem ser gerenciadas pelos próprios alunos.
- 14) Casos de ausências devem ser justificados (sem a necessidade de comprovantes ou atestados diversos) por e-mail, todavia não isenta o aluno de apresentar o trabalho dentro das datas de aula dessa disciplina. Ao término das aulas, as notas serão fechadas.
- 15) Antecipações serão permitidas e terão por feito nulo os itens 6 e 7, sendo os tempos, então, arbitrados com maior flexibilidade pelo professor no momento da apresentação.
- 16) É arbitrado ao professor modificar, anular e adicionar itens em qualquer tempo. 
- 17) É dispensada análise além dos dados disponibilizados. Não discorra sobre detalhes do contexto proposto que vão além dos dados e do que é solicitado. A analise deve ser totalmente orientado aos dados fornecidos.
- 18) Não será avaliado pelo professor (e tão pouco verificado) os resultados, mas, sim, as justificativas e a forma como foram apresentados.
- 19) Não há um desempenho mínimo de assertividade dos resultados, todavia não apresente resultados triviais.

## Recomendações.

- 1) Não use blocos de textos e não leia durante a apresentação.
- 2) Use até 6 quadros ou blocos de gráfico(s) (frames) até dois quadros progressivos (*storyboard*) por quadro.
- 3) Não conte a história do trabalho prévio, foque apenas em mostrar e justificar os resultados.
- 4) Ensaie a apresentação com um cronômetro com alarme.
- 5) Escreva os tópicos a serem tratados com um resumo das explicações e verifique se está coerente com o que é mostrado e se contribui como justificativa. Não há a necessidade de explicar o que deu errado previamente ou demais detalhes da análise que não sirvam como justificativa direta para os resultados.
- 6) Não há a necessidade se implementar um método específico, todavia, devido ao tamanho reduzido da base, com uma avaliação gráfica geral seguida de extração de *features* já se consegue um bom resultado com justificativa coerente.
- 7) Sendo redundante: o objetivo não é ganhar o primeiro lugar num desafio do *Kaggle*, mas é o de fazer uma apresentação clara, objetiva e coerente. Não importa a qualidade do resultado quando a forma como esse é apresentado é inadequada.
- 8) Não fique em dúvida, fale com o professor ou com os colegas. Mande e-mail para o professor com a dúvida quando não estiver em aula.

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

## Requisitos de entrega:

- 1) No formato de painel (dashboard), com no máximo 8 frames, podendo discorrer sobre cada um individualmente na modalidade de painéis progressivos (storyboard).
- 2) Faça uma apresentação de até 8 minutos, podendo chegar em 10 minutos. A partir dos 10 minutos, você estará automaticamente desclassificado para concorrer à vaga ~e sua apresentação interrompida~.
- 3) No caso de desclassificação, não terá penalizações quanto a sua avaliação na disciplina.

## Especificações para apresentação:

- 1) Todos os grupos devem apresentar, caso alguém mais queira apresentar além dos sorteados, poderá fazê-lo após as principais.
- 2) Poderá haver apresentação antecipada. Basta informar o professor.
- 3) O Cliente está sempre disponível para tirar dúvidas e isso não afetará a sua classificação no recrutamento.

## Dados:

- 1) Disponíveis em `trilha_final2.csv`.
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

*Pontos dessa trilha:* conciso e objetivo.

### Dicas:

- 1) Treine a apresentação com um cronômetro!!
- 2) Foco nos argumentos! E não no história da sua análise e nem na EDA.
- 3) Apenas os quadros (frames) com os gráficos e bem pouco texto (só legendas ou highlights). Sem molduras, sem capa, sem floreios.



--------------------
