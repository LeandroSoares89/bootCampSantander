# Comandos Git

### Inicia um repositório
```bash
git init 
```
### Verificar os comandos disponiveis
```bash
git --help
```
### Abrir/Ver documentação de um comando git 
```bash
git "nomeDoComando" --help
```
## Manipular Branches
* Criar uma nova branch
```bash
git branch "nomeDaBranch"
```
* listar branches local
```bash
git branch
git branch --list
```
* listar branches local e remotas
```bash
git branch --list --all
```
### Atualizar repositório remoto => Empurra as alterações do repositório local para o repositório remoto
```bash
git push
```
### Alterar branch 
```bash
git checkout "nomeDaBranch"
```
### Puxar/Atualizar repositório local => Trazer/puxar as alterações do repositório remoto para o repositório local
```bash
git pull
```
### baixar objetos e referências de outro repositório
```bash
git fetch 
```
### pegar todos os objetos e referencias remotos
```bash
git fetch --all
```