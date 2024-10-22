#POO - Aprenda de uma vez por todas !!!!


# O que é o POO?

> POO significa “Programação Orientada a Objetos”, onde pode conter dados na forma de campos ou atributos e até funções.

Se você não entendeu, segue um exemplo:

Vamos usar como exemplo **dogs** e um **PetShop**.

Se você quer criar um sistema de PetShop onde tem os dados dos dogs, uma forma de fazer isso é com POO.

Se liga!

Vamos usar `class` para criar o objeto, e o nome dessa classe será **Dog**, onde cada dog vai ter um `id`, `nome`, `idade` e `serviço`.

Usaremos o `constructor(id, name, idade, servico)` para inicializar os objetos criados a partir da classe.

Transformando em código fica assim:

```javascript
class Dog {
  constructor(id, name, idade, servico) {
    this.id = id;
    this.name = name;
    this.idade = idade;
    this.servico = servico;
  }
}
```
O ``this`` é uma referência ao objeto atual, ou seja, o objeto que está sendo criado.

E como vamos criar cada um e armazenar?

Vamos por partes! Primeiro, para criar um novo objeto, será esse código que irá simplificar e muito o nosso tempo:
```javascript
let nwdog = new Dog(1, "Caramelo", 3, "tosa");
```
Para você lembrar, no nosso código: ```constructor(id, name, idade, servico)```

Isso nos retorna um objeto:
```
Dog { id: 1, name: 'Caramelo', idade: 3, servico: 'tosa' }
```
# E como podemos armazenar os Dogs?

Para armazenar, você pode tanto jogar no banco de dados em uma tabela ou em um array:
```
let DogsArray = [];
DogsArray.push(nwdog);
```
Espero que tenha entendido! Qualquer dúvida, é só falar comigo na DM.

```
console.log("Obrigado!");
```
