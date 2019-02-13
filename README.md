
# Configurações e dicas úteis

## Git
Dicas e comandos de Git

### Merge sem commit desnecessário:

    git merge branch --no-commit

--------------------------
## PowerShell
Dicas e comandos do PowerShell


### Tail log:

    cat .\console.log -Wait -Tail 50

### Log de hoje para área de transferência:

    git log --since='1am' | Set-Clipboard


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
