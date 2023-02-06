# PREVISÂO DE PREÇOS DE PASSAGENS AÉREAS
PROBLEMA DE NEGÓCIO
Um dos grandes desafios dentro do mundo dos negócios das companhias aéreas ou afins, é prever uma estimativa de preços justo que seja adequado ao perfil dos clientes e das empresas portadoras desses serviços. Nesse contexto, se faz importante as análises dos dados para que se possa compreender o comportamento desse clientes no intuito de gerar valor competitivo através das técnicas de aprendizado de máquinas. Sendo assim esse projeto tem como onjetivo:

- Fazer uma estimativa de preços para passagens aéreas com base nos históricos dos passageiros

Conjunto dos dados

Companhia Aérea: Esta coluna terá todos os tipos de companhias aéreas como Indigo, Jet Airways, Air India e muitas outras.

Date_of_Journey: Esta coluna nos informará sobre a data em que a viagem do passageiro começará.

Fonte: Esta coluna contém o nome do local de onde começará a viagem do passageiro.

Destino: Esta coluna contém o nome do local para onde os passageiros queriam viajar.

Rota: Aqui podemos saber qual é a rota pela qual os passageiros optaram por viajar desde a sua origem até ao seu destino.

Arrival_Time: A hora de chegada é quando o passageiro chegará ao seu destino.

Duração: Duração é todo o período de tempo que um voo levará para completar sua jornada da origem ao destino.

Total_Stops: Isso nos informará em quantos lugares os voos vão parar lá para o voo em toda a viagem.

Additional_Info: Nesta coluna, obteremos informações sobre comida, tipo de comida e outras comodidades.

Preço: Preço do voo(referência Índia) para uma viagem completa incluindo todas as despesas antes do embarque.

CONSIDERAÇÕES FINAIS

Através das análises do dados verificou-se que:

Até 50% dos preços das passagens estão em torno de 8372 moeda local da india,sendo que exitem preços de 79.512 que reflete uam caracterísitica de serviços ou produtos diferenciado (voos executivos por exemplos).

Em relação preços e localização do inicio das viagens, percebe-se que os valores se emcontram nos custos de 10000 e 20000. Porém KOLKATA e DELHI apresentam uma leve supremacia em relação às outras. além disso, esse gráfico apresenta os cincos principais voos de origens

Quanto ao preço por destino se destaca COCHIN e BANGLORE com os melhores preços destinos. è importante ressaltar que os voos de destino se diferenciam em preços e localização aos de origens.

O maior número de viagens em relação ao preço, está com duração de 10hs e valor de 14714. porém existem preços menores com a mesma duraçao de viagens, levando a considerar que a duração do tempo de voo, não determina por si só as tarifas.Isso significa que é preciso conversar com a área de negócio sobre formação de preços.

Quanto á modelagemo modelo escolhido foi baseado nos testes com métricas de avaliação que precisou um erro médio absoluto de 6%, com assertividade de 94%,onde as variáveis explicativas contribuiram com o modelo em em 97%, porém é preciso que o modelo seja checado de forma a garantir à eficiencia da proposta
