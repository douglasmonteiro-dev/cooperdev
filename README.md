# cooperdev

## Referência rápida para agentes
- **CooperDev fornece ferramentas e templates de desenvolvimento** para o ecossistema.
- Priorizar padrões reutilizáveis: scripts de bootstrap, templates OpenAPI, CI patterns e SDKs para Raiz Platform.
- Novas ferramentas devem acelerar integração com Raiz Platform, não duplicar funcionalidades de produtos.
- Manter compatibilidade com Python, Node.js e Docker.

GitHub Pages
    A[Usuário precisa de uma página] -->|Cooperdev| B(Página do Usuário)
    B --> C{Produto ou Serviço}
    C -->|Agendamento| D[Serviço]
    C -->|Vendas| E[Produto]

## Estratégia de evolução
CooperDev fornece ferramentas e templates para acelerar o desenvolvimento do ecossistema, incluindo scaffolds, scripts e SDKs compartilhados.

### Roadmap priorizado
- Quick Wins (30 dias): templates de bootstrap e SDKs base para Auth e Events.
- Curto prazo (90 dias): templates de projetos e CI padrão.
- Médio prazo (6 meses): catálogo de ferramentas e integração com Raiz Platform.

### Dependências principais
- Raiz Platform: serviços compartilhados.
- OpenClaw: padrões de automação e agentes.