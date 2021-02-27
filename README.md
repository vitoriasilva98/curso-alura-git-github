# curso-alura-git-github
Curso Alura: Git e GitHub, aprendendo os comandos e como utilizar

Esse é um novo arquivo no repositório, mas na versão remota, testando upagem para o repositório remoto.

Comandos aprendidos até agora: git pull - atualiza o repositório local
git status - 
git clone - Clonar repositório 
git add . - para enviar tudo 
git add nome-do-documento.extensão - para enviar só uma arquivo

git pull - comando para trazer as alterações do repositório online (remote)

-----------------------------------------------------------------
COMANDOS LISTADOS EM ORDEM DE EXECUÇÃO - NA AULA DA FACULDADE
-----------------------------------------------------------------
git clone - clonar pasta remota

git init - utilizar pasta
git add/ git add . - adicionar arquivo ou repositório/ adicionar tudo na pasta
git commit -m "mensagem..." - comando para descrever alterações.
git push - comando para enviar informações para repositório remoto. 
--------------------------------------------------------------------------
ls - lista os arquivos do diretório atual
cd - entra em um repositório
cd .. - sobe um repositório
--------------------------------------------------------------
COMANDOS APRENDIDOS NO CURSO DA ALURA
--------------------------------------------------------------
git remote - lista todos os arquivos do diretório atual
git remote add local URL - o comando está adicionando um repositório local em outro diretório (OBS: só depois de tirar o "local" funcionou)
git remote -v - confirmação de endereço (url), para ver se está correto.
git init --bare - esse comando ativa o repositório transformando ele em puro, somente para consultas, não dá para editar nada dentro dele.(Com este comando nós criamos um repositório que não terá a working tree, ou seja, não conterá uma cópia dos nossos arquivos.)
git log - histórico de alterações
.gitignore
-------------------------------------------------------------
git remote rename origin local - comando para renomear pasta, rename(renomear) origin(nome repositório atual) local (renomeação deseja)
git pull local master - trazendo os dados de um repositório para outro, usando o parâmetro master para linkar.
git log -p - ver alterações realizadas
origin - repositório padrão
-------------------------------------------------------------
git remote add origin url (online (ex github)) - comando para adicionar um repositório online para o local
git push -u origin master - enviar dados (para onde eu quero enviar - origin) e (o que eu quero enviar - master)


Ordem de execução--------------------------------------------------
        1º Alterar documento "Editor de texto"
        2º Dicionar essas alterações no git (git add . - para adicionar todos os arquivos novos e atualizados)
        3º Confirmar alteração através do (git status)
        4º Adicionar as novas alterações em um pacote para ser enviado para o servidor (git remote add local master)
        5º Fazer o commit fazer uma descrição das atualizações, fechar o pacote (git commit -m "...")
        6º Enviar para o servidor (git push local master)
--------------------------------------------------------------------------------
        7º Depois só entrar na pasta do novo usuário e puxa as informações atualizadas (git pull local master)
-------------------------------------------------------------------------------
COMANDO PARA DELETAR ARQUIVOS DO DIRETÓRIO-------------------------------------

        1º Selecionar arquivo para deletar (git rm arquivo.extensão)
        2º Verificar status (git status ou ls)
        3º fazer um commit para efetivar a exclusão (git commit -am "Remoção...")   
