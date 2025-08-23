# 10 - Median of Two Sorted Arrays (Mediana de Dois Arrays Ordenados)

## Descrição
Dado dois arrays ordenados `nums1` e `nums2`, de tamanhos `m` e `n` respectivamente, retorne a mediana dos dois arrays ordenados combinados.

A complexidade de tempo geral da solução deve ser **O(log(m+n))**.

---

## Exemplos
```bash
Exemplo 1
Entrada: nums1 = [1,3], nums2 = [2]
Saída: 2.00000

Explicação: O array mesclado é [1,2,3], e a mediana é 2.
```
```bash
Exemplo 2
Entrada: nums1 = [1,2], nums2 = [3,4]
Saída: 2.50000

Explicação: O array mesclado é [1,2,3,4], e a mediana é (2 + 3) / 2 = 2.5
```
---
## Restrições

- nums1.length == m

- nums2.length == n

- 0 <= m <= 1000

- 0 <= n <= 1000

- 1 <= m + n <= 2000

- -10⁶ <= nums1[ i ], nums2[ i ] <= 10⁶
---

### **Próximos Passos**

1.  **Implemente a Solução:** Crie um arquivo de código para resolver o desafio. Siga os critérios de avaliação e certifique-se de que sua solução é limpa e organizada.

2.  **Faça o Commit:** Ao finalizar sua solução, use a seguinte mensagem de commit semântico: `feat: Resolve o desafio '[Nome do Desafio]'`.

3.  **Vá para o Próximo:** Continue para o próximo desafio na lista.
