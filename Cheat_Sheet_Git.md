# Cheat Sheet

**git init:** comando para inicializar um repositório git. PS: Só uma vez por projeto!!!

PS1: Ter certeza que estou iniciando na pasta onde vou desenvolver o meu projeto.

PS2: O git não enxerga pastas acima.

PS3: Nunca criar um git onde já existe.

**git add <name file>:** adiciona um arquivo no purgatório (stating area).

PS: para enviar tudo use o **git add ***

**git commit -m "mensagem significativa":** você se compromete com essa atualização que criei uma versão do meu repositório. PS: porque, como, efeitos, limitações.

PS: se esquecer do -m, é aberto o editor nativo do Git (VI editor), neste caso é necessário digitar primeiro "i" seguido de "ESC" para inserção, sendo possível escrever múltiplos parágrafos. Para sair: ESC seguido de :wq+ENTER

**giy status:** verifica as áreas conceituais e informa o status de cada arquivo nas áreas - untracked (desenvolvimento), not commit (purgatório)

**git log:** histórico de todos os commits (--help) (-n<nº>) (--abbrev-commit)

**git show <commit ID1> <commit ID2>:** compara os commits selecionados, igual ao git diff

**git diff <commit ID1> <commit ID2>:** compara os commits desejados.

**git remote add <pasta local> <ssh do repositório remoto> :** cria a ponte entre o repositório local e o repositório virtual (criado no GitHub>Meus repositórios)

**git push:** envia todos os arquivos do repositório para repositório remoto no GitHub 

**git pull:** importar arquivos do GitHub para repositório local.

<<<<<<< HEAD
**git branch <name>:** criar experimento/timeline paralela livre de risco.

PS: para ver todos os branches use o comando **git branch --list**

**git clone:** recuperar repositório do GitHub incluíndo em colaboração.

**git checkout <name>:** viajar entre timeline paralelas e a master.

**git checkout <id commit> :** viajar entre commits na mesma time line.

**git merge <name branch>:** mescla o branch com o master.

**git tag <name>:** cria uma etiqueta no commit de interesse.



## **Rotina básica de enriquecimento da timeline**

git branch: cria um local paralelo 

Git checkout: entrar nesse local paralelo
