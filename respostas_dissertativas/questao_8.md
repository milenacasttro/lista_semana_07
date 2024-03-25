**8)** Considere a implementação da classe base FormaGeometrica em um sistema de modelagem de formas geométricas. Sua tarefa é implementar, utilizando pseudocódigo, as classes derivadas Retangulo e Circulo, que herdam da classe FormaGeometrica, adicionando atributos específicos e métodos para calcular a área de um retângulo e de um círculo, respectivamente.

```
Classe FormaGeometrica:
    Atributos:
        - cor

    Método Construtor(cor):
        Define o valor do atributo cor com o valor passado como parâmetro.

    Método CalcularArea():
        # Implementação genérica para cálculo de área, a ser sobrescrita pelas subclasses.

```

**Resposta:**

```
Classe Retangulo herda FormaGeometrica:
    Atributos: 
        - comprimento
        - largura

    Método Construtor(cor, comprimento, largura):
        Chama o Construtor de FormaGeometrica ppassando cor como parâmetro 

        Define o valor dos atributos comprimento e largura com os valores passados como parâmetros

    Método CalcularArea(): 
        área = comprimento * largura
        Retorna área

Classe Circulo herda FormaGeometrica: 
    Atributos:
        - raio
    
    Método Construtor(cor, raio):
        Chama o Construtor de FormaGeometrica passando cor como parâmetro 

        Define o valor do atributo raio com o valor passado como parâmetro 

    Método CalcularArea():
        área = PI * raio * raio
        Retornar área


```
