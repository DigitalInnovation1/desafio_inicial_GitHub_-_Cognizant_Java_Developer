- git --version

- git init

- git clone -> clona o repositório; cria diretório com nome do repositório dentro do diretório atual

- git pull origin main -> sincroniza (modificando) o local (na máquina) tendo como base o ramo main do repositório chamado origin; origin é o nome do repositório/servidor (server shortname), esse nome origin é dado automaticamente pelo comando git clone

- git push origin main

- git config --global user.name "nome"

- git config --global user.email EMAIL

- git branch --show-current

- git branch -> mostra ramos (infelizmente não mostra repositórios)

- git branch -m main -> renomeia o branch atual para main; -m é de move

- git branch -avv -> mostra os branchs de todos os repositórios remotos

- git status

- git add README.md

- git commit -m "Meu primeiro commit"

- git commit (sem o -m) -> um editor de texto abre para colocar o resumo de edição

- git config --list -> mostra as configurações

- git config --global --unset user.email

- git config core.editor "nano"

- git log

- git remote -v -> mostra repositórios remotos; -v é de verbose

- git remote show NOME_DO_REPOSITORIO -> mostra alguns detalhes do repositório remoto nomeado

- git remote rm -> remove uma URL remota do repositório

se algum comando reclamar tentar com cuidado com -f que seria forçosamente
