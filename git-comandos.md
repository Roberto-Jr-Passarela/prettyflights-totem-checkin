# Git Comandos Essenciais

## 1. Inicialização

### git init

Inicializa um repositório Git.

Exemplos:

- git init
- git init meu-projeto

---

### git clone

Clona um repositório remoto.

Exemplos:

- git clone https://github.com/user/repo.git
- git clone URL_DO_REPOSITORIO

---

## 2. Configuração

### git config

Define configurações do Git.

Exemplos:

- git config --global user.name "Roberto"
- git config --global user.email "email@email.com"

---

### git status

Mostra o estado atual do repositório.

Exemplos:

- git status
- git status -s

---

## 3. Controle de Arquivos

### git add

Adiciona arquivos ao stage.

Exemplos:

- git add .
- git add arquivo.txt

---

### git commit

Salva alterações no histórico.

Exemplos:

- git commit -m "feat: adiciona login"
- git commit -m "fix: corrige erro"

---

### git rm

Remove arquivos do Git.

Exemplos:

- git rm arquivo.txt
- git rm -r pasta

---

### git mv

Move ou renomeia arquivos.

Exemplos:

- git mv antigo.txt novo.txt
- git mv pasta1 pasta2

---

## 4. Branches

### git branch

Lista ou cria branches.

Exemplos:

- git branch
- git branch develop

---

### git checkout

Troca de branch.

Exemplos:

- git checkout main
- git checkout develop

---

### git checkout -b

Cria e troca para uma nova branch.

Exemplos:

- git checkout -b feature/login
- git checkout -b hotfix/correcao

---

### git merge

Realiza merge entre branches.

Exemplos:

- git merge develop
- git merge feature/login

---

## 5. Histórico

### git log

Mostra histórico de commits.

Exemplos:

- git log
- git log --oneline

---

### git diff

Mostra diferenças entre arquivos.

Exemplos:

- git diff
- git diff main develop

---

## 6. Repositório Remoto

### git remote

Gerencia repositórios remotos.

Exemplos:

- git remote -v
- git remote add origin URL

---

### git push

Envia alterações para o remoto.

Exemplos:

- git push origin main
- git push origin develop

---

### git pull

Baixa alterações do remoto.

Exemplos:

- git pull origin main
- git pull origin develop

---

### git fetch

Busca atualizações sem merge.

Exemplos:

- git fetch
- git fetch origin

---

## 7. Versionamento

### git tag

Cria tags de versão.

Exemplos:

- git tag v1.0.0
- git tag -a v1.0.1 -m "hotfix"

---

### git rebase

Reorganiza commits.

Exemplos:

- git rebase main
- git rebase develop

---

### git stash

Salva alterações temporariamente.

Exemplos:

- git stash
- git stash pop
