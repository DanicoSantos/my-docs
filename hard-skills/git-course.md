# Curso Git e Github: Estratégias de ramificação, conflitos e Pull Request

Fork Checklist:
- Criar um *fork* - Cria uma cópia do projeto em um repositório do desenvolvedor que quer contribuir com o projeto
- Criar um repositório local e sincronizar com o remoto
- Fazer as alterações, adicionar, fazer um *commit* e dar um *push* para o repositório remoto
- Criar um pull request e esperar os administradores aprovarem e prosseguir com o o *merge* no projeto base

Cherry-pick:
- Usado quando precisamos fazer um *merge* de um *commit* específico deu uma *branch* qualquer para a *branch* que estamos trabalhando
- Comando: `git cherry-pick [commit]`

Bisect:
- Usado para pesquisar o *commit* de uma alteração específica (*search*)
- Comando: `git bisect start | good | bad | [HEAD | commit]`

Blame:
- Usado para encontrar o responsável (*desenvolvedor*) pela alteração em um determinado arquivo
- Comando: `git blame [arquivo]`



