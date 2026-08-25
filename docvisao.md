# 📖 Documento de visão 📖

## 1. introdução ✍️

### 🎯 Objetivo e público alvo
Este documento estabelece a visão estratégica, os objetivos de negócio, os perfis de 
usuários e as funcionalidades essenciais do aplicativo **Tropical Turbo**. O objetivo central 
é conectar comerciantes locais, moradores, turistas e entregadores em uma única rede logística 
eficiente e adaptada às peculiaridades insulares.

### ⚙️ Escopo do sistema
Aplicativo para gestão de pedidos, mapeamento comunitário e suporte à logística de entregas de
produtos como suprimentos básicos, produtos de farmácia, artesanato e encomendas.


## 2. Posicionamento ⬇️

### 🤝 Oportunidade de Negócio
Centralizar e profissionalizar o comércio local insular que hoje depende de grupos informais de mensagens, unificando a venda de alimentos, mantimentos e produtos essenciais em uma única plataforma.

### ❗ Especificação do Problema
Solucionar desafios de logística em ilhas, como ruas sem endereço oficial, proibição de veículos a combustão, instabilidade de internet e a extrema flutuação de demanda entre moradores e turistas.

### ‼️ Proposta de Solução
Criação de um aplicativo adaptado com mapeamento por pontos de referência e fotos, cálculo de rotas para entregas, a pé ou de bicicleta, e funcionamento offline para garantir as vendas mesmo sem sinal.


## 3. Descrição dos Stakeholders e Usuários 🙋‍♂️

O ecossistema do aplicativo engloba moradores locais, que buscam acesso previsível a refeições, gás, medicamentos e mantimentos com fretes justos, comerciantes locais que precisam de uma ferramenta leve para gerir vendas e estoque sem altas taxas e entregadores da comunidade, que exigem rotas otimizadas para deslocamentos a pé, de bicicleta/ moto ou barco com transparência em seus ganhos.


## 4. Visão geral do produto 🔬

### 🛠️ Recursos principais
Catálogo organizado: 
Produtos divididos por categorias como alimentação, farmácia, gás, conveniência e serviços locais.

Localização adaptativa: 
Mapeamento feito por fotos de fachada, pontos de referência informais e pino no mapa.

Agendamento e encomendas: 
Possibilidade de programar entregas com antecedência ou reservar produtos antes da chegada do barco de suprimentos.

Painel do comerciante e entregador: 
Interface leve para gestão simples de estoque, controle de horários e atribuição de rotas por zonas.

Rastreamento em tempo real: 
Acompanhamento do status do pedido e da rota da entrega ajustada para transporte a pé, de bicicleta ou barco.

### ⛔ Restrições
Mobilidade Limitada: 
Entregas restritas a modais não motorizados (a pé ou de bicicleta) ou pequenas embarcações.

Dependência de Conectividade Local: 
Operação sujeita a instabilidades na rede móvel e oscilações no sinal de internet da ilha.

Impacto Climático e de Marés: 
Entregas e estoque sujeitos a interrupções devido ao clima adverso ou fechamento da navegação marítima.


## 5. Requisitos de Alto Nível 🔍

### 💎 Requisitos Funcionais
Gestão de pedidos e catálogo: 
O sistema deve permitir a busca, visualização de produtos por categorias e a realização do checkout com pagamento digital ou na entrega.  

Mapeamento adaptativo: O sistema deve permitir o cadastro de endereços por meio de fotos da fachada, coordenadas no mapa e descrições de pontos de referência.  

Agendamento de entregas: O sistema deve possibilitar a encomenda programada de itens e reservas prévias alinhadas à chegada de suprimentos. 

Painel do comerciante: O sistema deve oferecer recursos para controle simples de estoque e ajuste dos produtos.

Distribuição e atribuição de rotas: O sistema deve direcionar os pedidos aos entregadores de acordo com suas zonas geográficas de atuação e capacidade de carga.  

Alertas climáticos e de maré: O sistema deve exibir avisos automáticos sobre condições adversas de tempo ou maré que afetem o tempo estimado de entrega.

### 💾 Requisitos Não Funcionais
Desempenho: 
O aplicativo deve carregar em no máximo 2 segundos, mantendo bom tempo de resposta mesmo sob conexões de dados móveis instáveis.

Disponibilidade e Tolerância a Falhas: 
O sistema deve contar com navegação via cache offline para permitir a consulta de cardápios e status de pedidos mesmo com quedas temporárias de internet na ilha.

Usabilidade e Acessibilidade: 
A interface deve ser simples, leve e intuitiva, com botões claros e navegação facilitada para acomodar usuários idosos ou com pouca familiaridade tecnológica. 


## 6. Restrições e Premissas ♟️

### ❌ Restrições
Tecnológicas: 
Necessidade de desenvolver uma aplicação extremamente leve para operar em conexões móveis lentas e com suporte a sincronização offline.

Operacionais: 
Proibição de veículos a combustão na região, limitando toda a logística de entregas ao uso de modais suaves.

Geográficas: 
Ausência de endereçamento formal (CEPs e nomes de ruas oficiais) em grande parte da comunidade, exigindo validação por pontos de referência informais. 

### 🤔 Premissas
Adesão Comercial: 
Os estabelecimentos locais irão migrar o atendimento de vendas informais por redes sociais para a plataforma centralizada.

Força de Trabalho Local: 
A comunidade contará com entregadores parceiros utilizando seus próprios meios de transporte não motorizados.

Infraestrutura de Rede: 
A região manterá um sinal básico e funcional de telefonia/internet para permitir a sincronização dos dados do aplicativo.


## 7. Riscos e Dependências 📊

### ⚠️ Riscos
Inoperância por falhas de conectividade: 
Quedas prolongadas na rede de internet móvel da ilha podem impedir o processamento de novos pedidos e o rastreamento em tempo real.

Desabastecimento por condições climáticas: 
Marés altas, tempestades e ventanias que fechem os canais de navegação podem interromper o estoque dos comerciantes locais.

Sobrecarga na alta temporada: 
O aumento repentino do volume de pedidos durante feriados e férias pode sobrecarregar a capacidade logística dos entregadores locais.  

### 🫂 Dependências
Engajamento do comércio local: 
O funcionamento do sistema depende da adesão contínua de restaurantes, farmácias e mercados para manter o catálogo atualizado.

Frota local ativa: 
A viabilidade das entregas depende da disponibilidade diária de pessoas para realizar os trajetos.

Disponibilidade da infraestrutura de telecom: 
O sistema depende dos serviços prestados pelas operadoras locais de telefonia para a sincronização dos dados do aplicativo.