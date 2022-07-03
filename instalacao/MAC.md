# INSTALAÇÃO MAC

## Instalar o Homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```
1. Update HomeBrew.
``` 
$ brew update 
```
2. Add the casks tap.
```
$ brew tap homebrew/cask-versions
```

## Git
```
$ brew install git
```

## Java 17
```
$ brew tap AdoptOpenJDK/openjdk
$ brew install --cask adoptopenjdk17
```

- Verificar a instalação: 
```
$ java —version
```

## Maven
```
brew install maven
```
- Verificar:
```
mvn -v
```

## Node & NPM 
```
$ brew install node
```

## YARN (Caso queira usar o YARN ao invés do NPM)

```
$ brew install yarn
```

## Heroku CLI 
Criar uma conta no site do Heroku
https://devcenter.heroku.com/articles/heroku-cli#getting-started
- Instalar o heroku CLI
```
$ brew tap heroku/brew && brew install heroku
```
- Vincular a sua conta com a instalação no computador
```
$ heroku autocomplete
```
- Esse comando irá abrir o site de login, faça login com seu usuário e senha


## VS Code

1. Download Visual Studio Code for macOS. https://go.microsoft.com/fwlink/?LinkID=534106
2. No Finder abrir a pasta de downloads e localizar o arquivo baixado. 
3. Arrastar o Visual Studio Code.app para a pasta Applications , para que ele fique disponível no macOS Launchpad.
5. Adicionar VS Code na Dock clicando com o botão direito no icone e no menu de contexto selecionar: Options, Keep in Dock.

## Postman 
```
$ brew cask install postman
```

## Intellij Community
https://www.jetbrains.com/pt-br/idea/download

