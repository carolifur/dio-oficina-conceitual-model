# dio-oficina-conceitual-model

Para este novo desafio da Oficina Mecânica, o texto do README precisa ser um pouco mais detalhado que o anterior, pois você está construindo a lógica do zero. Como você está na trilha de QA, foquei em destacar a organização das entidades e as regras de negócio que você interpretou.

Aqui está um modelo completo para você copiar e colar no README.md do seu novo repositório:

🛠️ Projeto Conceitual de Banco de Dados - Sistema de Oficina
Este repositório contém o modelo conceitual de um sistema de controle e gerenciamento de execução de ordens de serviço (OS) em uma oficina mecânica, desenvolvido como desafio de projeto na DIO.

🎯 Objetivo
Criar um esquema conceitual do zero que recupere a lógica de negócio de uma oficina, onde clientes levam veículos para conserto, e equipes de mecânicos realizam os serviços.

🧩 Estrutura do Modelo
O diagrama foi estruturado em torno das seguintes entidades principais:

Cliente: Possui os dados de identificação e pode ser proprietário de um ou mais veículos.

Veículo: Registra os dados do automóvel que passará pela revisão ou conserto.

Ordem de Serviço (OS): O documento central que controla o status, a data de entrega e o valor total.

Serviço & Peça: Tabelas que compõem os itens da OS, permitindo o cálculo individualizado de mão de obra e materiais.

Equipe & Mecânico: Define quem são os profissionais responsáveis pela avaliação e execução dos serviços.

⚖️ Regras de Negócio Aplicadas
Durante a modelagem, considerei os seguintes cenários para garantir a qualidade dos dados:

Cálculo de Valor: O valor total da OS é derivado da soma dos serviços e das peças.

Fluxo de Status: A OS deve passar por estados (Aberto, Em Execução, Concluído, Cancelado) para permitir o rastreamento do progresso.

Vínculo de Equipe: Uma equipe é designada para a OS, e cada equipe é composta por múltiplos mecânicos especializados.

🛠️ Ferramentas Utilizadas
Draw.io para a criação do diagrama.

Git/GitHub para versionamento da documentação.

[https://github.com/carolifur/dio-oficina-conceitual-model/dio-oficina-mecanica.png]
