**9)** Você foi contratado(a) como estagiário(a) da Tesla e está participando do desenvolvimento de um programa para simular o desempenho de um carro elétrico em uma corrida. Seu objetivo é determinar em quantos minutos o carro levará para completar uma determinada distância, levando em consideração uma velocidade inicial e uma taxa de aceleração constante. No entanto, você deseja garantir que o carro não exceda uma velocidade máxima nem que a corrida demore mais do que um tempo máximo. Implemente a lógica dessa simulação em pseudocódigo.

Considere a fórumla de atualização velocidade:
```
    velocidade = velocidadeInicial + aceleracao*tempo
```

**Resposta:**
```
Função SimularCorrida (velocidadeInicial, aceleracao, distanciaTotal, velocidadeMaxima, tempoMaximo):
    var:
        tempo = 0
        velocidade = velocidadeInicial

    Enquanto velocidade < velocidadeMaxima E tempo <= tempoMaximo:
        velocidade = velocidade + aceleracao * tempo

        Se velocidade > velocidadeMaxima:
            Retorna "Velocidade Excedida"
        
        Senão:
        distanciaAtual = velocidade * tempo

        Se distanciaAtual >= distanciaTotal:
            Retorna tempo
    
        tempo = tempo + 1

    Se tempo > tempoMaximo:
        Retornar "Tempo máximo excedido"
    

    
```
