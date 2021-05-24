## aula 1 - github

Aprendendo a utilizar o github

- [Instalar git bash](https://gitforwindows.org/)
- Configurar vscode para utilizar o github.
- Criar repositório no github.
- Enviar dados para o repositório.
-- Adicionar link do repositorio remoto a uma variavel de origem local.
```sh
git remote add origin https://github.com/wesleycbl/aula-1.git 
```
-- inicia o repositório local.
```sh
git init
```
-- adiciona os arquivos alterados ao repositório local.
```sh
git add .
```
-- Finaliza as alterações e prepara para ser enviada.
```sh
git commit -m "Aqui vai o comentario da sua modificação"
```
-- Envia as alterações para  repositorio de origem e branch especificada..
```sh
git push -u origem master
```