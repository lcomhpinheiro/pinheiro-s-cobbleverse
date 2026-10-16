# Pinheiro’s Cobbleverse

Instalador e launcher do modpack para Windows x64 e Linux x64.

## Baixar o instalador 1.4.0

- [Windows 10/11 x64](https://github.com/lcomhpinheiro/pinheiro-s-cobbleverse/releases/download/launcher-1.4.0/CobbleverseInstaller-Windows-x64.zip)
- [Linux x64](https://github.com/lcomhpinheiro/pinheiro-s-cobbleverse/releases/download/launcher-1.4.0/CobbleverseInstaller-Linux-x64.tar.gz)
- [Todas as versões](https://github.com/lcomhpinheiro/pinheiro-s-cobbleverse/releases)

Extraia o pacote inteiro. No Windows, abra **CobbleverseInstaller.exe**; no Linux, execute **Instalar Cobbleverse**. Avance pelos botões Começar/Próximo, escolha o perfil e a pasta e instale. A lista lateral apenas indica o andamento. A primeira instalação precisa de internet; Python e Java não precisam ser instalados manualmente.

Ao concluir, clique **Abrir launcher**. O programa fica em **Cobbleverse Launcher**, dentro da pasta escolhida, com um atalho **Jogar Cobbleverse**. Nas próximas vezes, abra esse atalho: a tela diária contém nome, Play e imagens. A engrenagem no canto superior esquerdo abre memória alocada, Java automático/personalizado, pasta do jogo e opções de conta e atualização.

Preferências ficam em `.cobbleverse-settings`, na pasta do jogo. A reinstalação preserva essas preferências e os mundos. Depois de instalar, a pasta extraída do instalador pode ser removida. Para testar somente a interface, digite **↑ ↑ ↓ ↓ ← → ← → B A Enter**, avance normalmente e clique **Testar launcher**; a faixa MODO VISUAL identifica a simulação.

O perfil local atende mundos locais e servidores que aceitam contas offline. O modpack 1.0.2 não contém o Essential. O login Microsoft real ainda depende do registro e da aprovação do aplicativo pelo responsável.

## Atualizações do modpack

O endereço estável já vem configurado:

```text
https://github.com/lcomhpinheiro/pinheiro-s-cobbleverse/releases/latest/download/manifest.json
```

Cada Release mais recente precisa incluir `manifest.json`. Os arquivos `f-*` e `b-*` são baixados e verificados automaticamente; não precisam ser baixados à mão. Arquivos inalterados podem ser reutilizados de versões anteriores. Por isso, mantenha os Releases antigos cujos arquivos ainda são referenciados.

Os instaladores 1.4.0 recebem o modpack mais recente pelo canal acima. O modpack 1.0.2 remove o Essential e seus botões dos menus; não é necessário baixar outro instalador. Uma atualização somente de configurações não exige baixar os mods novamente. A política `merge` preserva alterações pessoais; `replace` substitui o arquivo inteiro; `seed` instala apenas se ele não existe. Saves não fazem parte da atualização.

Uma atualização do modpack não substitui o programa launcher. Os links dos instaladores acima apontam para a versão específica e continuam válidos quando um novo modpack for publicado.

## Validação e ajuda

**54 testes passaram no Linux e no Python de Windows via Wine.** Os dois pacotes compilados foram testados também copiando o runtime e o aplicativo para uma pasta nova e abrindo o launcher instalado. O modpack já foi executado até o menu principal no Linux. O teste de gameplay em Windows nativo ainda depende de validação externa. Veja [VALIDACAO.md](VALIDACAO.md) e [TESTE-WINDOWS.md](TESTE-WINDOWS.md).

Se houver falha, abra a engrenagem e use **Abrir pasta do jogo**. Os logs ficam em `logs/launcher-game.log` e `logs/latest.log`. Não compartilhe credenciais nem saves. A distribuição contém os programas compilados; a cópia privada de fontes do administrador não é publicada aqui.
