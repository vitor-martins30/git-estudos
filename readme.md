# Estudos da ferramenta git e seus comandos 

## O que é?

## Pra que serve?

## Principais comandos

#### Cria um novo repositório para ser rastreado todas as mudanças 
```shell
git init
```

#### Exibe o status atual de todos os arquivos rastreados 
```shell
git status
```

####  Adiciona os arquivos para area temporaria "stage"
```shell
git add <nome-arquivo.extensao>
git add readme.md

git add <*.extensao>
git add *.md

git add . 
```

####  Registra uma foto das mudanças em stage 
```shell
git commit -m "sua mensagem"
```

####  Configura quem e o autor dos commits
```shell
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

####  Lista de todos os coomits registrados
```shell
git log
```

####  Vai para a mudança conforme o hash informado
```shell
git checkout <hash-commit>
```