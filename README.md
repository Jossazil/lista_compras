# Lista de compras
compras = [
    {"produto": "Arroz", "quantidade": 2, "preco": 5.50},
    {"produto": "Feijão", "quantidade": 1, "preco": 7.80},
]

for item in compras:
    print(f"Produto: {item['produto']}, Quantidade: {item['quantidade']}, Preço: {item['preco']}")
    
print("\n---Resumo da Compra:---\n")

total = 0
for item in compras:
    total += item["quantidade"]

print(f"Total de itens: {len(compras)}")
  
