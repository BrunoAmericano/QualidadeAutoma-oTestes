# Qualidade e Automação de Testes

## Descrição do Projeto
Este projeto tem como objetivo demonstrar a aplicação de **testes de caixa branca** em Python.  
O foco é validar a função `maximo()`, que compara dois números inteiros e retorna o maior valor ou indica quando ambos são iguais.

A prática foi realizada no ambiente online [Replit](https://replit.com/languages/python3) sem necessidade de login ou instalação.

---

## Funcionalidades
- Recebe dois números inteiros como entrada.  
- Compara os valores e retorna:
  - O maior número entre os dois, ou
  - Uma mensagem indicando que os números são iguais.  
- Possui testes documentados cobrindo todos os caminhos lógicos (`if`, `elif`, `else`).

---

## Código Principal
```python
def maximo(a, b):
    if a > b:
        return print("O numero {} e o maior.".format(a))
    elif a == b:
        return print("Os numeros sao iguais.")
    else:
        return print("O numero {} e o maior.".format(b))
```
## Exemplos de Teste
```
# Teste 1
maximo(15, 30)  # Saída: O numero 30 e o maior.

# Teste 2
maximo(100, 20) # Saída: O numero 100 e o maior.

# Teste 3
maximo(50, 50)  # Saída: Os numeros sao iguais.
```

## Objetivos do Teste

1. Validar a lógica interna do código (teste de caixa branca).

2. Cobrir todos os caminhos possíveis do programa (if, elif, else).

3. Observar o comportamento correto da função com diferentes entradas:

   - Primeiro número menor que o segundo

    - Primeiro número maior que o segundo

    - Números iguais

## Resultados Esperados
```
| Cenário | Entrada    | Saída Esperada               |
|---------|------------|------------------------------|
| Teste 1 | (15, 30)   | "O numero 30 e o maior."    |
| Teste 2 | (100, 20)  | "O numero 100 e o maior."   |
| Teste 3 | (50, 50)   | "Os numeros sao iguais."    |
```

Todos os testes foram executados com sucesso, garantindo cobertura total do código.

## Como Executar

1. Acesse Replit – Python3.

2. Copie e cole o código principal no editor.

3. Clique em Run para executar a função e visualizar os testes.

![image](https://github.com/BrunoAmericano/QualidadeAutoma-oTestes/blob/main/Imagens/1.png?raw=true)

![image](https://github.com/BrunoAmericano/QualidadeAutoma-oTestes/blob/main/Imagens/2.png?raw=true)

![image](https://github.com/BrunoAmericano/QualidadeAutoma-oTestes/blob/main/Imagens/3.png?raw=true)