# Janela — Aeroporto de Campo Grande

App web progressivo e responsivo para observar chegadas e partidas no Aeroporto Internacional de Campo Grande (CGR).

## Estado atual

- Protótipo visual funcional com filtros de chegadas e partidas, relógio local, sugestão de janela movimentada e pedido de notificações.
- **Dados exibidos são fictícios e servem somente para demonstração.** Não use para planejar viagem nem para assumir que um voo está operando.
- A origem de dados de voos reais ainda precisa ser escolhida. Uma fonte pode exigir cadastro, chave e limites de uso. A chave nunca deve ser publicada no código do navegador; para dados protegidos, será necessário um pequeno serviço intermediário.
- O botão de atualização está preparado para consultar a API pública do GitHub após configurar `github-repo` no HTML.
- A notificação no protótipo é local; notificações confiáveis em segundo plano pedem um serviço de push.

## Publicação

O repositório configurado é `mundoarkade1-arch/campo-grande-spotter`. Antes do primeiro deploy, abra **Settings → Pages → Build and deployment** no GitHub e selecione **GitHub Actions** como fonte. Depois disso, o workflow `.github/workflows/pages.yml` publica o app automaticamente em cada push para `main`. Acompanhe **Actions** no GitHub.

O botão de verificação consulta a API pública do GitHub e compara o commit mais recente com a versão publicada. Ele está configurado para este repositório.

## Retomar o trabalho

Leia este README e `HANDOFF.md` no início da próxima sessão. O trabalho está em `work/campo-grande-spotter`.
