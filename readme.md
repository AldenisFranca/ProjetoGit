Olá, esse projeto ensina você a usar o git.

1 - Baixa o git e instala na máquina.
2 - Cria uma pasta no seu PC e abre essa pasta no VSCode.
3 - Abre essa pasta no windows e botão direito -> Git Bash Here (ou abre um terminal no VSCode e escolhe o terminal bash)
4 - git init (inicializar um repositório git vazio)
5 - git add NOME_DO_ARQUIVO (ele fica na espera para entrar no sistema até ser dado o commit) ou só . para add todos os arquivos.
6 - git status
7 - git commit -m "COMENTÁRIO SOBRE O ARQUIVO ADICIONADO"
8 - git branch -M "main" (mudar de master para main)
9 - Criar um repositório no github e pegar o link HTTPS que aparece para usar no comando: git remote add origin https://github.com/AldenisFranca/ProjetoGit.git (faz a conexão da pasta da máquina local com o repositório virtual no github)
10 - git push -u origin main (para enviar os arquivos da local para o github na primeira vez)
11 - git push origin main (envia os arquivos e/ou alterações a partir da 2ª vez, pois já foi criada a ligação do remote com o github.
12 - git checkout -b "nome_da_branch"