# Controle de Venda de Ingressos

![controle de venda de ingressos](https://user-images.githubusercontent.com/17755195/189212250-6979acfa-47c7-4687-824e-aaab23125c67.png)

 Esse projeto foi idealizado, como uma atividade avaliativa, seguindo as instruções dos professores responsáveis da disciplina Programação I do Curso de Análise e Desenvolvimento  de Sistemas da Unicesumar e usando Apache NetBeans IDE 14.
 
 ## Problema a Ser Resolvido 
 
 Caro estudante,

Temos por certo que os desafios sempre contribuem na aquisição de conhecimentos e competências desejadas. Sendo assim, faz-se necessário relacionar o que se aprende com situações reais que podem ser encontradas no cotidiano.

Nesta atividade, você é convidado a realizar uma atividade para verificar como a disciplina em questão pode contribuir na sua experiência e formação profissional. Por este motivo, nesta atividade MAPA, você é instigado a solucionar um problema voltado para sua área de formação.

Atente-se para as informações e realize um ótimo trabalho!

O setor de eventos foi um dos mais atingidos pelas restrições da pandemia da COVID 19.

“Responsável por pouco mais de 4% do PIB brasileiro, o setor de eventos foi um dos mais abalados pela pandemia da covid-19. Estima-se que as medidas restritivas impactaram 97% das empresas do setor, que deixaram de faturar ao menos R$ 230 bilhões em 2020 e 2021, segundo a Associação Brasileira de Promotores de Eventos (Abrape).” (Revista EXAME 2022)

Já para 2022 o cenário é outro, depois de tanto tempo, os eventos voltaram com tudo, um exemplo disso é o Rock in Rio 2022, evento que acontecerá em setembro de 2022 teve seus ingressos esgotados em poucas horas, mostrando a alta procura nesse período pós pandemia.

Sabendo disso você foi contratado para desenvolver um sistema de venda de ingressos para shows e eventos. Esse sistema deverá conter as seguintes regras:

- Armazenar dados de Evento: evento deverá ter como atributos, nome, data, valor único, capacidade máxima e uma lista de ingressos vendidos essas informações são obrigatórias.
- Armazenar dados de Ingresso: todo ingresso deverá ser nominal, portanto deverá ter o nome, CPF e o evento relacionado
- Devem existir 3 categorias de ingresso, Ingresso Pista, Ingresso VIP e Ingresso Camarote
- Nas classes de Ingressos, devem existir um método de calcular valor do ingresso, onde Pista é o valor único do evento, no VIP deve-se adicionar 30% sobre o valor único do evento e no Camarote adicionar 60%
- Para ingresso é preciso também um método mostrar resumo, onde mostrará o nome e o CPF do dono do ingresso e os dados do evento, como nome do evento e a data.
- Para cada tipo de ingresso, crie um método imprimirValor que retorna o tipo do ingresso com o valor calculado.
- Para evento deve existir um método vender ingresso, no qual irá adicionar o ingresso criado na lista, verificando se não excede a capacidade máxima do evento
- Para evento deve existir também um método pra mostrar a quantidade de ingressos vendidos.

Para funcionamento do programa, poderá ser criado uma classe Principal para que se crie os objetos e executem os métodos, sem ter a necessidade da criação de uma interação com usuário, os dados para os testes devem ser fictícios
