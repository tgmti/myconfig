
# Configurações e dicas úteis

## Git
Dicas e comandos de Git

### Merge sem commit desnecessário:

    git merge branch --no-commit

### Submodules

[working-with-submodules](https://github.blog/2016-02-01-working-with-submodules/)

    # Update submodule
    git submodule update --init --recursive


--------------------------
## PowerShell
Dicas e comandos do PowerShell


### Tail log:

    cat .\console.log -Wait -Tail 50

### Log de hoje para área de transferência:

    git log --since='1am' | Set-Clipboard

--------------------------
## Robocopy
/E para copiarsubdiretórios:

    Robocopy.exe origem destino  /W:1 /R:1 /E

--------------------------
## VsCode
Dicas e comandos para o VsCode

### Remover duplicatas:

[Dica do Marc.2377](https://stackoverflow.com/questions/37992493/how-to-remove-duplicate-lines-in-visual-studio-code/45829605)

* Localizar com o RegEx: `^(.*)(\r?\n\1)+$`
* Substituir por `$1`

--------------------------
## Markdown

Links: `[palavra](meulink)`

--------------------------

## SQL

### Testar conexão com o banco via jdbc

[Squirrel-sql](http://squirrel-sql.sourceforge.net/)

--------------------------

## Gif

### LICEcap - Gravar Gif

### [] - Gif to Video converter

--------------------------
