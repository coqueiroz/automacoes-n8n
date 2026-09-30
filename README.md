# Automações com n8n

Olá! Sou **Lucas Coqueiro**, estudante de Ciência da Computação com foco em automação de processos, Python e integrações entre sistemas.

Este repositório reúne fluxos que construí no [n8n](https://n8n.io) combinando agentes de IA com ferramentas do Google Workspace. As empresas citadas são **casos fictícios criados para estudo**.

## Projetos

| Projeto | O que faz | Tecnologias | Pasta |
|---|---|---|---|
| Agente de e-mail para imobiliária (Nova Lar Imóveis) | Responde e-mails de clientes, consulta imóveis em uma planilha e registra ou atualiza leads em uma planilha de CRM | n8n, Gmail, Google Gemini, Google Sheets, memória por thread | [agente-email-imobiliaria](agente-email-imobiliaria/) |
| Agente de e-mail para escola online (EduVerso+) | Responde e-mails de interessados nos cursos com informações oficiais, trata objeções e envia o link de inscrição | n8n, Gmail, Google Gemini, memória por thread | [agente-email-escola-online](agente-email-escola-online/) |
| Alerta de estoque crítico | Todo dia às 9h lê uma planilha de estoque, identifica os itens no mínimo ou abaixo dele e envia um relatório em HTML por e-mail | n8n, Google Sheets, Gmail, JavaScript (nó Code) | [alerta-estoque-critico](alerta-estoque-critico/) |

Cada pasta tem um `workflow.json` pronto para importar no n8n (sem credenciais e com os links de planilhas substituídos por `SEU_ID_AQUI`) e um README com o passo a passo, os destaques técnicos e as limitações conhecidas.
