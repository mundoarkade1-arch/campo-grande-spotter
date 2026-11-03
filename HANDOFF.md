# Retomada do projeto — Janela

Última atualização: 2026-11-03

## Objetivo

Criar um app simples e bonito para observar voos chegando e saindo do Aeroporto Internacional de Campo Grande (CGR), encontrar o melhor período para observar muitos pousos/decolagens, receber alertas e publicar pelo GitHub.

## Onde está o trabalho

Pasta do projeto: `work/campo-grande-spotter/`

- `index.html`: estrutura e interface em português.
- `styles.css`: identidade visual responsiva.
- `app.js`: filtros, relógio local, notificações básicas e botão para consultar atualização no GitHub.
- `.github/workflows/pages.yml`: publicação automática no GitHub Pages após push para `main`.
- `README.md`: instruções iniciais e limitações.

## Estado e decisões

- Protótipo estático, sem dependências de build.
- Os voos atuais são dados de demonstração inventados; não apresentam estado real do aeroporto.
- Melhor janela estática, só ilustrativa. O cálculo real deve agrupar movimentos reais por intervalos e explicar o período recomendado.
- Notificação do navegador é demonstrativa e requer página aberta; alertas em segundo plano precisam de backend/push.
- O botão “verificar atualização” está configurado para consultar `mundoarkade1-arch/campo-grande-spotter`.
- A pasta local foi inicializada como repositório Git na branch `main` e o remoto `origin` aponta para `https://github.com/mundoarkade1-arch/campo-grande-spotter.git`.
- O protótipo foi enviado ao GitHub em seis commits pela integração. O workflow já executou uma vez, mas falhou porque o GitHub Pages não estava habilitado. Foi incluída a opção `enablement: true` para habilitá-lo no novo deploy.
- O workflow será iniciado de novo ao atualizar sua configuração. Confirmar se concluiu e registrar o URL de Pages publicado.
- Nenhum teste foi executado.

## Próximos passos

1. Confirmar que o workflow habilitou Pages e publicar em `https://mundoarkade1-arch.github.io/campo-grande-spotter/`.
2. Depois, escolher fonte legítima e adequada de dados CGR: validar cobertura, atraso, termos, limites e custo antes de integrar.
3. Trocar dados de demonstração por dados reais, estimativa da melhor janela e mecanismo de alerta apropriado.

## Como continuar amanhã

Leia `HANDOFF.md`, depois `README.md`, examine os arquivos deste diretório e retome no primeiro próximo passo ainda não concluído. Não assuma que os horários de demonstração são reais.
