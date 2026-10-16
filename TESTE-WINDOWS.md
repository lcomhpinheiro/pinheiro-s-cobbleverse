# Teste do Cobbleverse Launcher no Windows

Para testar a instalação online, envie ao testador somente o launcher de Windows e use **Canal oficial**. Para testar a instalação por pacote local, envie os dois arquivos abaixo da pasta `dist`:

- `CobbleverseLauncher-Windows-x64.zip` — launcher portátil, com Python incluído.
- `Cobbleverse-Modpack-1.0.1.zip` — modpack.

O teste deve ser feito no **Windows 10 ou 11 x64 real**, com driver gráfico compatível com Minecraft 1.21.1. Separe aproximadamente 6 GB de RAM para o jogo e espaço para extrair os arquivos e instalar Minecraft, Java e os assets. A primeira instalação baixa arquivos da internet. Não precisa instalar Python nem Java manualmente. Este teste usa perfil local; não precisa informar senha Microsoft.

## Roteiro

1. Extraia os dois ZIPs para pastas normais. Não abra o launcher diretamente de dentro do ZIP.
2. Abra `CobbleverseLauncher.exe`, mantendo as pastas `runtime` e `app` ao lado do executável.
3. Para testar o Release publicado, clique **Canal oficial** e use o endereço preenchido pelo launcher. Para teste com os ZIPs locais, clique **Selecionar pacote local…** e escolha o `manifest.json` dentro de `Cobbleverse-Modpack-1.0.1`. A pasta `files` precisa continuar ao lado desse manifesto.
4. Mantenha **Usar perfil local** marcado e escolha um nome com 3 a 16 letras, números ou `_`. Use 6 GB de memória se houver RAM disponível.
5. Use a pasta de jogo padrão do launcher, separada de instalações existentes. Clique **Instalar / atualizar** e aguarde terminar. A primeira instalação pode demorar.
6. Clique **JOGAR** e espere o menu principal do Cobbleverse. Registre se o jogo abriu ou qual erro apareceu. O teste passa nesta etapa quando o menu do modpack está utilizável.
7. Feche o jogo normalmente. Confirme que o launcher voltou a permitir clicar em **JOGAR**, sem erro ao encerrar.
8. Desmarque **Verificar atualizações antes de jogar**, clique **JOGAR** novamente e confirme que o jogo volta ao menu usando a instalação existente. Feche o jogo e o launcher normalmente.

Não teste o botão de login Microsoft nesta rodada: o aplicativo Microsoft de produção ainda não foi registrado. Não altere a pasta de um Minecraft ou Modrinth já instalado.

## Resposta para devolver

Copie e preencha:

```text
Windows e versão (10/11):
Memória RAM total:
Placa de vídeo:
O launcher abriu? sim/não
Instalar / atualizar terminou? sim/não
O jogo chegou ao menu do Cobbleverse? sim/não
O jogo fechou sem erro no launcher? sim/não
A segunda abertura sem verificar atualizações funcionou? sim/não
Erro observado, se houver:
```

Se falhar, anexe o texto exato do erro e, se possível, uma captura da janela. O botão **Abrir pasta** leva à instalação do jogo; os arquivos úteis são `logs/launcher-game.log`, `logs/latest.log` e o relatório mais recente em `crash-reports`, quando existirem. Confira o conteúdo antes de compartilhar: logs do jogo podem conter nomes de jogador, caminhos locais e endereços de servidores. Não é necessário enviar saves nem arquivos de contas.

O resultado precisa vir desse teste real; os testes com Wine já executados não o substituem.
