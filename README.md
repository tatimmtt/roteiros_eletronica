# Roteiro 1
***
## Buffer Seguidor de tensão
Para realizar o roteiro foi seguido os seguintes passos:
1. Definir o ganho teórico no smath  
1. Simular no lt spice
1.  Analisar os resultados de simulação gráfica e comparar com os resultados teóricos

Primeiramente foi feita a análise teórica no smath:

![](https://github.com/tatimmtt/roteiros_eletronica/blob/main/prints/Smath%20teorico.png)

No ltspice foi adicionado as bibliotecas externas da texas instruments spice model do LM324N e TL082 para conseguir simular o circuito com componentes que chegam perto do comportamento do componente real.

Link que disponibiliza o modelo do LM324N: https://www.ti.com/product/LM324?keyMatch=LM324N&tisearch=Search-EN-everything&usecase=OPN

O circuito montado com o LM324N:







