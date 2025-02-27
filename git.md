# FLUXO DE TRABALHO
git fetch ------------ ATUALIZAR MAIN
git checkout main  ------------ ATUALIZAR MAIN
git pull origin main (minha máquina <- github)  ------------ ATUALIZAR MAIN
git checkout -b feat/home (criar branch máquina) ------------ CRIANDO UMA NOVA BRANCH E TROCANDO PARA ELA
// implementar
git add .
git commit -m "mensagem"
git push origin feat/home ----------------- MANDANDO O CÓDIGO IMPLEMENTADO NA NOVA BRANCH LOCAL PARA O GITHUB
// criar o pull request caso terminar a implementação
// fazer o merge do pr

CRUD -> 4 branchs -> 4 PR -> 4 merge
feat/listagem-produtos (atualizar a main)
feat/cadastro-produto
feat/apagar-produto
feat/editar-produto

# FLUXO DE AULA
# N tenho repo local
git clone <link> => branch main
# trocar a para a branch que está desenvolvendo
git checkout feat/......

# Tenho o repo local desatualizado
git fetch
git status
git checkout feat/.........
git pull origin feat/.......
