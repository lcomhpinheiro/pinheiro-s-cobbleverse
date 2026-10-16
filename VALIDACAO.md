# Validação do launcher 1.7.0

- 63 testes passaram no Linux e 63 via Wine com Python de Windows.
- Instalador, simulação visual, cópia do runtime e abertura do launcher instalado passaram nas duas plataformas.
- Instalador Windows único e atalho EXE passaram no teste de abertura via Wine.
- Memória em MB: migração de preferências em GB, marcações da barra, persistência e argumento Java exato verificados.
- Perfis: persistência, migração da identidade anterior, criação, troca, exclusão confirmada, preservação dos arquivos do jogo, falha de gravação e bloqueio durante operações verificados.
- Pacotes compilados correspondem aos fontes locais da versão 1.7.0; checksums acompanham os downloads.

Gameplay em Windows nativo ainda precisa ser validado em um PC Windows 10/11. A validação via Wine não substitui esse teste. O login Microsoft permanece desativado.
