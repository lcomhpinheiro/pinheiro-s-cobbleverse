# Teste do Cobbleverse Launcher no Windows

Baixe e execute `CobbleverseSetup-Windows-x64.exe`, disponível no release launcher-1.7.0. Não é preciso extrair arquivos ou manter pastas ao lado do instalador. O canal HTTPS oficial já vem configurado.

Teste em Windows 10/11 x64 real, com drivers compatíveis com Minecraft 1.21.1. Não é preciso instalar Python ou Java manualmente. O perfil local não exige senha Microsoft.

## Roteiro

1. Avance usando Começar e Próximo passo. Confirme que a lista lateral não permite mudar de etapa e que não há menu de configurações no instalador.
2. Escolha perfil local e uma pasta separada de instalações existentes. Clique Instalar agora e aguarde a preparação automática do modpack e do launcher, com progresso de 0% a 100%.
3. Durante a instalação, confirme que Voltar/Próximo estão bloqueados. Ao terminar, a tela Concluído aparece automaticamente; clique Abrir launcher.
4. A nova tela deve mostrar o seletor de perfis, Novo perfil, Excluir, Play, imagens e uma engrenagem no canto superior esquerdo. Na engrenagem, ajuste a memória na barra em MB (marcações de 2, 4, 8, 16 e 32 GB) e confirme a abertura da pasta do jogo. Deixe o Java em automático.
5. Clique Jogar e aguarde o menu principal do Cobbleverse. Feche o jogo normalmente e confirme que o launcher continua utilizável.
6. Feche o launcher, abra o atalho Jogar Cobbleverse na pasta do jogo ou na área de trabalho. Confirme que o launcher abre com o nome e a memória salvos.
7. Na engrenagem, desmarque verificar atualizações e confirme uma segunda abertura do jogo usando os arquivos existentes.

O teste de gameplay em Windows nativo ainda precisa ser realizado. O login Microsoft permanece desativado.

Crie um segundo perfil e alterne entre eles. Exclua um perfil de teste e confirme que é necessário escolher ou criar outro antes de jogar. Feche e reabra o launcher para conferir a persistência da seleção e da memória.

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
