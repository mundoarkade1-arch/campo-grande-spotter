# Janela — Aeroporto de Campo Grande

App web progressivo e responsivo para observar chegadas e partidas no Aeroporto Internacional de Campo Grande (CGR).

## Estado atual

- Protótipo visual funcional com filtros de chegadas e partidas, relógio local, sugestão de janela movimentada e pedido de notificações.
- **Dados exibidos são fictícios e servem somente para demonstração.** Não use para planejar viagem nem para assumir que um voo está operando.
- A origem de dados de voos reais ainda precisa ser escolhida. Uma fonte pode exigir cadastro, chave e limites de uso. A chave nunca deve ser publicada no código do navegador; para dados protegidos, será necessário um pequeno serviço intermediário.
- O botão de atualização está preparado para consultar a API pública do GitHub após configurar `github-repo` no HTML.
- A notificação no protótipo é local; notificações confiáveis em segundo plano pedem um serviço de push.

## Publicar no GitHub Pages

1. Crie um repositório público chamado `campo-grande-spotter` na sua conta GitHub. Não inicialize com README, licença ou `.gitignore`.
2. No GitHub, abra **Settings → Pages → Build and deployment** e selecione **GitHub Actions**.
3. Suba o conteúdo desta pasta para o repositório. O workflow `.github/workflows/pages.yml` publica o app automaticamente em cada push para `main`.
4. O verificador de versão já está configurado para `mundoarkade1-arch/campo-grande-spotter`.

## Retomar o trabalho

Leia este README e `HANDOFF.md` no início da próxima sessão. O trabalho está em `work/campo-grande-spotter`; a publicação só começa depois de conectar a conta GitHub e autorizar o envio.
