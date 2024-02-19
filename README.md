# Script para configuração de conta local e remota no GIT.
Este é um tutorial para configuração do GIT para enviar para 2 repositorios distintos.

## #Configurando uma conta global
Se vc trabalha pra uma empresa, é essencial que vc envie para a mesma, a sua condificação, para isso vc deve configurar sua conta GLOBAL.
Para isso, siga os seguintes passos

#### Configurando conta Global
 - git config --global user.name ```Anderson Santos```
 - git config --global user.email ```"anderson.santos@emailempresarial.com.br"```
 
## #Configurando uma conta Local
Se vc trabalha em algum projeto pessoal, e deseja enviar os teus commits para algum repositorio que não seja o corporativo, 
Siga os seguintes passos:

- 1° Navegue até a pasta do projecto que esta desenvolvendo...

Ex.: cd /projetos


 #### Configurando conta Local
 - git config user.name ```Anderson Santos```
 - git config user.email ```"anderood@hotmail.com"```
 
 Desta forma, vc conseguira enviar para 2 repositorios distintos, sem um processo interferir em outro.



# Erro de configuração

Talvez tenha digitado errado ou por algum motivo, com o comando acima, nao consegue fazer a modificação.

 #### Correção

  - git config --global --add user.email "email@corporativo_Ou_Pessoal.com"
