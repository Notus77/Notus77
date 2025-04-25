## Conjectura da Média dos Três Primos

Explorando uma ideia que tive ao estudar mais a fundo os números primos e a lei dos grandes números, me veio uma ideia aparentemente tosca — mas gosto de sempre "brincar" com a matemática, e o Python é um grande aliado nessas minhas aventuras.

O objetivo aqui é tentar achar um padrão em algo que, por natureza, não possui padrão: os números primos. Com o tempo, pretendo refinar a aproximação observada nessa conjectura.

### Interpretação da Conjectura

Considere três números primos consecutivos (por exemplo, p1, p2 e p3), onde p2 é o primo do meio, e todos estão em ordem crescente, como 3, 5 e 7.

Some esses três números:
S = p1 + p2 + p3

Divida a soma por 3 (o número de termos):
M = S / 3 = (p1 + p2 + p3) / 3

Minha conjectura afirma que M será igual ou "aproximado" ao primo do meio, p2.

Minha conjectura afirma que **M será igual ou aproximadamente igual ao primo do meio**, p2.

### Exemplos:

**Para os primos 3, 5 e 7:**
- Soma: 3 + 5 + 7 = 15  
- Divisão por 3: 15 / 3 = 5  
- Primo do meio: 5  
- Resultado: M = 5, que é exatamente igual ao primo do meio.

**Para os primos 11, 13 e 17:**
- Soma: 11 + 13 + 17 = 41  
- Divisão por 3: 41 / 3 ≈ 13.666...  
- Primo do meio: 13  
- Resultado: M ≈ 13.666, que é "aproximado" de 13.

---

Portanto, os números primos continuam sendo um mistério interessante: não seguem um padrão fixo e as distâncias entre eles são imprevisíveis. 
No entanto, esta conjectura sugere que, mesmo com o crescimento dos primos, **a média dos três ainda permanece próxima ao primo central** — o que abre espaço para futuras análises e explorações.
