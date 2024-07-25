# Prática de CodeCommit - AWS e GitHub Actions

Pratica de GitHub na disciplina de Base de Dados - AWS Cloud Computing CESAE

## Objetivo
Realizar a configuração de uma pipeline para conectar a base de dados do Postgres ao repositório no GitHub.

## Etapas
1. Criar um repositório no GitHub
2. Clonar para a maquina localmente através do comando git clone.
3. Salvar o arquivo SQL gerado no Postgres e salvar na pasta do repositório local.
4. Criar uma nova branch (git checkout -b xxxx) e realizar o git add ., git commit e git push para atualizar o repositório no GitHub.
5. Realizar o pull request e o merge das branchs no GitHub
6. Criar as variáveis da password (secrets) e de ambiente. 
7. Configurar o workflow no GitHub Actions com os parametros para conexão ao postgress.
8. Executar o workflow e visualizar os dados da tabela gerada na base de dados.

![image](https://github.com/user-attachments/assets/95d8c5de-660a-4f1b-87f4-e12692a35715)
