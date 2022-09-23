**1.Inicializando o repositorio local**

-> git init

**2.Verificando alterações nos arquivos**

-> git status

**3.Adcionando arquivos atuais ao proxumo commit**

-> git add nomeArquivo
-> git add .

**4.Criando versões do codigo com commit**

-> git commit  -m "Criando arquivo index.html com lista de curso"

**5.Envia as atualizações para a nuvem na branch atualmente ativa**

-> git push

**6.Modificar cofigurações do git**

-> git config -- local user.name / user.email
-> git config -- global

**7.Verificar o historicos de modificações no repositorio**

-> git reflog

**8.Como navegar entre versões do codigo**

-> git reset --hard "ID do reflog"

**9.Permite listar e ver qual branch esta ativa atualmente**

-> git branch

**10.Permite mudar de branch**

-> git branch "nomeBranch"

**11.Permite mudar e criar uma nova branch com base em outra**

-> git checkout -b  "master" "nomeBranch"

**12.Atualiza a branch atualmente ativa**

-> git pull 

**13.Permite fazer merge da branch ativa atualmente com outra branch**

-> git merge "branch a receber merge" ( sempre que utilizar antes os comandos 10 e 12)

**14.Excluir arquivos do controle de versão**

-> touch .gitignore
