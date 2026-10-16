# Pinheiro's Cobbleverse

Distribuição do modpack e dos launchers para Windows x64 e Linux x64.

## Baixar o launcher

- [Windows 10/11 x64](https://github.com/lcomhpinheiro/pinheiro-s-cobbleverse/releases/download/modpack-1.0.1/CobbleverseLauncher-Windows-x64.zip)
- [Linux x64](https://github.com/lcomhpinheiro/pinheiro-s-cobbleverse/releases/download/modpack-1.0.1/CobbleverseLauncher-Linux-x64.tar.gz)
- [Versões e novidades](https://github.com/lcomhpinheiro/pinheiro-s-cobbleverse/releases)

Extraia a pasta inteira e abra `CobbleverseLauncher.exe` no Windows ou `./CobbleverseLauncher` no Linux. Clique **Canal oficial**, escolha a memória disponível e use **Instalar / atualizar**. O launcher instala Minecraft 1.21.1, Fabric 0.19.5, Java e o modpack. A primeira instalação precisa de internet.

O perfil local atende mundos locais e servidores que aceitam contas offline. O login Microsoft exige aplicativo Microsoft autorizado; ainda não há Client ID de produção configurado nesta versão. Serviços do Essential que dependem da conta oficial ficam desativados no perfil local.

## Atualizações

O canal estável é:

```text
https://github.com/lcomhpinheiro/pinheiro-s-cobbleverse/releases/latest/download/manifest.json
```

Os arquivos `f-*` e `b-*` dos Releases são baixados automaticamente pelo launcher. Não precisam ser baixados à mão. Os hashes SHA-256 são verificados antes da instalação.

O inventário do modpack é completo em cada versão, mas arquivos e pacotes inalterados continuam sendo reutilizados das versões anteriores. Uma versão que muda só configurações não exige baixar novamente os mods. Configurações personalizadas são preservadas quando a política é `merge`; `replace` substitui o arquivo inteiro; `seed` só instala quando o arquivo não existe. Saves não fazem parte da atualização.

## Validação e ajuda

Linux: execução até o menu principal. Windows: interface e instalação testadas sob Wine; a execução do jogo em Windows nativo ainda aguarda teste externo. Consulte [TESTE-WINDOWS.md](TESTE-WINDOWS.md).

Se houver falha, o botão **Abrir pasta** mostra a instalação. Os logs ficam em `logs/launcher-game.log` e `logs/latest.log`. Não envie arquivos de contas nem saves ao relatar problemas.

Este repositório contém a distribuição pública. Credenciais de publicação e código de desenvolvimento não fazem parte dos arquivos enviados aos jogadores.
