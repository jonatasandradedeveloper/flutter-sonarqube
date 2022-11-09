# Configurando o Sonnar no FLutter

No root no seu projeto precisa criar 2 aquivo com o nome de 

# sonar-project.properties


sonar.projectKey=flutter_rocks

sonar.projectName=Flutter Rocks

sonar.projectVersion=1.0

sonar.sources=lib

sonar.tests=test

sonar.sourceEncoding=UTF-8

# sonar.sh

flutter clean 

flutter pub get 

flutter pub upgrade

flutter test

flutter test --machine --coverage > tests.output 

/Users/macbookpro/Desktop/docker-repositories/Sonar-Docker/sonar-scanner-4.6.2.2472-macosx/bin/sonar-scanner


No seu terminal rode o comando 

./sonar.sh

## no seu .gitignore

sonar-project.properties

sonar.sh

.scannerwork

coverage

tests.output
