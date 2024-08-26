## Object Class in C#
> Pequeno repositório criado afim de publicar meu estudo sobre a curiosa classe Object que aparece em qualquer projeto .NET

### O que é a classe Object? 🔎
> Seguindo a hieraquia das classes em .NET, a class Object é a "classe mãe" de todas as classes. Já que todas as classes se derivam diretamente ou indiretamente dela.


### Ok, mas qual é a serventia desta classe?
> Ela promove métodos para serviços de baixo nível para as suas classes heredeiras/filhas.

* **Exemplos de Métodos**.
1. `Equals()` - Determina se um objeto especificado é igual ao objeto atual.
2. `GetHash()` - Promove a função de hash padrão.
3. `GetType()` - Obtém o *Type* da instância atual.
4. `ToString()` - Retorna uma cadeia de caracteres que representa o objeto atual.

> [!NOTE]
> Existem diversos outros métodos da classe Object. No exemplo acima, citei apenas os mais conhecidos.

### Outras considereções
* **Polimorfismo:** A classe Object permite que você trate objetos de diferentes tipos como se fossem objetos de um tipo mais geral.
* **Boxing e Unboxing:** Esses mecanismos permitem converter tipos de valor em objetos e vice-versa, e a classe Object desempenha um papel fundamental nesse processo.
* **Métodos fundamentais:** A classe Object fornece métodos como `Equals`, `GetHashCode`, `ToString` e `GetType`, que são a base para muitas operações comuns em objetos.

Analise o código disponível neste respositório para esclarecimentos quanto ao uso da classe descrita.

## Referências 📝
[Object Classe - Microsoft](https://learn.microsoft.com/pt-br/dotnet/api/system.object?view=net-8.0)

[System.Object class - Microsoft](https://learn.microsoft.com/en-us/dotnet/fundamentals/runtime-libraries/system-object)

[C# | Objects Class - Geeks for Geeks](https://www.geeksforgeeks.org/c-sharp-object-class/)

## Considerações finais ✨
Obrigado por ter chegado até aqui! Este repositório tem o intuito de escrever apenas um resumo ditático do que eu aprendi sobre a Object Class (System) e também para sanar a curiosidade de quem porcurar sobre tal assunto.

*Obrigado!* 🖤