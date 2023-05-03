![Imagem da Capa do Projeto de Formulário](https://i.imgur.com/iYdBrl6.png)
# Projeto: Crie e compartilhe seu evento
## Tecnologias Estudadas 🚀
- html 
- css

### Aplicando estilos aos agrupamentos restantes


### Links
- [Yoksel - url-encoder svg](https://yoksel.github.io/url-encoder/)

## html

### Validação de dados

Para começar a colocar uma validação de formulário, vamos utilizar a palavra `required` que serve para exigir um dado do usuário.  

Por exemplo:

```html
  <input type="text" id="event-title" required />
```


Quando colocamos essa palavra, queremos dizer que o campo precisa ser preenchido.

### Através do CSS
Para fazer a validação de dados através da estilização, fazemos da seguinte forma:
```css
  input:invalid {
    border: 1px solid red;
  }
```

### Propriedade minlength

Ao usar esta propriedade, estou limitando a quantidade de caracteres a ser digitado no campo, por exemplo:
```html

```