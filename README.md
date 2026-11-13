# RA Agency Manager — PWA Android (MVP 0.2)

## Publicação pelo celular
1. Entre em https://github.com/ e crie uma conta ou faça login.
2. Crie um repositório novo chamado `ra-agency-manager`.
3. Marque-o como **Public** e crie o repositório.
4. No repositório, use **Add file > Upload files** e envie o conteúdo desta pasta (index.html, manifest.webmanifest, sw.js e a pasta icons).
5. Faça commit dos arquivos.
6. Abra **Settings > Pages**.
7. Em **Build and deployment**, escolha **Deploy from a branch**.
8. Selecione `main` e `/ (root)`, depois **Save**.
9. Aguarde a publicação. O endereço ficará parecido com `https://SEU-USUARIO.github.io/ra-agency-manager/`.
10. Abra o endereço no Chrome do Android, menu ⋮ > **Adicionar à tela inicial** ou **Instalar app**.

## O que funciona neste MVP
- Navegação entre Início, Clientes, Conteúdo, Agentes e Aprovações.
- Cadastro local de clientes.
- Cadastro e mudança de etapa de conteúdos.
- Aprovação manual simulada pelo diretor.
- Exportação de backup JSON.
- Cache offline básico via service worker.

## Limitações
- Dados ficam apenas no armazenamento local do navegador/dispositivo; não sincronizam entre aparelhos.
- Não há login, banco remoto, permissões multiusuário nem agentes de IA conectados.
- A aprovação é uma ação local de demonstração, não publicação em redes sociais.
- Este pacote é uma PWA, não um APK nativo.
- Não use dados sensíveis de clientes nesta versão de teste.

## Próximas etapas
Adicionar backend seguro, autenticação, sincronização, gestão completa de briefing, arquivos, histórico, relatórios e integrações com IA. Depois empacotar como Android quando a base estiver estável.
