# Cachorro
class Dog:
    def __init__(self,nome,idade):
        self.nome = nome
        self.idade = idade

    def latir(self):
        print("AU Auuu!")

    def comer(self):
        print("gostoso")

d1 = Dog("Duque",3)
d2 = Dog("Princesa",2)
print("meu cachorro se chama {} e possui {}messe".format(d1.nome,d1.idade))
d1.latir()
print("meu cachorro se chama{} e possui {}messes".format(d2.nome,d2.idade))
d2.latir()
