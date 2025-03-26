<h1>
    <a href="https://github.com/Rafael705">
     <img align="center" width="40px" src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"></a>
    <span> Extra </span>
</h1>

## 📌 Novos Comandos do Git e Terminal

### 1️⃣ `echo` (Criar e escrever em arquivos)
O comando `echo` é usado para exibir uma mensagem no terminal ou escrever um texto dentro de um arquivo.

🔹 **Exibir uma mensagem no terminal:**
```bash
echo "Olá, Git!"
```

🔹 **Criar um arquivo e adicionar um texto nele:**
```bash
echo "Este é meu primeiro repositório Git" > arquivo.txt
```
> Isso cria (ou sobrescreve) um arquivo chamado `arquivo.txt` e adiciona o texto nele.

🔹 **Adicionar mais texto a um arquivo existente:**
```bash
echo "Nova linha adicionada" >> arquivo.txt
```
> O `>>` adiciona o texto sem apagar o conteúdo anterior.

---
### 2️⃣ `.gitignore` (Ignorar arquivos no Git)
O arquivo `.gitignore` define quais arquivos ou pastas não devem ser rastreados pelo Git (como senhas, arquivos temporários e pastas do sistema).

🔹 **Criar um `.gitignore` e adicionar regras:**
```bash
echo "node_modules/" > .gitignore
echo "*.log" >> .gitignore
```
> Isso impede que a pasta `node_modules/` e todos os arquivos `.log` sejam rastreados pelo Git.

---
### 3️⃣ `touch` (Criar arquivos vazios)
O comando `touch` cria um novo arquivo vazio sem abrir um editor.

🔹 **Criar um arquivo chamado `novo_arquivo.txt`**:
```bash
touch novo_arquivo.txt
```

---
### 4️⃣ `.gitkeep` (Manter pastas vazias no Git)
O Git não rastreia pastas vazias, mas às vezes queremos manter uma estrutura de diretórios. O truque é adicionar um arquivo chamado `.gitkeep` dentro da pasta vazia.

🔹 **Criar uma pasta e um `.gitkeep` dentro dela:**
```bash
mkdir minha_pasta
touch minha_pasta/.gitkeep
```
> Isso garante que a pasta seja incluída no repositório.

---
### 5️⃣ `git log` (Histórico de commits)
O comando `git log` exibe o histórico de commits do repositório.

🔹 **Ver todos os commits:**
```bash
git log
```

🔹 **Resumir o log (uma linha por commit):**
```bash
git log --oneline
```

🔹 **Ver os commits de um usuário específico:**
```bash
git log --author="SeuNome"
```

🔹 **Ver commits de um arquivo específico:**
```bash
git log -- arquivo.txt
```

---
## 📌 Resumo da Aula de Hoje
```
✅ `echo` → Escreve textos no terminal ou cria arquivos com conteúdo.  
✅ `.gitignore` → Arquivo que define quais arquivos o Git deve ignorar.  
✅ `touch` → Cria arquivos vazios.  
✅ `.gitkeep` → Mantém pastas vazias no Git.  
✅ `git log` → Mostra o histórico de commits.  
```
##
<div align="center">💻🛠️ Feito por <a href="https://github.com/Rafael705">Rafael Pontes 💻🛠️</a>.</div>

