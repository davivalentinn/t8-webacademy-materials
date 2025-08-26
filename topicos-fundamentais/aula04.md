# **Tópicos Fundamentais**

## **Professor(a):** Catarina Costa

## **E-mail:** catarina.costa@ufac.br



### **Aula:** 04

#### **Data:** 21/08/2025

#### **Assunto:** Sistema de Controle de Versão e GitHub



##### Comandos comuns no git:

**add <file> =>** prepara alterações em arquivos para serem incluídas no próximo commit

**commit -m "msg" =>** realiza um commit com uma mensagem

**clone <repo> =>** clona um repositório remoto para a máquina local

**pull =>** baixa as alterações remotas e as mescla com as locais

**push =>** envia as alterações locais e as mescla com as remotas

**checkout <branch> =>** troca de branch

**config =>** altera configurações do git

**init =>** inicia o repositório criando uma pasta oculta chamada .git

**branch =>** lista os ramos locais

**branch <branch> =>** cria um novo ramo

**config --globaluser.name "" =>** altera o nome de usuário padrão

**config --globaluser.email "" =>** altera o email padrão

**help =>** exibe comandos git

##### Áreas de arquivo:

* **Working Diretory:** Pasta local onde estão os arquivos
* **Staging Area:** Local onde os arquivos ficam antes de passar pelo 'git add'
* **Localrepo:** repositório Git
* **Remoterepo:** repositório Git remoto

##### Apelidos

**HEAD:** local atual no histórico de commits

**main:** nome padrão utilizado para a branch principal

**origin:** nome padrão usado para o repositório remoto

##### **Estrutura de um commit:**

**git commit -m "<tipo>**: **<descrição>** - Ref. #**<id>"**

**<tipo> =>** Define o propósito do commit:

**Tipos comuns:**

* feat => nova funcionalidade
* fix => correção de bug
* docs => alterações na documentação
* style => formatação, espaços, indentação (sem alteração de código funcional)
* refactor => refatoração de código
* test => adição ou alteração de testes

**<descrição> =>** breve resumo sobre o que foi modificado no commit

**<id> =>** id da issue

