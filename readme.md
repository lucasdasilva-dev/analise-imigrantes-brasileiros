python -m venv .venv: Usar ambiente virtual.

source .venv/scripts/activate: Ativar ambiente virtual.

pip install -r requirements.txt: instalar bibliotecas de uma arquivo.

ls -la .git: verifica diretórios ocultos.

rm -rf .git: apaga pasta.

git init: inicia repositório.

git status: Verifica status do reposítorio.

git add requirements.txt: adiciona arquivo para ser monitorado para o commit.

git add . : adiciona todos arquivos do diretório para serem monitorados para o commit.

git config --global user.name "Nome"
git config --global user.email "lucas@gmail.com": configura diretório git via e-mail

git commit -m "Primeiro commit: Commit todos os arquivos que estavam sendo monitorados e informa uma mensagem.

git log: verifica os logs do git

criar chave de acesso ao repositório: ssh-keygen -t rsa -C "lucasdasilva.desenvolvedorlds@gmail.com"

Utilizar em grupo somente a chave que fica no arquivo .pub depois de gerada

git push: joga minhas alterações local para o repositório remoto

git branch: verifica sua base: master ou base

git push -u origin master: envia para o repositório
ou
git push -u origin main: envia para o repositório

git clone: passar url do epositorio(git@github.com:lucasdasilva-dev/analise-imigrantes-brasileiros.git)

git checkout: pega uma branch para trabalhar / muda local

gitmerge(nome da branch): para unificar os códigos

git branch -d (nome da branch): faz a exclusão dessa branch.

git pull: obter atualizações do repositório central