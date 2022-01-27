# jQuery
"write less, do more"
- Biblioteca de JavaScript
- Carregamento rápido
- Converte para JS (ECMAScript) padrão 
- Crossbrowser: funciona em diversos navegadores
- Escrever um código para todos os navegadores
- Rápida captura e transmissão de dados 
- Manipula o DOM
- Facilita a consulta (query) a elementos
- Extensível com plugins
- Instalação: https://jquery.com/download/

## Seletores
### Simples
```
    $('h4') // tag
    $('.featured-item') // class
    $('#featured') // id
```

### Compostos 
```
    $('h4, h6')

    $('div h4')

```


## Plugins
jQuery Mask https://igorescobar.github.io/jQuery-Mask-Plugin




# Gulp

- Organização das pastas 
- e então rodar na pasta "npm unit -y"
- apos baixar o package.json se quiser preencher alguns dados

- agora basta rodar o codigo "npm install gulp-cli -g" (Para instalar globalmente)

# Gerenciamento de independencias 

- apos a instalação global rodar "gulp" 
- mostrara um erro 

- mas vc pode seguir instalando suas dependencias como...

### Jquery 
- usando o "npm install jquery"
### Bootstrap 
- usando o "npm install bootstrap"
Caso queira mais dependecias entrar no site de npm e verificar, em seguida basta instalar
nisso as criara uma pasta escrito "node-modules" e um arquivo package diferente
vc pode ate apagalos de imediato ate pq as dependecias apos instaladas com npm serao registradas no package.json.
-  então caso outro desenvolvedor entre no seu projeto basta ele rodar npm install que instalara as dependecias utilizadas pot ti no projeto, que criara de novo o node-modules porem com as suas dependecias (jquery, bootstap e etc)
