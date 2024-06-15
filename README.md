# Oficina de Git e GitHub

## Introdução

- O que é Git? E GitHub?
    - Git: Sistema de controle de versão GRATUITO
    - GitHub: Serviço que hospeda o sistema de controle de versão Git

- Pra que serve?

- Como funciona
    - Terminologia
        - Alterações
        - Repositórios remoto e local
        - Projeto
        - Branch/ramificação
        - Main
        - Push e pull
    - Etapas
        - Iniciar projeto
        - Salva alterações
        - Faz commits
        - Atualiza repositório remoto
    - Estados dos arquivos
        - Não rastreado
        - Preparado
        - Confirmado
        - Modificado


## Prática Git

0. Criação de conta no GitHub

1. Instalação

* Windows: [Git - site oficial](https://gitforwindows.org)
* Linux:
```
sudo apt-get update
sudo apt-get install git
git --version
```


2. Configuração
```
git config --global user.name "Nome Qualquer" 
git config --global user.email "exemplo@seuemail.com.br"
```

3. Inicializar repositório
```
mkdir pasta && cd pasta
git init
```

4. Adicionar e confirmar arquivos
```
git add nome_do_arquivo
git commit -m "Comentário sobre a alteração"
```

5. Criar um repositório remoto
Ir ao GitHub e criar um repositório

6. Adicionar origem remota
```
git remote add origin link_remoto
```

7. Subir repositório
```
git push origin main
```


8. Atualizar repositório
```
git pull
```


9. Criar branches
```
git checkout -b nome_da_branch
git branch -m mudar_nome_da_branch
```

10. Mesclar branches

Ir para a branch final onde as alterações serão mescladas
```
git checkout main
git merge test
```

9. Usando VsCode
Ferramenta: Git Blame e Git Graph

## Prática GitHub

1. Clonar um projeto existente
```
git clone link_do_repositorio
```

2. Solicite alteração do repositório

3. Aceite as solicitações

4. Crie tarefas

5. Crie branches a parte de tarefas

## Comandos

- `git version` checa versão do git
- `git status` lista branch atual e estado dos arquivos
- `git init` inicializa projeto git
- `git add endereço_do_arquivo` adiciona arquivo
- `git commit -m "Comentário significativo"` salva arquivos adicionados
- `git push` atualizar repositório remoto com alterações locais
- `git pull` atualizar repositório local com alterações remotas
- `git checkout nome_da_branch` mudar de branch
- `git stash` salvar alterações como rascunho, sem salvar definitivamente
- `git diff branch_1 branch_2` 
- `git log` lista últimos commits da branch atual
- `git clone link_repositorio` clona localmente um repositório remoto
- `git config --list`

## Boas práticas

1. Faça commits breves e explicativos
2. Use tags para organizar suas alterações
3. Cuidado com conflitos
4. Use .gitignore
5. Sempre pesquise em caso de dúvidas
6. Crie branches
7. Faça revisão de código
8. Abra tarefas


## Referência

[git - site oficial](https://git-scm.com/docs/gittutorial)
[GIT Tutorial Para Iniciantes - Hostinger Tutoriais](https://www.hostinger.com.br/tutoriais/tutorial-do-git-basics-introducao)
[]