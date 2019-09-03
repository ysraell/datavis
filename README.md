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


# Trilha 3: Liberdade Econômica.

### Introdução:

A liberdade econômica posibilita uma maior eficiência na produção de riqueza. Países/regiões que investiram no sentido de aumentar a liberdade econômica conseguiram melhorar seus índices socio-econômicos. Do outro lado, pode-se observar uma fuga de pessoas (principalmente com maior nível eduacional) de países menos livres para os mais livres (p.e.: fuca de Cuba para os EUA).

### Proposta:

Construir a apresentar um infográfico ou um painel (*dashboard*), com *storyboard* (painéis progressivos) opcional, com o objetivo de corrborar ou refutar a alegação da introdução.

## Especificações.

- 1) Apresentar na forma de painel de gráficos (*dashboard*) ou infográfico. No caso de painel, o *storyboard* é opcional. Apenas o infográfico pode ter barra de rolagem.
- 2) Responder e justificar apenas a pergunta  "O desarmamento civil produz resultados positivos para a população?". 
- 3) Não precisa explicar os métodos utilizados.
- 4) *Item removido*.
- 5) O painel ou o infográfico, **em PDF**, deve ser finalizado e enviado para o professor até às **18:00** do dia da apresentação. Envios posteriores serão desconsiderados a apresentação será cancelada (tendo como efeito o trabalho não entregue e com nota zero). O envio deve ser feito para o professor e para todos os integrantes do grupo na mesma mensagem.
- 6) O tempo de apresentação será de 10 minutos por grupo de alunos. Para cada 1 minuto excedente será descontado 1/10 do conceito da atividade, com o máximo de 5 minutos. O limite é de 15 minutos seguida de interrupção imediata.
- 7) É reservado 5 minutos para que o professor e os demais alunos façam perguntas e as respostas sejam dadas (ou seja, o tempo não sofre pausa).
- 8) Nenhuma observação será feita pelo professor no dia da apresentação.
- 9) Os grupos devem se organizar para realizar as apresentações com início às 19:00.
- 10) A presença na apresentação dos outros grupos faz parte da avaliação.
- 11) O intervalo de tempo entre o fim de uma apresentação e o início de outra será arbitrado pelo professor.
- 12) Formato da apresentação livre (mais de um dos integrantes podem apresentar).
- 13) *Item removido*
- 14) Salvo o item 11, a organização e as trocas de apresentação devem ser gerenciadas pelos próprios alunos.
- 15) Casos de ausências devem ser justificados (sem a necessidade de comprovantes ou atestados diversos) por e-mail.
- 16) Todos os grupos devem apresentar até o dia da apresentação, sem alternativa possível (pois é o ultimo dia de aula).
- 17) Antecipações serão permitidas e terão por feito nulo os itens 6 e 7, sendo os tempos, então, arbitrados com maior flexibilidade pelo professor no momento da apresentação.
- 18) É arbitrado ao professor modificar, anular e adicionar itens em qualquer tempo.
- 19) É arbitrado aos integrantes do grupo a melhor forma de apresentar e quais argumentos serão apresentados, não há limitações gerais.
- 20) Não será avaliado, nem julgado, pelo professor (e tão pouco verificado) os dados e informações usados, serão avaliados apenas os seguintes itens: qualidade do material produzido e o correto uso dos gráficos.
- 21) *Item removido*.

## Recomendações.

- 1) Não use blocos de textos e não leia durante a apresentação. Ainda que se use um infográfico, evite ao máximo textos volumosos.
- 2) Use até 6 quadros ou blocos de gráfico(s) (frames) até dois quadros progressivos (*storyboard*) por quadro.
- 3) Não conte a história do trabalho prévio, foque apenas em mostrar e justificar a análise e suas conclusões.
- 4) Ensaie a apresentação com um cronômetro com alarme.
- 5) Escreva os tópicos a serem tratados com um resumo das explicações e verifique se está coerente com o que é mostrado e se contribui como justificativa. Não há a necessidade de explicar o que deu errado previamente ou demais detalhes da análise que não sirvam como justificativa direta para os resultados.
- 6) *Item removido*
- 7) *Item removido* 
- 8) Não fique em dúvida, fale com o professor ou com os colegas. Mande e-mail para o professor com a dúvida quando não estiver em aula.

