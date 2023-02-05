COMANDOS GIT:

	- git rebase: alterar os últimos commits dados do arquivo (na branch que ele tiver). ele serve para integrar as alterações feitas no arquivo, no repositório local.
	- git reset (usado para alterar aquivos locais): serve pra desfazer alterações realizadas em arquivos locais, após o commit  ter sido executado. Vamos supor que por algum motivo eu dei um commit em um arquivo, mas percebi que errei. então posso usar esse comando pra desfazer a alteração.
			git reset [modo] [nomedoarquivo | commit]
	- git revert (usados para alterar arquivos em branch pública):  decarta commits em uma branch pública 
	- git checkout: descarta alterações no diretório 
	- git ignore (.gitignore): é um arquivo de texto que serve pra dizer quais arquivos/pastas ele deve ignorar em um determinado projeto.
	- git status: vai mostrar o status dos arquivos e branchs que estão no meu git. mostra se tem algum arquivo pra ser commitado, se teve algum arquivo que recentemente foi modificado, arquivos não monitorados, etc
	- git commit -m "Definição do objetivo desse repositório": dentro do diretório que eu estiver, esse comando vai dar um 'título' de status ao diretório e vai commitar;
	- git push: ele vai enviar o arquivo comitado ao diretório público (git web);
	- git commit -a -m "Atualização": estou dando um titulo ao diretorio e ao mesmo tempo comitando o arquivo ao diretorio na web;
	- git add nomedoarquivo: comando para criar um arquivo;
	- git pull: eu baixo as alteraçẽos feitas no git web pro git local;
	- git branch nomedabranch: comando pra criar uma branch nova;
	- git branch --list: lista as branchs existentes;
	- git branch delete nomedabranch: apaga o nomedabranch desejada;