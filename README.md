Agente Virtual de Atendimento --- Pizzaria Bucho
Projeto de engenharia de prompts para estruturar um agente virtual
de atendimento ao cliente da Pizzaria Bucho, com foco em conversas pelo
WhatsApp.

O agente foi planejado para responder dúvidas sobre o cardápio e
orientar solicitações de pedidos com uma comunicação simples, cordial e
profissional. O prompt também define limites para evitar informações
inventadas e orientar o encaminhamento de situações que exigem
atendimento humano.
Objetivo
Criar um prompt claro e reutilizável que ajude a padronizar o
atendimento da pizzaria, oferecendo respostas úteis sem prometer ações
ou informações que o agente não pode confirmar.
Problema que o projeto busca resolver
No atendimento por mensagens, dúvidas sobre produtos e pedidos podem
exigir respostas rápidas e consistentes. Um agente sem orientações
claras pode fornecer preços incorretos, prometer disponibilidade ou
confirmar ações que não realizou.

Este projeto organiza instruções para reduzir esses riscos e deixar
explícito quando o atendimento deve ser encaminhado à equipe da
pizzaria.
O que foi desenvolvido
- Definição do papel, do público e do escopo do agente.
- Orientações de tom de voz e formato das respostas.
- Regras para uso exclusivo de informações oficiais.
- Limites de segurança e proteção de dados dos clientes.
- Critérios para encaminhar situações ao atendimento humano.
- Cenários de teste para avaliar o comportamento em situações
  difíceis.
- Prompt final unificado para configuração ou experimentação do
  agente.
Arquivo principal
- [`prompt_agente_pizzaria_bucho.md`](prompt_agente_pizzaria_bucho.md)
  --- contém as instruções completas do agente, os cenários de teste e
  o prompt final.
Como utilizar
1. Abra o arquivo
   [`prompt_agente_pizzaria_bucho.md`](prompt_agente_pizzaria_bucho.md).
2. Copie a seção Prompt final para utilização.
3. Cole o conteúdo nas instruções de um assistente de IA ou utilize-o
   para realizar testes em uma ferramenta de sua preferência.
4. Forneça ao agente uma base atualizada com as informações oficiais da
   pizzaria, como cardápio, ingredientes, preços, horários, formas de
   pagamento e regras de entrega.
5. Execute os cenários de teste e revise as respostas antes de qualquer
   uso com clientes.
Importante: este repositório contém um prompt. Ele não representa,
por si só, um chatbot conectado ao WhatsApp, um sistema de pedidos ou
uma integração com pagamentos e entregas. Essas funcionalidades exigem
desenvolvimento e conexão com ferramentas externas.

Critérios de qualidade
O agente deve:
- Responder em português do Brasil, com educação e objetividade.
- Não inventar preços, ingredientes, promoções, disponibilidade ou
  prazos.
- Não afirmar que registrou pedidos ou confirmou pagamentos sem
  evidência real.
- Fazer perguntas claras quando faltarem informações.
- Não solicitar senhas, códigos de autenticação ou dados completos de
  cartão.
- Encaminhar reclamações e situações que exijam autorização ou análise
  humana.
Tecnologias e ferramentas
- Engenharia de prompts: elaboração e refinamento das instruções
  do agente.
- Inteligência artificial generativa: ambiente para testar o
  comportamento do prompt.
- Markdown: documentação do projeto.
- Git e GitHub: versionamento e publicação do material.
Estrutura do repositório
agente-atendimento-pizzaria-bucho/
├── README.md
└── prompt_agente_pizzaria_bucho.md
Próximas melhorias
- Adicionar uma base oficial e atualizada do cardápio.
- Testar o prompt com perguntas reais e registrar os resultados.
- Documentar ajustes realizados após os testes.
- Avaliar uma futura integração com WhatsApp por meio de ferramentas
  apropriadas, com autorização da pizzaria.
Status do projeto
Documentação inicial publicada. O prompt está disponível para
leitura, teste e melhoria. A integração com canais ou sistemas de
atendimento não faz parte desta versão.
Autor
Dair José de Freitas Filho

Projeto desenvolvido como prática de engenharia de prompts e aplicação
de inteligência artificial generativa em um cenário de atendimento ao
cliente.
