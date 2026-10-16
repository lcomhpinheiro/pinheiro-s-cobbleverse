# Teste do Cobbleverse Launcher no Windows

Envie `dist/CobbleverseLauncher-Windows-x64.zip` ao testador. Extraia o pacote inteiro e abra `CobbleverseInstaller.exe`, mantendo `runtime` e `app` ao lado dele. O canal HTTPS oficial já vem configurado.

Teste em Windows 10/11 x64 real, com drivers compatíveis com Minecraft 1.21.1. Não é preciso instalar Python ou Java manualmente. O perfil local não exige senha Microsoft.

## Roteiro

1. Avance usando Começar e Próximo passo. Confirme que a lista lateral não permite mudar de etapa e que não há menu de configurações no instalador.
2. Escolha perfil local e uma pasta separada de instalações existentes. Na etapa Preparação, instale o modpack e o launcher.
3. Durante a instalação, confirme que Voltar/Próximo estão bloqueados. Ao terminar, clique Concluir instalação e Abrir launcher.
4. A nova tela deve mostrar nome, Play, imagens e uma engrenagem no canto superior esquerdo. Na engrenagem, ajuste a memória e confirme a abertura da pasta do jogo. Deixe o Java em automático.
5. Clique Jogar e aguarde o menu principal do Cobbleverse. Feche o jogo normalmente e confirme que o launcher continua utilizável.
6. Feche o launcher, apague somente a pasta extraída do instalador e abra o atalho Jogar Cobbleverse na pasta do jogo ou na área de trabalho. Confirme que o launcher abre com o nome e a memória salvos.
7. Na engrenagem, desmarque verificar atualizações e confirme uma segunda abertura do jogo usando os arquivos existentes.

O teste de gameplay em Windows nativo ainda precisa ser realizado. O login Microsoft com conta real depende do registro/aprovação do aplicativo.

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

Se falhar, anexe o texto exato do erro e, se possível, uma captura da janela. O botão **Abrir pasta do jogo** leva à instalação do jogo; os arquivos úteis são `logs/launcher-game.log`, `logs/latest.log` e o relatório mais recente em `crash-reports`, quando existirem. Confira o conteúdo antes de compartilhar: logs do jogo podem conter nomes de jogador, caminhos locais e endereços de servidores. Não é necessário enviar saves nem arquivos de contas.

O resultado precisa vir desse teste real; os testes com Wine já executados não o substituem.

## Testar somente a interface

Digite **↑ ↑ ↓ ↓ ← → ← → B A Enter** no instalador. Avance normalmente e, na última etapa, clique **Testar launcher**. O launcher diário e a engrenagem podem ser testados sem downloads, instalação de programas ou abertura do Minecraft. **Voltar ao instalador** encerra a prévia. Esse teste não substitui a validação de instalação e gameplay real acima.
