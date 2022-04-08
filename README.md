# Estudando os principais conceitos sobre Git e GitHub

## Alguns comandos importantes e como funciona

### - git init
Inicializa o repósitorio vazio dentro do arquivo desejado;
### - git status
Verifica qual estado as alterações está, se o arquivo foi *alterado, deletado ou se não está rastreado*
### git add . ou nome do arquivo desejado
É possível enviar todos os arquivos modificados para a área de "stage" ou apenas o arquivo desejado
### - git commit - m "digite aqui a sua explicação"
É utilizado para adicionar uma explicação nas modificações que foram feitas
### - git reset
Tira os arquivos adicionados na área de "stage" e é possível voltar a modifica-lo
### - git log / Git log --oneline
Mostra os commits realizados
### - git checkout HEAD~N / git checkout sua branch
O "N" siginifica o commit desejado que quer acessar, e sua função é voltar o código para aquele determinado commit, 
sua função é apenas de verificação nunca realizar modificações no arquivo vizualizado. Para voltar o arquivo original
utilize ***git checkout nome da sua branch***
### git reset --soft HEAD~1
Sua função e desfazer o último commit sem alterar o arquivo, o commit íra voltar para a área de "stage"
### git reset HEAD~N / git reset código commit -> git reset 97afdf2
Deleta o commit desejado e deleta todas as alterações realizadas no código, ação destrutiva.
### git pull origin main
Caso o repósitorio esteja atrasado em relação ao servidor realiza-se um pull em seguida de git commit, irá abrir o
editor de texto VIM utiliza o "i" para inserir um comentário "esq" e ":qw" para finalizar utiliza o git push
### git pull origin main - resolvendo conflito
Caso faça alteração no mesmo código em locais diferentes o git ira perguntar qual será a versão que deve ser salva,
é so abrir o editar apagar a edição indesejada e realizar um *git add . git commit -m "msg" git push*
