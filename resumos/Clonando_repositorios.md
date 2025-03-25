# 🚀 Guia de Clonagem e Conexão de Repositórios Git

Este guia explica como clonar um repositório, conectar um repositório local ao GitHub e enviar arquivos para o repositório remoto.

## 📌 1. Clonar um Repositório (Cópia do Remoto para o Local)
Você pode clonar um repositório do GitHub para sua máquina com:

🔹 **Usando HTTPS:**
```bash
git clone https://github.com/usuario/repositorio.git
```

🔹 **Usando SSH:**
```bash
git clone git@github.com:usuario/repositorio.git
```

## 📌 2. Conectar um Repositório Local ao GitHub (Ligar o Local ao Remoto)
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

## 📌 3. Enviar Arquivos do Repositório Local para o Remoto (Push)
Depois de conectar, envie os arquivos para o GitHub:

```bash
git add .
git commit -m "Primeiro commit"
git push -u origin main
```

---
📌 **Dica:** Sempre verifique se está na branch correta antes de enviar arquivos para o repositório remoto!

🛠️ **Criado por [Seu Nome](https://github.com/Rafael705)** 🚀
