# Lista de comandos GIT aprendidos no Alura

## Inicializar repositório local
```	
git init
```

## configurar o usuário do git
```	
git config --global user.email "voce@exemplo.com.br"
git config --global user.name "seu nome"
```

## Definir o nome da branch local a ser trabalhada
```	
git branch -M nome_da_banch_remota 
```

## Sincronizar o repositório local com o remoto
```
git remote add origin link_do_repositorio_remoto
```

## Subir o código para o repositório
```
git push -u origin nome_da_branch_remota
```

## Baixar para a sua máquina o repositório remoto
```
git clone link_do_repositorio
```

## Listar os repositórios remotos conectados (Adicionados no repo. Local)
```
git remote
```

## Para adicionar um novo editor na linha de autoria, deve-se seguir a seguinte estrutura.
```
	git commit -m "Modificações informadas"
	>
	>
	Co-authored-by: nome_do_co_autor <nome@email.com>
```

## Reverter modificações do ultimo commit sem apaga-lo e criar um novo commit (Ctrl + Z)
```
	git revert numero_do_rash_do_ultimo_commit
```

## Resetando um commit (--hard) - Realiza um reset forçado para o penultimo commit
```
	git reset --hard numero_do_id_do_commit
```

## Alterar um commit
```
	git commit --amend -m "Novo Commit"
```

## Ingnorar um arquivo no Git
>> É necessário criar um arquivo com o nome ".gitignore" e dentro dele, informar os arquivos ou os diretórios
