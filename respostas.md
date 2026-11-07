Qual foi a mensagem exata de erro que o Pytest imprimiu?
AssertionError: assert {'resultado': 2} == {'resultado': 8}

O que ele esperava receber e o que ele recebeu de fato?
O teste enviou os números 5 e 3 (na rota /somar/5/3) e esperava receber o resultado 8 (a soma). No entanto, como alterou o código para subtrair, recebeu de facto o valor 2 (5 - 3). O "Guarda-Costas" (CI) funcionou e bloqueou o código defeituoso.