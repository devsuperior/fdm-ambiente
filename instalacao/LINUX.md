# INSTALAÇÃO LINUX

## Curl
- Instalar o curl
```
sudo apt-get install -y curl
```
- Conferir a instalação: 
```
curl
```

## Git

- Instalar: 
```
sudo apt-get install -y git
```

- Conferir a instalação: 
```
git
```

## Java JDK 17

- Instalar Java: 
```
sudo apt install openjdk-17-jdk
```

- Verificar a instalação: 
```
java -version
```
- Configurar JAVA_HOME:
  - Verificar caminho Java: 
  ```
  sudo update-alternatives --config java
  ```
  - Edite o arquivo .bashrc: 
  ```
  code ~/.bashrc
  ```
  - Copie o código abaixo no final do arquivo (observe a versão do seu JDK). Salve o arquivo.
  ```
  JAVA_HOME=/usr/lib/jvm/java-17-openjdk-amd64
  export JAVA_HOME
  export PATH=$PATH:$JAVA_HOME
  ```
  - Abra um novo terminal e teste: 
  ```
  echo $JAVA_HOME
  ```

## Maven

- Instalar Maven: 
```
sudo apt-get install maven
```
- Verificar a instalação: 
```
mvn -v
```
- Configurar M2_HOME:
  - Observe o valor de Maven Home no comando `mvn -v` acima
  - Acrescente no final de ~/.bashrc:
  ```
  M2_HOME=/usr/share/maven
  export M2_HOME
  ```
  - Abra um novo terminal e teste: 
  ```
  echo $M2_HOME
  ```

## Node 16

```
sudo apt update

curl -sL https://deb.nodesource.com/setup_16.x | sudo -E bash -

sudo apt-get install nodejs
```

## YARN

```
 curl -sS https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -
 
 echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list
 
 sudo apt-get update && sudo apt-get install yarn

```

## Heroku CLI

```
https://devcenter.heroku.com/articles/heroku-cli
```

## VS Code

```
https://code.visualstudio.com/download

sudo snap install code --classic
```

## Postman
- Instalar com snap: 
```
snap install postman
```

## Intellij Community
https://www.jetbrains.com/pt-br/idea/download

