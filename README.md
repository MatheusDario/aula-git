# Estudando os principais conceitos sobre Git e GitHub

## Alguns comandos importantes e como funciona

### - git init
Inicializa o repósitorio vazio dentro do arquivo desejado;
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
Sua funcao e desfazer o último commit sem alterar o arquivo, o commit íra voltar para a área de "stage"
