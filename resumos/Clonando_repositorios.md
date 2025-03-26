<h1>
    <a href="https://github.com/Rafael705">
     <img align="center" width="40px" src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png"></a>
    <span> Guia de Clonagem e Conexão de Repositórios Git</span>
</h1>

## 📌 Clonando Repositórios

Você pode clonar um repositório do GitHub para sua máquina usando os seguintes métodos:

🔹 **Usando HTTPS:**
```bash
git clone https://github.com/usuario/repositorio.git
```

🔹 **Usando SSH:**
```bash
git clone git@github.com:usuario/repositorio.git
```

## 📌 Conectando um Repositório Local ao GitHub
Se já tiver um repositório local e quiser conectá-lo ao GitHub:

🔹 **Adicionando um repositório remoto via HTTPS:**
```bash
git remote add origin https://github.com/usuario/repositorio.git
```

🔹 **Adicionando via SSH:**
```bash
git remote add origin git@github.com:usuario/repositorio.git
```

🔹 **Para verificar se o repositório remoto foi adicionado:**
```bash
git remote -v
```

## 📌 Enviando Arquivos para o Repositório Remoto

Após conectar o repositório, envie os arquivos para o GitHub:
```bash
git add .
git commit -m "Primeiro commit"
git push -u origin main
```

## 📌 Desfazendo Alterações no Repositório Local

🔹 **Como alterar a mensagem do último commit:**
```bash
git commit --amend
```

🔹 **Alterando a mensagem sem abrir o editor:**
```bash
git commit --amend -m "nova mensagem"
```

🔹 **Como desfazer um commit:**
```bash
git reset --soft
```
```bash
git reset --mixed
```
```bash
git reset --hard
```

##
<div align="center">💻🛠️ Feito por <a href="https://github.com/Rafael705">Rafael Pontes 💻🛠️</a>.</div>
