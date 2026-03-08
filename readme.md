# Comandos básicos do Git

## Inicializar repositório
- `git init`  
  Inicia um repositório Git na pasta atual (geralmente começa com a branch `master` ou `main`).

---

## Ver estado dos arquivos
- `git status`  
  Mostra o estado atual dos arquivos:
  - arquivos rastreados
  - não rastreados
  - modificados

---

## Adicionar arquivos para commit

- `git add NOME_DO_ARQUIVO`  
  Adiciona um arquivo específico para a **staging area**.

- `git add .`  
  Adiciona **todos os arquivos modificados** para a staging area.

---

## Salvar alterações

- `git commit -m "mensagem"`  
  Salva as alterações da staging area no **repositório local**.

---

## Histórico de commits

- `git log`  
  Mostra o histórico completo de commits.

- `git log --oneline`  
  Mostra o histórico de forma resumida.

---

## Ver alterações no código

- `git diff`  
  Mostra as diferenças no código antes do commit.

---

# Trabalhando com Branches

## Ver branches
- `git branch`  
  Mostra todas as branches do repositório.

---

## Criar nova branch
- `git checkout -b NOME_DA_BRANCH`  
  Cria uma nova branch e muda para ela.

Tudo o que for alterado ficará apenas nessa branch.

---

## Trocar de branch
- `git checkout main`  
  Volta para a branch principal.

---

## Juntar branches
- `git merge NOME_DA_BRANCH`  
  Junta as alterações da branch especificada na branch atual.

---

## Apagar branch
- `git branch -d NOME_DA_BRANCH`  
  Remove uma branch que não será mais utilizada.

---

# Conectar com GitHub

## Definir branch principal
- `git branch -M main`  
  Muda o nome da branch principal de `master` para `main`.

---

## Conectar repositório local ao GitHub
- `git remote add origin LINK_DO_REPOSITORIO`  
  Cria a conexão do repositório local com o repositório remoto no GitHub.

---

# Enviar código para o GitHub

- `git push -u origin main`  
  Envia os commits e arquivos da máquina local para o GitHub.

Depois do primeiro push, basta usar:

- `git push`

---

# Baixar alterações do GitHub

- `git pull`  
  Baixa alterações do repositório remoto para o repositório local.

---

# Clonar repositório

- `git clone LINK_DO_REPOSITORIO`  
  Clona um repositório do GitHub para o computador.

---

# Pull Request

- **Pull Request (PR)**  
  Usado para enviar alterações para o repositório de outra pessoa ou para revisar mudanças antes de integrar no projeto.  
  Geralmente feito diretamente pelo **GitHub**.

---

# Navegação no terminal

- `cd NOME_DO_PROJETO`  
  Entra na pasta do projeto pelo terminal.