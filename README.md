<h1>Curso de git</h1>

Este repositório foi criado para ser usado nos estudos de git, de acordo com o curso "Git e GitHub: repositório, commit e versões" da Alura. 

<h2>Módulos: </h2>

* Criação de conta no Github
* Commit, VSCode e equipe
* Adicionando arquivos
* Ramificações e merge

<h1>Executar o projeto </h1>

Para executar o projeto, deve ter o node instalado e rodar o comando: 

```
node app.js
```
<h1>Comandos</h1>

* git clone: clonar um repositório

* git log: verificar o histórico de commits
    * git log --online: verificar o histórico resumido de commits
    * git log -p: Ver mais informações no histórico
    * git log --author="user_name": histórico de algum autor específico
    * git log --since=1.month.ago --until=1.day.ago: histórico por data

* git pull: Atualização do respositório sem ter que clonar novamente

* git status: Verificar tudo o que está modificado no respositório

* git add . : Adicionar todos arquivos modificados no commit

* git commit -m "Descrição do commit": Realizar o commit

* git push: Mandar todas os commits para o repositório
    * git push origin main: fazer o push para a branch main

* git restore --source 'hash do commit' 'arquivo': Voltar o código para algum commit específico
    * Exemplo:
    ```
        git restore --source ba837b8 app.js
    ```

* git checkout -b 'nome da branch': Criar uma branch
* git checkout -b 'nome da branch': Trocar de branch
