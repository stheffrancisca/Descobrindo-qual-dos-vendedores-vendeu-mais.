# Descobrindo-qual-dos-vendedores-vendeu-mais.
Descobrindo qual dos vendedores vendeu mais.

vendas = [
    [10, 20, 100, 80, 90, 100, 20, 30, 44, 55, 33, 34, 100, 90, 80, 39, 87, 45, 50, 50, 50, 50, 40, 30, 3, 93, 39, 49, 88],    
    [100, 1, 1, 4, 5, 90, 100, 20, 4, 5, 100, 100, 100, 100, 100, 93, 20, 15, 40, 90, 90, 90, 90, 90, 90, 33, 22, 44, 43, 34],
]

vendas_vendedor1 = sum(vendas[0])
vendas_vendedor2 = sum(vendas[1])

if vendas_vendedor1 > vendas_vendedor2:
   print("Vendedor 1 vendeu mais")
else:
   print("Vendedor 2 vendeu mais")
