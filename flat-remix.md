# Instalação do tema Flat-Remix em qualquer distro Linux

* Procure e instale o GNOME-TWEAKS (ajustes do gnome) via Ubuntu Store:

* Agora clone o primeiro repositório (Icon set):
  ```
  $ git clone https://github.com/daniruiz/flat-remix
  ```
  
* Clone o segundo repositório (GTK theme):
  ```
  $ git clone https://github.com/daniruiz/flat-remix-gtk
  ```
  
* Crie os seguintes diretórios:
  ```
  $ mkdir -p ~/.icons && mkdir -p ~/.themes
  ```
  
* Copie o conteúdo dos diretórios clonados para os diretórios criados no item anterior:
  ```
  $ cp -r flat-remix/Flat-Remix* ~/.icons/ && cp -r flat-remix-gtk/Flat-Remix-GTK* ~/.themes/
  ```

* Remova os diretórios clonados:
  ```
  $ rm -rf flat-remix && rm -rf flat-remix-gtk
  ```

* Abra o GNOME-TWEAKS e na seção aparência escolha o tema dentre os novos de acordo com sua preferência!

---
[**Início**](https://github.com/figueiredo-alef/configuracoes/blob/master/README.md) | [**Anterior**](https://github.com/figueiredo-alef/configuracoes/blob/master/git-%26-ssh.md) | [**Próximo**](https://github.com/figueiredo-alef/configuracoes/blob/master/outros-programas.md)

---

Feito por [Alef Figueiredo](https://github.com/figueiredo-alef)
