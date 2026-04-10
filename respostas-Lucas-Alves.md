aluno: Lucas Rafael da Silva Alves
matricula: 01849525

1- Qual a diferença entre git init e git clone? 
git init cria um repositório local e o git clone faz uma cópia de um repositório já existente.

2- O que faz o comando git status?
git status exibe o estado atual do repositório, mostra todos os arquivos modificados, adicionados ou removidos que ainda não foram commitados.

3- Para que serve o git add antes do git commit? 
git add serve para preparar as alterações, já o git commit ele salva registra as alteração feitas com uma mensagem de descrição prévia doq foi feito.

4- Qual a diferença entre git pull e git fetch?
o git pull baixa as alterações remotas e mecla automaticamente na sua branch atual, o git fetch só baixa as alterações feitas sem alterar automaticamente.

5- O que é um branch e por que ele é usado?
branch é uma ramificação de desenvolvimento independente e paralela à branch principal(main, master) ou outra brach(develop, style). As branch são utilizadas para que segurança, trabalho em equipes, assim ninguém sobre-escreve o seu código e nem você pode testar outars funcionalidades e só após estar funcionando adicionar a funcionalidade ao site ou app.

6- O que é um Pull Request no GitHub?
é uma proposta de alteração de código, onde um desenvolvedor solicita que suas modificações, feitas em um branch separado, sejam revisadas e integradas a branch principal.

7- Explique a diferença entre branch de origem e branch de destino em um PR.
branch de origem é da onde as alterações foram desenvolvidas e a branch de destino é onde essas novas alterações será incorporada, (normalmente a main, mas pode ter casos onde ela vai pra uma brach de revisão antes de ser incorporada na main).

8- O que acontece se duas pessoas alterarem a mesma linha de um arquivo em branches diferentes?
Ao alternar não acontece nada pois estão em branch separadas, entretanto quando foram implementar as duas alterações na mesma brach vai dar conflito e terá que aceitar só uma das alterações ou as duas. E só após isso o commit é liberado e pode finializar o git merge.

9- Para que serve o arquivo .gitignore?
é um arquivo de configuração usado no Git para instruir o sistema de controle de versão sobre quais arquivos ou diretórios devem ser ignorados quando as alterações são preparadas ou confirmadas.
Ex: node_modules

10- Qual é a função do README.md em um projeto?
a documentação inicial, "cartão de visitas" e guia principal para usuários e desenvolvedores.