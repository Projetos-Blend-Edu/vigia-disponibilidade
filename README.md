# Vigia de disponibilidade (reserva)

Confere de hora em hora se os sites da Blend Edu respondem e avisa a equipe por
e-mail quando algum cai ou volta. É a **reserva** do vigia principal, que roda a cada
5 minutos em outro serviço.

Este repositório é público porque, assim, o GitHub não cobra os minutos de execução.
Por isso ele **não contém** código de produtos, dados, endereços nem chaves: a lista de
sites e a chave de envio de e-mail ficam em segredos cifrados do repositório, e os
registros públicos das execuções mostram apenas o nome de cada site.

Uma vez por mês o próprio vigia registra a data em `ultima-manutencao.txt`, porque o
GitHub desliga agendamentos de repositórios públicos sem atividade por 60 dias.
