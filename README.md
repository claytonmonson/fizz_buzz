# FizzBuzz

Projeto FizzBuzz do curso
[Elixir e Phoenix do Zero: Crie sua primeira API Phoenix](https://www.udemy.com/course/elixir-e-phoenix-do-zero/)

## Descrição
Dada uma lista:

* Múltiplos de 3 são substituídos por Fizz
* Múltiplos de 5 são substituídos por Buzz
* Múltiplos de 3 e 5 são substituídos por FizzBuzz

Exemplos

[1, 2, 3, 4, 5, 15]  →  [1, 2, Fizz, 4, Buzz, FizzBuzz]

[1, 2, 4, 8, 10] → [1, 2, 4, 8, Buzz]

Obs.: lista deve ser lida de um arquivo. Caso arquivo não exista, gerar erro para o usuário.

## Installation

```elixir
def deps do
  [
    {:fizz_buzz, "~> 0.1.0"}
  ]
end
```

Documentation can be generated with [ExDoc](https://github.com/elixir-lang/ex_doc)
and published on [HexDocs](https://hexdocs.pm). Once published, the docs can
be found at <https://hexdocs.pm/fizz_buzz>.

