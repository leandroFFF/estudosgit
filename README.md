# Como utilizar o Git e GitHub?
- Repositório destinado a estudos sobre o GIT e GITHUB

## O que é Git?
- O Git é um sistema de controle de versão que permite rastrear as alterações feitas em seus arquivos ao longo do tempo.

## O que é GitHub?
- O GitHub é um servidor na nuvem.

## Como instalar o Git?
- Para usar o Git, você precisa instalá-lo em seu computador.
> Link: [Link para baixar o Git](https://git-scm.com/)

## Como criar uma conta no GitHub?
> Link: [Link para criar/acessar uma conta do GitHub](https://github.com/signup)




===================================================================================================================================

### uso: 
- git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

### Estes são comandos Git comuns usados ​​em diversas situações:

#### iniciar uma área de trabalho (veja também: tutorial de ajuda do git)
   - clone     - Clonar um repositório em um novo diretório
   - init      - Crie um repositório Git vazio ou reinicialize um existente

### trabalhar na mudança atual (veja também: git help todos os dias)
   - add       - Adiciona o conteúdo do arquivo ao índice
   - mv        - Mover ou renomear um arquivo, diretório ou link simbólico
   - restore   - Restaurar arquivos da árvore de trabalho
   - rm        - Remove arquivos da árvore de trabalho e do índice

### examine o histórico e o estado (veja também: revisões de ajuda do git)
   - bisect    - Use pesquisa binária para encontrar o commit que introduziu um bug
   - diff      - Mostra alterações entre commits, commit e árvore de trabalho, etc.
   - grep      - Imprime linhas que correspondem a um padrão
   - log       - Mostrar registros de commit
   - show      - Mostrar vários tipos de objetos
   - status    - Mostra o status da árvore de trabalho

### crescer, marcar e ajustar sua história comum
   - branch    - Listar, criar ou excluir filiais
   - commit    - Registrar alterações no repositório
   - merge     - Unir dois ou mais históricos de desenvolvimento
   - rebase    - Reapply confirma em cima de outra dica base
   - reset     - Redefinir o HEAD atual para o estado especificado
   - switch    - Mudar ramos
   - tag       - Criar, listar, excluir ou verificar um objeto de tag assinado com GPG

### colaborar (veja também: fluxos de trabalho de ajuda do git)
   - fetch     - baixar objetos e referências de outro repositório
   - pull      - busque e integre-o a outro repositório ou branch local
   - push      - Atualizar referências remotas junto com objetos associados

- 'git help -a' e 'git help -g' listam os subcomandos disponíveis e alguns
guias conceituais. Consulte 'git help <comando>' ou 'git help <conceito>'
para ler sobre um subcomando ou conceito específico.
Consulte 'git help git' para uma visão geral do sistema.

===================================================================================================================================

git
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           [--super-prefix=<path>] [--config-env=<name>=<envvar>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone     Clone a repository into a new directory
   init      Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add       Add file contents to the index
   mv        Move or rename a file, a directory, or a symlink
   restore   Restore working tree files
   rm        Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect    Use binary search to find the commit that introduced a bug
   diff      Show changes between commits, commit and working tree, etc
   grep      Print lines matching a pattern
   log       Show commit logs
   show      Show various types of objects
   status    Show the working tree status

grow, mark and tweak your common history
   branch    List, create, or delete branches
   commit    Record changes to the repository
   merge     Join two or more development histories together
   rebase    Reapply commits on top of another base tip
   reset     Reset current HEAD to the specified state
   switch    Switch branches
   tag       Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch     Download objects and refs from another repository
   pull      Fetch from and integrate with another repository or a local branch
   push      Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.
