# Guia definitivo sobre GIT e GITHUB

## Preparação inicial de versioinamento

    - 1° Passo - Instalar o GIT => Software de versionamento
    - 2° Passo - configurar o GIT
        - git config --global user.name "MeuUserName"
        - git config --global user.email "meu@email.com"
    - 3° Passo - Iniciar o repositório dentro do projeto (.git)
        - git init
    - 4° Passo - Sincronizar o GIT com o GITHUB
        - Criar um reposiório no Github
        - git remote add origin "endereço do repositório"
    - 5° Passo - Adicionar arquivos ao repositório local (GIT)
        - git add . ( vai adicionar todos os arquivos ao repositório )
    - 6° Passo - Criar a versão local
        - git commit -m "meu texto" 
    - 7° Passo - Enviar para o GITHUB (nuvem)
        - git push -u origin main
    - 8° Passo - Atualizar repositório local com os arquivos da nuvem
        - git pull
    - 9° Passo - Clonar meu repositório da nuvem
        - git clone "endereço do repositório online"
    
