# REPOSITÓRIO DE COMANDOS GIT

> Olá, este repositório tem o intuito de informar todos os comandos git que eu aprendi no curso de GIT do Digital Innovation One, para que caso eu venha esquecer, ele exista para lembrar dos devidos comandos.

#### Comandos:

​	**Criar pasta .Git no seu repositório local: **

​		_git init_ 

​	**Adicionar todos os seus arquivos:**

​		_git add *_

​	**Listar os comandos globais:**

​		_git config --global --list_

​	**Adicionar seu E-mail e Nome do Autor do Repositório:**

​		_git config --global user.email "email@online.com"_

​		_git config --global user.name "Nome_do_Autor"

​	**Editar os comandos:**

​		_git config --global --unset user.name_

> OBS: Após a modificação a pessoa pode sinalizar um novo nome adicionando um user.name "Novo_nome"

​	**Commitar o git:**

​		_git commit -m "Nome do Comentário"_

​	**Verificar o Status:**

​		_git status_

​	**Emparelhar o seu repositório local com o repositório do GitHub:**

​		_git remote add origin git@github.com:Wallison00/Git.git_

> Link deste repositório

​	**Listar os repositórios remotos que seu git tem:**

​		_git remote -v_

​	**Subir o nosso código para o Git:**

​		_git push origin master_

​	**Puxar código já existente no Git para o meu repositório local:**

​		_git pull origin master_
