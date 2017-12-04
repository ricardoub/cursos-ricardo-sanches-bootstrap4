# Passo a passo do projeto

## Dependências de sistema
```
sudo apt-get install ruby ruby-sass
```

## Dependências de desenvolvimento e projeto
```
npm init -y
npm install -S bootstrap@4.0.0-beta.2 jquery popper.js
```

## Para compilar os arquivos
```
sass --watch node_modules/bootstrap/scss:public/css
```
No arquivo src/scss/style.scss colocar:
```
@import "../../node_modules/bootstrap/scss/bootstrap";
```
