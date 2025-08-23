# 08 - Merge Intervals (Unir Intervalos)

## Descrição
Dado um array de intervalos onde `intervals[i] = [starti, endi]`, una todos os intervalos que se sobrepõem e retorne um novo array apenas com os intervalos não sobrepostos que cobrem todos os intervalos da entrada.

---

## Exemplos
```bash
Exemplo 1
Entrada: intervals = [[1,3],[2,6],[8,10],[15,18]]
Saída: [[1,6],[8,10],[15,18]]

Explicação: Os intervalos [1,3] e [2,6] se sobrepõem e são unidos em [1,6].
```
```bash
Exemplo 2
Entrada: intervals = [[1,4],[4,5]]
Saída: [[1,5]]

Explicação: Os intervalos [1,4] e [4,5] são considerados sobrepostos.

```
