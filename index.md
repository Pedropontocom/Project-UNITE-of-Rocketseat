fronteditor.dev/nlw-unite
# HTML

*Hypertext*

*Markup*
- Tag
- Atributos

*Language*

# CSS
Cascading StyleSheet

```
/*declarações*/
body {
  background-color: #121214;
  color: white;
}
```

# JavaScript
```js
// variaveis
const mensagem = 'Oi, tudo bem?';
// tipos de dados
  //number
  //string
// funcao
alert(mensagem);

// objeto javascript
const participante = {
  nome: "Pedro Henrique",
  email: "hp7717433@gmail.com",
  dataInscricao: new  Date(2024, 2, 22, 19, 20),
  dataCheckIn: new Date(2024, 2, 25, 22, 00)
}

//array
let participantes = [
  {
    nome: "Pedro Henrique",
    email: "hp7717433@gmail.com",
    dataInscricao: new  Date(2024, 2, 22, 19, 20),
    dataCheckIn: new Date(2024, 2, 25, 22, 00)
  },
]

// estrutura de repetição - loop
  for(let participante of participantes){
    // faça alguma coisa aqui 
    // enquanto tiver pessoas nessa lista
    output = output + criarNovoParticipante(participante);
  }
```