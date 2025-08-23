# 02 - Verificador de Palíndromo

## Descrição
Uma frase é considerada um palíndromo se, após converter todas as letras maiúsculas em minúsculas e remover todos os caracteres não alfanuméricos, ela for lida da mesma forma da esquerda para a direita e vice-versa. Caracteres alfanuméricos incluem letras e números.

Dada uma string `s`, retorne `true` se ela for um palíndromo, ou `false` caso contrário.

---

## Exemplos
```bash
Exemplo 1
Entrada: s = "A man, a plan, a canal: Panama"
Saída: true
Explicação: "amanaplanacanalpanama" é um palíndromo.
```
```bash
Exemplo 2
Entrada: s = "race a car"
Saída: false
Explicação: "raceacar" não é um palíndromo.
```
```bash
Exemplo 3
Entrada: s = " "
Saída: true
Explicação: Após remover os caracteres não alfanuméricos, s torna-se uma string vazia "". Como uma string vazia lida igual nos dois sentidos, é um palíndromo.
```
## Critérios de Avaliação
Código limpo e bem organizado

Nomeação adequada de variáveis e funções

Tratamento correto das restrições

Implementação eficiente (considerando a abordagem de dois ponteiros)
