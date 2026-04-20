# Crystal Laser - Automação de Atendimento com IA (WhatsApp)

Sistema de automação inteligente para atendimento, qualificação de leads e agendamento via WhatsApp, desenvolvido para clínicas de estética.

---

## Sobre o projeto

Este projeto foi desenvolvido para otimizar o processo de atendimento de uma clínica de depilação a laser, automatizando interações com clientes através de fluxos inteligentes e integração com IA.

---

## Tecnologias utilizadas

* Automação baseada em fluxo (JSON)
* Integração com API de WhatsApp
* Modelos de IA (OpenAI / Claude)
* Webhooks e integrações externas

---

## Funcionalidades

* 💬 Atendimento automatizado via WhatsApp
* 🧠 Respostas inteligentes com IA
* 📊 Qualificação de leads
* 📅 Direcionamento para agendamento
* 🔄 Fluxos personalizados

---

## Estrutura do projeto

O repositório é composto por um fluxo principal de automação responsável por gerenciar todo o atendimento via WhatsApp.

.
└── Crystal Laser - Fluxo Principal WhatsApp.json
📌 Descrição dos arquivos
Crystal Laser - Fluxo Principal WhatsApp.json
Arquivo principal contendo toda a lógica da automação, incluindo:
Fluxo de atendimento ao cliente
Integração com API de WhatsApp
Processamento de mensagens com IA
Regras de decisão e ramificações
Qualificação de leads
Direcionamento para agendamento
🔄 Organização lógica do fluxo

Dentro do arquivo JSON, o fluxo é estruturado em etapas como:

Entrada (Trigger)
Recebimento de mensagens via WhatsApp
Processamento
Interpretação da mensagem utilizando IA
Decisão
Identificação da intenção do usuário (ex: dúvidas, agendamento, orçamento)
Resposta
Retorno automatizado ao cliente
Ação
Encaminhamento para agendamento, humano ou CRM
⚠️ Observação

Por se tratar de um projeto baseado em automação por fluxo, não há separação tradicional em pastas de código (como controllers, services, etc.).
Toda a lógica está centralizada no arquivo JSON, sendo executada dentro da ferramenta de automação escolhida (ex: n8n, Make).

## Como usar

1. Importar o arquivo `.json` na ferramenta de automação (n8n, Make, etc.)
2. Configurar APIs (WhatsApp + IA)
3. Ajustar variáveis do negócio
4. Ativar o fluxo

---

## Configurações necessárias

* API Key de IA
* Provedor de WhatsApp
* Webhooks

---

## Benefícios

* Redução de atendimento manual
* Aumento de conversão
* Escalabilidade

---

## Observações

* Dependente de APIs externas
* Custos variáveis conforme uso

---

## Empresa

Desenvolvido por **I.Ara™** – Soluções em automação e inteligência artificial para negócios.

---

## Responsável Técnico

[Lorenzo Amorim](https://github.com/LorenzoAmorim)
CTO & Desenvolvedor responsável pela arquitetura e implementação do sistema.

---

## Licença

Uso comercial sob autorização.

---