# Trilha 4: Inadimplência no Cartão de Crédito. (desatualizado)

### Introdução:

Com a maior popularização dos produtos como serviço (*as a service*), a automatização de crédito não ficaria de fora dessa. Com efeito, temos a modalidade de crédito como serviço (*credit as a service*), a qual fornece ao cliente um crédito de forma automatizada (sem intervenção humana). Nisso, abre-se um problema: como oferecer à financeira um nível de segurança adequado para o sistema automatizado de aprovação de crédito? 

No contexto apresentado, um gerente de uma financeira solicita a uma empresa de cientistas de dados uma forma de atribuir uma pontuação de risco de inadimplência de acordo, apenas, com o sexo, com o nível educacional, com o status matrimonial e com a idade. Tal forma poderá ser usada no sistema autônomo de crédito.

### Proposta:

Porduzir um painel (*dashboard*), com *storyboard* (painéis progressivos) opcional, com o qual justifica-se a forma utilizada de pontuação. A pontuação deve discriminar os clientes com diferentes características. Não há restrição em relação aos valores absolutos da pontuação. O cliente não está interessado em detalhes de inadimplência (quantas parcelas em atraso, tempo de atraso de pagamento etc.).

### Dados:

[Default Payments of Credit Card Clients in Taiwan from 2005](https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset#UCI_Credit_Card.csv)

Arquivo: UCI_Credit_Card.csv (~2,8 MB).

## Especificações.

- 1) Apresentar na forma de painel de gráficos (*dashboard*). O *storyboard* é opcional.
- 2) Apresentar e justificar apenas os resultados.
- 3) Não precisa explicar os métodos utilizados, mas deve, no mínimo, justificar o uso (durante a apresentação dos resultados).
- 4) O painel para apresentação (e possíveis painéis progressivos) pode ser estático ou dinâmico.
- 5) O painel **em PDF** deve ser enviado para o professor até às **18:00** do dia 15 de julho. Envios posteriores serão desconsiderados e a apresentação será cancelada, tendo como efeito o trabalho não entregue e com nota zero. O envio deve ser feito para o professor e para todos os integrantes do grupo no mesmo envio.
- 6) O tempo de apresentação será de 10 minutos por grupo de alunos. Para cada 1 minuto excedente será descontado 1/10 do conceito da atividade, com o máximo de 5 minutos. O limite é de 15 minutos seguida de interrupção imediata.
- 7) É reservado 5 minutos para que o gerente (cliente) faça perguntas e as respostas sejam dadas (ou seja, o tempo não sofre pausa).
- 8) Nenhuma observação será feita pelo professor no dia da apresentação.
- 9) Os grupos devem se organizar para realizar as apresentações com início às 19:00.
- 10) *Item removidp*
- 11) O intervalo de tempo entre o fim de uma apresentação e o início de outra será arbitrado pelo gerente (cliente).
- 12) Apenas um integrante do grupo apresenta;
- 13) os demais integrantes podem responder quando o gerente fizer perguntas.
- 14) Salvo os itens 10 e 11, a organização e as trocas de apresentação devem ser gerenciadas pelos próprios alunos.
- 15) Casos de ausências devem ser justificados (sem a necessidade de comprovantes ou atestados diversos) por e-mail.
- 16) Todos os grupos devem apresentar até o dia 15 de julho, não há alternativa.
- 17) Antecipações serão permitidas e terão por feito nulo os itens 6 e 7, sendo os tempos, então, arbitrados com maior flexibilidade pelo professor no momento da apresentação.
- 18) É arbitrado ao professor modificar, anular e adicionar itens em qualquer tempo.
- 19) É dispensada análise além dos dados disponibilizados. Não discorra sobre detalhes do contexto proposto que vão além dos dados e do que é solicitado. A analise deve ser totalmente orientado aos dados fornecidos.
- 20) Não será avaliado pelo professor (e tão pouco verificado) os resultados, mas, sim, as justificativas e a forma como foram apresentados.
- 21) Não há um desempenho mínimo de assertividade dos resultados, todavia não apresente resultados triviais.

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
