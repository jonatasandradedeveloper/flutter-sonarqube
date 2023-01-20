# SonarQube
 
No nosso docker-compose temos toda configuração para criamos o Container e subir a imagem do SonarQube tudo configurado.

## Link do docker-compose do SonarSource

https://github.com/SonarSource/docker-sonarqube/blob/master/example-compose-files/sq-with-postgres/docker-compose.yml

## Github

git clone 

Criar os seguintes diretorios dentro do diretorio (sonar), data e extensions

## Instalando o Docker 

Lembrando que após a instalação precisa da um start no docker

## On Mac

https://docs.docker.com/desktop/install/mac-install/

## Windows

https://docs.docker.com/desktop/install/windows-install/

## Linux

https://docs.docker.com/desktop/install/linux-install/

Rode o comando no seu terminal e aguarde ele subir a imagem do SonarQube

## docker-compose up

Em seguida no seu browser acesse a url 

## localhost:9000

## Link do plugin

https://github.com/insideapp-oss/sonar-flutter

## Vamos instalar o plugin do fluter sonar

## Download do plugin

https://github.com/insideapp-oss/sonar-flutter/releases/tag/0.3.2

Depois do download criar um diretorio chamado (plugin) dentro de (extensions/) e mover seu sonar-flutter-plugin-0.3.2.jar para esse diretorio

Depois pare o seu docker-compose e inicia novamente com o docker-compose up

Vamos instalar o sonar scanner 

https://github.com/insideapp-oss/sonar-flutter


## DOC

https://docs.sonarqube.org/latest/analysis/scan/sonarscanner/

## Install

adicionar esse .zip no seu diretorio (/sonar) e precisa descompactar

On Mac

https://binaries.sonarsource.com/Distribution/sonar-scanner-cli/sonar-scanner-cli-4.7.0.2747-macosx.zip

Windowns

https://binaries.sonarsource.com/Distribution/sonar-scanner-cli/sonar-scanner-cli-4.7.0.2747-windows.zip

Linux

https://binaries.sonarsource.com/Distribution/sonar-scanner-cli/sonar-scanner-cli-4.7.0.2747-linux.zip

# Configurando o Sonnar no FLutter

<a href="FLUTTER.md">Configurando o SonarQube no projeto Flutter</a>