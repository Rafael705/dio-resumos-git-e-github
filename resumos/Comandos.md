# 🚀 Guia Completo de Comandos Git

Este documento contém um resumo dos principais comandos do Git para gerenciamento de repositórios.

## 📌 Comandos Essenciais

### 🔥 Remover todo o histórico do Git (⚠️ Perigoso)
```bash
rm -rf .git
```
> **Atenção:** Este comando remove completamente o controle de versão do repositório.

### 🔄 Restaurar arquivos para o estado original
```bash
git restore arquivo.txt
```
```bash
git restore .  # Restaura todos os arquivos
```

### ✍️ Editar última mensagem de commit
```bash
git commit --amend -m "Nova mensagem corrigida"
```

### ⏪ Resetar commits
- **Manter arquivos no staging:**
  ```bash
  git reset --soft HEAD~1
  ```
- **Manter arquivos modificados, mas remover do staging:**
  ```bash
  git reset --mixed HEAD~1
  ```
- **Apagar completamente as mudanças:**
  ```bash
  git reset --hard HEAD~1
  ```

## 🔀 Trabalhando com Branches

### 📌 Criar uma nova branch
```bash
git branch nova-branch
```

### 🚀 Criar e alternar para a nova branch
```bash
git checkout -b minha-nova-branch
```

### 🔄 Unir branches
```bash
git checkout main
git merge nome-da-branch
```

## 📤 Enviando e Recebendo Alterações

### ⬆️ Enviar commits para o repositório remoto
```bash
git push -u origin main
```

### 🔄 Atualizar o repositório local com o remoto
```bash
git pull origin main
```

### 📡 Buscar mudanças do repositório remoto sem aplicá-las
```bash
git fetch origin
```

## 📋 Resumo Rápido
| Comando | Descrição |
|---------|------------|
| `rm -rf .git` | Remove todo o histórico do Git. |
| `git restore` | Restaura arquivos modificados. |
| `git commit --amend -m "Nova mensagem"` | Edita a mensagem do último commit. |
| `git reset --soft HEAD~1` | Volta um commit mantendo mudanças. |
| `git reset --hard HEAD~1` | Apaga completamente o último commit. |
| `git push -u origin branch` | Envia commits para o repositório remoto. |
| `git branch` | Lista ou cria branches. |
| `git checkout -b branch` | Cria e muda para uma nova branch. |
| `git merge branch` | Mescla uma branch com a principal. |
| `git pull` | Atualiza o código local com o remoto. |
| `git fetch` | Baixa mudanças do repositório remoto sem aplicá-las. |

---
📌 **Dica:** Sempre faça `git pull` antes de começar a trabalhar para evitar conflitos!

🛠️ **Criado por [Rafael Pontes](https://github.com/Rafael705)** 🚀
