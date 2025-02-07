# Comandos Essenciais do Git

Se você é dev, Git é seu melhor amigo! Mas você realmente domina os comandos essenciais? Se liga nessa lista rápida que pode salvar seu código (e sua sanidade)!

---

## 💡 Básico do Básico

- **`git init`** → Cria um novo repositório
- **`git clone URL`** → Clona um repositório remoto
- **`git status`** → Mostra mudanças no projeto

---

## 💡 Trabalhando no Código

- **`git add .`** → Adiciona todas as mudanças
- **`git commit -m "Mensagem"`** → Salva as alterações com uma mensagem de commit
- **`git push origin branch`** → Envia os commits para o repositório remoto na branch especificada

---

## 💡 Branches & Colaboração

- **`git branch nome-da-branch`** → Cria uma nova branch
- **`git checkout nome-da-branch`** → Muda para outra branch
- **`git merge nome-da-branch`** → Junta uma branch na branch atual (geralmente a principal)
- **`git pull origin branch`** → Atualiza seu repositório local com as alterações da branch remota

---

## 💡 Quando Dá Ruim (e Sempre Dá! 😂)

- **`git revert id-do-commit`** → Desfaz um commit criando um novo commit que reverte as alterações, sem perder o histórico
- **`git reset --hard id-do-commit`** → Volta para um ponto anterior, descartando mudanças posteriores (cuidado, pois pode perder alterações não commitadas)

---

## 💡 Comandos Adicionais

- **`git log`** → Exibe o histórico de commits com detalhes
- **`git diff`** → Mostra as diferenças entre as mudanças não commitadas ou entre commits
- **`git stash`** → Salva temporariamente alterações não commitadas para limpar o ambiente de trabalho
- **`git stash pop`** → Recupera as alterações guardadas com `git stash`
- **`git tag`** → Cria uma tag para marcar versões importantes ou lançamentos
- **`git fetch`** → Busca atualizações do repositório remoto sem mesclar automaticamente com sua branch local
- **`git rebase`** → Reaplica commits em cima de outra base, útil para manter um histórico linear
- **`git cherry-pick id-do-commit`** → Aplica commits específicos de outra branch na branch atual

---

Sinta-se à vontade para usar e adaptar esses comandos conforme suas necessidades. Dominar o Git pode fazer toda a diferença na organização e colaboração do seu código. Boas commits e happy coding! 🚀

