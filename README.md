## Git cheat sheet

## Criando repositorio e enviando para o repo no Github

1. Criar repositorio github

![Github new repos](https://github.com/vssaAnjos/cheat-sheet-git/blob/master/github_new_repos.png)

1.1 Será enviado para essa página

![Github repos criado](https://github.com/vssaAnjos/cheat-sheet-git/blob/master/github_new_repos2.png)

2. No diretório onde vai ser criado o repositório local
``` 
git init
```

3. Sincronizar com o repositório do Github

```
git remote add origin https://github.com/vssaAnjos/repositorio.git
```

4. Para adicinar gitignore com 

```
vim .gitignore
``` 

5. Baixar readme do Github (caso tenha sido criado) 

```
git pull origin master
```
ou 
```
git pull origin
```

6. Para adicionar os arquivos do repositório local no repositório remoto do Github

```
git add . 
``` 
ou 
```
git add <nome arquivo>
```

7. Para salvar alterações no repositório com uma mensagem no commit

```
git commit -m "comentario"
```

8. Para atualizar as alterações no repositório remoto - nessa caso o Github
```
git push origin master
```
ou
```
git push origin
```

:pushpin: Comando coringa para mostrar o status das mudanças atuais

```
git status
``` 

### Baixando repositório remoto do Github para repositório local

Para baixar as mudanças da repositorio remoto para o repositorio local

```
git pull origin master
```
ou 
```
git pull origin outra-branch
```
ou
```
git pull origin
```

### Branchs

Para listar todas branchs

```
git branch -a
```

Para trocar de branch

```
git checkout Nome-da-branch
```

Para criar nova branch
```
git branch Nome-da-branch
```

Para atualizar as alterações e nova branch ao repositório remoto (nessa caso Github)
```
git push origin Nome-da-branch
```

### Pull Request
Para abrir um Pull Request de uma branch para outra
Acessar tela de pull request
![Github new pr](https://github.com/vssaAnjos/cheat-sheet-git/blob/master/github_pr_1.png)

2- Na aba Pull Requests,selecionar as branchs - a branch base (destimo) e a branch para ser comparada. E cliclar no botão **Create pull request**
![Github new pr](https://github.com/vssaAnjos/cheat-sheet-git/blob/master/github_pr_2.png)

3- Após aberto o PR - pull request. Verificar as diferenças entre os códigos. E caso tudo certo, clicar em **merge request** 
![Github new pr](https://github.com/vssaAnjos/cheat-sheet-git/blob/master/github_pr_3.png)

4- Em seguida irá abrir a tela para confirmar o PR. Clicar em **Confirm merge**. 
![Github new pr](https://github.com/vssaAnjos/cheat-sheet-git/blob/master/github_pr_4.png)


### Referências

- https://git-scm.com/

- http://rogerdudler.github.io/git-guide/index.pt_BR.html

- http://gabsferreira.com/criando-e-enviando-arquivos-para-seu-repositorio-no-github/


### Úteis

- https://gitignore.io/
- https://ohshitgit.com/

