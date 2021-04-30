# jenkins-sonarqube-docker-environment
(Jenkins + SonarQube + PostgreSQL + Nginx) on Docker

Esse script foi idealizado para automatizar a criação dos conteiners das aplicações citadas acima. A premissa é de que se está trabalhando em uma instância de um servidor Ubuntu 20.04 sem os pacotes necessários instalados. Siga os passos abaixo e tenha seu ambiente de suporte à integração contínua disponibilizado. Obs.: é necessário possuir as credenciais de adminitrador do sistema.

Se o git não estiver instalado então,
no terminal execute:
$ sudo apt install git

Se a instalação do git foi concluída ou o mesmo já estiver instalado, então:

Realize o pull do projeto
$ git clone https://github.com/andrevilas/jenkins-sonarqube-docker-environment.git

Entre na pasta do projeto
$ cd jenkins-sonarqube-docker-environment

Execute o script
$ bash deploy-jenkins-sonarqube-stack.sh

Se a instalação ocorrer sem erros então basta acessar as aplicações, realizar as devidas configurações e utilizá-las.
