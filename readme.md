# Conceitos de Git e Github
Este arquivo tem como objetivo armazenar os comandos básicos
para utilização de git e github

## Configuração Inicial
Rode os comandos abaixo no terminal (cmd) do seu computador.
```bash
git config --global user.name "Pedro Henrique Prado"

git config --global user.email pedro.prado6@fatec.sp.gov.br
```

## Comandos do Git
Para iniciar o GIT em uma pasta do computador utilizamos o init.
**IMPORTANTE** : Só é executado 1 vez.
```bash
git init
```

Para vincular o projeto ao Github utilizamos o comando remote, basta o repositório estar criado no Github e segur a segunda 
opção da lista de comandos que aparece no site.<br>.
**IMPORTANTE** Depois do remote deve ser executados os outros 2 comandos da página.
```bash
git remote add origin < url_repositorio_github >
```


Para verificar a situação do repositório (pasta)
usamos o status a qualquer momento.
```bash
git status
```

Para adicionar arquivos na pasta 
usamos o add quando o status mostrar arquivos em vermelho 
```bash
git add .
```

Para salvar uma alteração no git
usamos o commit -m
```bash
git commit -m "Mensagem"
```

Para baixar as alterações que estão apenas no Github utilizamos o pull. <br>
**Importante** Sempre deve baixar a última versão da nuvem antes de enviar a atual do computador.
```bash
git pull
```


Para enviar os commits do pc para o Github utilizamos o push.
```bash
git push
```


