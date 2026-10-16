# Validação da distribuição

Release: [modpack-1.0.1](https://github.com/lcomhpinheiro/pinheiro-s-cobbleverse/releases/tag/modpack-1.0.1). Launcher: 1.1.0.

- 231 assets enviados ao Release, com tamanho e SHA-256 conferidos contra os valores registrados pelo GitHub antes da publicação.
- Links dos launchers Windows e Linux responderam HTTP 200 sem autenticação.
- Instalação limpa completa por HTTPS no Linux: os 1.926 arquivos do modpack foram baixados e verificados pelo atualizador, sem credenciais GitHub. Cinco pacotes ZIP transportam os arquivos pequenos; os demais assets são baixados diretamente.
- No Python de Windows sob Wine: manifesto HTTPS, um pacote ZIP e um mod direto baixados e verificados sem autenticação.
- 30 testes passaram no Linux e no Python de Windows sob Wine. Incluem atualização somente de configurações sem baixar novamente mods, hashes, preservação de configurações pessoais, reversão de falhas, proteção de caminhos, PKCE e encerramento do aplicativo.
- Execução real do modpack no Linux até o menu principal em uma tela virtual isolada, seguida de fechamento normal.

## Ainda não comprovado ou configurado

- Execução do jogo em Windows nativo. O teste externo segue o [roteiro Windows](TESTE-WINDOWS.md); Wine não substitui essa confirmação.
- Login Microsoft com aplicativo de produção. O responsável ainda precisa registrar e obter autorização para um Client ID. O perfil local está disponível nesta versão.

O arquivo `SHA256SUMS.txt` do Release permite conferir os downloads. Saves e credenciais pessoais não fazem parte do pacote de atualização. O ZIP separado de fontes do administrador não foi publicado no Release.
