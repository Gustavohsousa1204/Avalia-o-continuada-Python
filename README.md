# Avalia-o-continuada-Python

totalvotos = int (input("Informe aqui a quantidade total de votos: "))
voto1 = int (input("Informe aqui a quantidade de votos Válidos: "))
voto2 = int (input("Informe aqui a quantidade de votos Brancos: "))
voto3 = int (input("Informe aqui a quantidade de votos Nulos: "))

pvalidos = (voto1 / totalvotos) *100
pbrancos = (voto2 / totalvotos) *100
pnulos = (voto3 / totalvotos) *100

print ("A quantidade total de votos foi de: ",totalvotos)
print ("O percentual de votos Válidos em relação ao total de votos é de: {:.0f}%".format(pvalidos))
print ("O percentual de votos em Branco em relação ao total de votos é de: {:.0f}%".format(pbrancos))
print ("O percentual de votos Nulos em relação ao total de votos é de: {:.0f}%".format(pnulos))
