# 07 - Valid Parentheses (Parênteses Válidos)

## Descrição
Dada uma string `s` contendo apenas os caracteres '(', ')', '{', '}', '[' e ']', determine se a string é válida.

Uma string de entrada é considerada válida se:
- Parênteses abertos forem fechados pelo mesmo tipo de parêntese;
- Parênteses abertos forem fechados na ordem correta;
- Todo parêntese de fechamento tiver um correspondente de abertura do mesmo tipo.

---

## Exemplos
```bash
Exemplo 1
Entrada: s = "()"
Saída: true
```
```bash
Exemplo 2
Entrada: s = "()[]{}"
Saída: true
```
```bash
Exemplo 3
Entrada: s = "(]"
Saída: false
```
```bash
Exemplo 4
Entrada: s = "([)]"
Saída: false
```
