# Validação da distribuição 1.4.0

- 54 testes passaram no Linux e no Python de Windows via Wine: atualização, integridade, preservação de arquivos, autenticação simulada com PKCE, instalador por etapas, controles da janela, launcher diário e memória/Java personalizados.
- Nos dois pacotes compilados, o modo visual percorreu as etapas e abriu a prévia do launcher sem downloads, autenticação ou jogo.
- Os dois pacotes copiaram seu runtime e aplicativo para uma pasta nova e abriram a cópia instalada pelo executável correspondente. A configuração instalada seleciona o launcher diário, não o assistente.
- Reinstalação, cancelamento e reversão de falha de gravação foram testados em pastas temporárias. Mundos e preferências anteriores foram preservados.
- O modpack continua na versão 1.0.1. Seu manifesto é reutilizado sem alterar os URLs imutáveis dos 1.926 arquivos. A instalação completa desses arquivos por HTTPS sem autenticação já passou na distribuição inicial; os mesmos assets continuam hospedados em `modpack-1.0.1`.
- O jogo chegou ao menu principal no Linux em validação anterior. O teste externo de gameplay em Windows nativo e o login Microsoft com aplicativo de produção continuam pendentes. Wine e respostas simuladas de autenticação não substituem esses testes.

Os instaladores contêm imagens e Python. Java, Minecraft, Fabric e o modpack são instalados na etapa de preparação. Os hashes dos arquivos públicos deste Release estão em `SHA256SUMS.txt`. O arquivo privado de fontes não faz parte dos assets publicados.

## Atualização do modpack 1.0.2

Essential e os botões correspondentes foram removidos. O atualizador foi executado sobre uma cópia dos 1.926 arquivos anteriores: removeu o mod, aplicou os dois menus novos, verificou os 1.925 hashes restantes e preservou um save. Apenas um pacote de configurações foi baixado; nenhum mod inalterado precisou ser transferido novamente. Os assets anteriores continuam necessários para os arquivos reutilizados.
