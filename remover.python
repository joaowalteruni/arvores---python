def remover(self,valor):
  self.raiz- self.remover_recursivo(self.raiz ,valor)

def remover_recursivo(self ,no_atual , valor):
  if no_atual is None:
    return no_atual

if valor < no_atual.valor:
  no_atual.esquerda=self.remover_recursivo(no_atual.esquerda, valor)
elif valor > no_atual.valor:
  no_atual.direita = self.remover_recursivo(no_atual.direita,valor)
else:
  if no_atual.esquerda is None:
    return no_atual.direita
  elif no_atual.direita is None:
    return no_atual.esquerda

temp = self.encontrar_minimo(no_atual.direita)
no_atual.valor = temp.valor
no_atual.direita = self.remover_recursivo(no_atual.direita , temp.valor)
return no_atual
