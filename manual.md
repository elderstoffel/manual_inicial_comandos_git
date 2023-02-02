# criar repositorio publico no github 
manual_inicial_comandos_git

# criar um diretório local
mkdir manual_git
cd manual_git

#clonar o repositorio criado no diretorio acima
git clone https://github.com/elderstoffel/manual_inicial_comandos_git.git

#verificar o status da sincronização dos arquivos com o git
git status

#adicionar arquivos ao git
git add .

# realizar o commit dos arquivos adicionando uma mensagem de identificação
git commit -m "mensagem do commit"

# enviar os arquivos ao repositorio do github
git push origin main

#recuperar um arquivo deletado por engano
#verificar o status e pegar o nome do arquivo
git status 
git restore nomedoarquivo


