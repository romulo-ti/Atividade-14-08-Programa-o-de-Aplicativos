

class ContaBancaria:

    def __init__(self, titular, saldo, n_Conta):
        self.titular = titular
        self.__saldo = saldo
        self.n_Conta = n_Conta

    def Depositar(self, valor):
        valor = self.saldo + valor
        return valor

    def Sacar(self, valor):
        if valor <= self.saldo:
            self.saldo -= valor
        return valor

    def ConsultarSaldo(self):
        print(f"Exibir extrato")
        print(f"Titular:{self.titular}")
        print(f"Saldo:{self.saldo}")
        print(f"Numero conta:{self.n_conta}")

    def getSaldo(self):
        return self.__saldo

    def setSaldo(self, valor):
        if valor > 0:
            self.__saldo = valor

class Veiculo:
    def __init__(self, marca, modelo):
        self.marca = marca
        self.modelo = modelo

    def Ligar(self):
        print(f"Veiculo Ligado")

class Carro(Veiculo):
    def __init__(self, n_portas):
        self.n_portas = n_portas
    def Ligar(self):
        print(f"Carro ligado")
class Moto(Veiculo):
    def __init__(self, cilindradas):
        self.cilindradas = cilindradas
    def Ligar(self):
        print(f"Moto ligada")
