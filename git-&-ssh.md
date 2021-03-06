# Instalação do Git e configuração de chave SSH no GitHub ou GitLab

- Instale o Git:
  ```
  $ sudo apt install git
  ```

- Setar usuário:
  ```
  $ git config --global user.name "user name"
  ```

- Setar e-mail:
  ```
  $ git config --global user.email "user e-mail"
  ```

- Setar editor (opcional):
  ```
  $ git config --global core.editor code
  ```

- Definir Alias hist no arquivo .gitconfig (para gerar a árvore de commits estilizada):
  ```
  $ git config --global alias.hist 'log --pretty=format:"%h %ad | %s%d [%an]" --graph --date=short'
  ```

---
- Gerar chave SSH:
  ```
  $ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
  ```

- Mostrar chave:
  ```
  $ cat .ssh/id_rsa.pub
  ```

- Copiar chave e configurar no GitHub ou GitLab

---

[**Início**](https://github.com/figueiredo-alef/configuracoes/blob/master/README.md) | [**Anterior**](https://github.com/figueiredo-alef/configuracoes/blob/master/config-basic.md) | [**Próximo**](https://github.com/figueiredo-alef/configuracoes/blob/master/flat-remix.md)

---

Feito por [Alef Figueiredo](https://github.com/figueiredo-alef)
