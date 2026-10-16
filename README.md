# Pinheiro’s Cobbleverse

Instalador e launcher do modpack para Windows x64 e Linux x64.

## Baixar o instalador 1.7.0

- [Windows 10/11 x64 — instalador EXE único](https://github.com/lcomhpinheiro/pinheiro-s-cobbleverse/releases/download/launcher-1.7.0/CobbleverseSetup-Windows-x64.exe)
- [Linux x64](https://github.com/lcomhpinheiro/pinheiro-s-cobbleverse/releases/download/launcher-1.7.0/CobbleverseInstaller-Linux-x64.tar.gz)
- [Todas as versões](https://github.com/lcomhpinheiro/pinheiro-s-cobbleverse/releases)

No Windows, execute o EXE diretamente, sem extrair ZIP ou usar BAT/CMD. No Linux, extraia o pacote e execute **Instalar Cobbleverse**. Escolha seu nome e a pasta e clique **Instalar agora**: a preparação começa automaticamente, mostra progresso de 0% a 100% e avança ao concluir. A primeira instalação precisa de internet. Python e Java são fornecidos pelo instalador.

Ao concluir, clique **Abrir launcher**. Nas próximas vezes, abra **Jogar Cobbleverse**, na pasta escolhida, ou o atalho na área de trabalho. O launcher e o instalador usam o visual azul com fundo `#1a1b26`, imagens e ícone do Cobblemon.

## Perfis e configurações

O nome fica salvo como perfil e não pode ser editado acidentalmente. Use **Novo perfil** para criar outro e a lista **Perfil ativo** para trocar. O nome anteriormente salvo é importado com a mesma grafia. Cada nome pode ter seu próprio inventário e progresso em servidores.

**Excluir** pede confirmação e remove somente o perfil salvo: mundos e arquivos do jogo são preservados. Depois de excluir o perfil ativo, selecione ou crie outro antes de jogar. Para voltar à identidade anterior, crie novamente exatamente o mesmo nome. Perfis não podem ser criados, trocados ou excluídos durante uma operação.

A engrenagem no canto superior esquerdo abre configurações de Java e memória. A barra deslizante mostra MB, com marcações em 2048, 4096, 8192, 16384 e 32768 MB (2, 4, 8, 16 e 32 GB). Também há Java automático/personalizado, abertura da pasta do jogo e verificação de atualizações. O login Microsoft permanece desativado; o perfil local atende mundos locais e servidores que aceitam contas offline.

O programa instalado fica em **Cobbleverse Launcher**; preferências ficam em `.cobbleverse-settings`. Reinstalar na mesma pasta preserva preferências e mundos. A atualização do modpack não substitui o programa launcher: para receber esta interface, execute o novo instalador.

## Atualizações do modpack

O canal oficial continua configurado:

```text
https://github.com/lcomhpinheiro/pinheiro-s-cobbleverse/releases/latest/download/manifest.json
```

O modpack atual é o **1.0.3**, sem Essential e sem os cinco mods marcados como desativados. O instalador busca a versão atual pelo canal oficial. Não apague os releases antigos: arquivos inalterados podem ser reutilizados pelas atualizações. Saves não fazem parte do pacote; configurações pessoais alteradas são preservadas pela política `merge`.

Os links de instaladores acima são fixos e continuam funcionando quando outro modpack for publicado. O release do launcher não muda o canal de atualizações do modpack.

## Validação e ajuda

**63 testes passaram no Linux e 63 no Python de Windows via Wine.** Os pacotes foram testados copiando runtime e aplicativo para uma pasta nova e abrindo o launcher instalado. O EXE único também passou pelo teste de abertura via Wine, sem baixar o jogo. O teste de gameplay no Windows nativo continua pendente. Veja [VALIDACAO.md](VALIDACAO.md) e [TESTE-WINDOWS.md](TESTE-WINDOWS.md).

Para testar somente a interface, digite **↑ ↑ ↓ ↓ ← → ← → B A Enter**. A faixa MODO VISUAL confirma a simulação e as alterações de teste não são gravadas.

Os logs do jogo ficam em `logs/launcher-game.log` e `logs/latest.log`. Abra a pasta pela engrenagem. Não compartilhe credenciais ou saves.
