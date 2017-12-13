Cheatsheet:
	1) git init:
		Inicia o repositório selecionado como um repositório git
	
	2) git clone /path/to/repository name:
		Clona um repositório com o nome 'name'

	3) git add <filename>:
		Adiciona o arquivo filename para o estado "stage"

	4) git commit -m "Commit message":
		Aceita os arquivos no estado "staging"

	5) git push origin master:
		Manda as mudanças de "master" para o repositório remoto "origin"

	6) git status:
		Retorna o estado dos arquivos (untracked, unmodified, modified, staged)

	7) git checkout -b <branch>:
		Cria e seleciona um novo branch com o nome <branch>

	8) git checkout <branch>:
		Seleciona o branch <branch>

	9) git branch:
		Lista todos os branchs

	10) git branch -d <branch>:
		Deleta o branch <branch>

	11) git merge <branch>:
		Mescla o branch atual com o <branch> em um novo commit

	12) git log:
		Mostra todas as alterações do branch selecionado

	13) git log --graph:
		Mostra todas as alterações, com gráfico, do branch selecionado

	14) git diff:
		Verifica as alterações realizadas em arquivos não commitados

	15) git stash:
		Guarda informações não commitadas (WIP) em um arquivo

	16) git stash apply:
		Aplica as mudanças guardadas no stash

	17) git stash list:
		Lista de todos os stashs

	18) git stash clear:
		Limpa o arquivo stash

	19) git checkout <filename>:
		Volta o arquivo <filename> para a ultima versão commitada

	20) git reset HEAD <filename>
		Retira o arquivo <filename> do estado "staged"

	21) git reset --soft <commithash>:
		Elimina todos os commits acima de <commithash> mas mantem os arquivos no estado 
		"staged"

	22) git reset --mixed <commithash>:
		Elimina todos os commits acima de <commithash> mas mantem os arquivos no estado 
		"modified"

	23) git reset --hard <commithash>:
		Elimina todos os commits acima de <commithash> e todas as alterações

	24) git remote add <name> <gitAddress>:
		Linka o repositório atual com o repositório <gitAddress> e usando o nome <name>

	25) git push -u <name> <branch>:
		Envia os arquivos de <branch> para <name>

	26) git rebase <branch>:
		Mescla o branch atual com <branch> jogando o ultimo commit de <branch> para o final do 
		branch atual


Alias:
	* O que é:
		Alias é um "nickname" ou apelido para um comando. Por exemplo trocar o comando
		"status" pelo apelido "s". É o mesmo comando mas com outro nome.

	* Como usar:
		git config --global alias.<apelido> <comando>

	* Exemplo:
		git config --global alias.s status

	* Meus Alias:
		1) status: s
