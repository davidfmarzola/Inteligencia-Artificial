# Regras de Associação

• Elas relacionam atributos que “co-ocorrem” em conjuntos de itens 
(itemsets)

• As regras de associação têm a forma de regras **<se antecedente então 
consequente>**, em que antecedente e consequente são itemsets.

• Por exemplo, Se o valor da pizza está entre **34 e 38** reais, então o cliente também compra **guarana**. 

• Estas regras são calculadas a partir dos dados e são de natureza probabilística.

• Não classifica, faz **somente** associação

### Como avaliar a qualidade das regras de associação?
#### Usamos métricas de avaliação
#### Exemplo: {34-38} ⇒ {guarana}
Se o valor da pizza está entre 34 e 38 reais, então o cliente também compra guarana?!

• Suporte: Número de transações que contém todos os itens da transação, dividido pelo total de transações

• Confiança de uma regra (A ⇒ B): Indica a **proporção** de vezes que, em uma transação contendo o 
elemento A, também tem B
![image](https://user-images.githubusercontent.com/77236515/197041835-716cc14b-7b5e-4963-a471-833da67bae5c.png)

• Lift de uma regra (A ⇒ B): O quanto mais **frequente** torna-se B quando A ocorre
![image](https://user-images.githubusercontent.com/77236515/197048914-840c74e5-9b81-4f24-9ff5-dda28da86c32.png)


