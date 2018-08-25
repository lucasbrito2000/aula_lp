dicionario={'nome':"fggg",'telefone':"gfgfdsg",'email':"fgkfdgjkfg" }

class contato:
    def __init__(self,_nome,_telefone,_email):
        self.nome=_nome
        self.telefone=_telefone
        self.email=_email
    
    def imprime(self): 
        return('suas informaçoes sao:==>nome:{}--telefone:{}--email:{}').format(self.nome,self.telefone,self.email)

    def reset(self):
        self.nome=None
        self.telefone=None
        self.email=None

chama=contato(dicionario['nome'], dicionario['telefone'], dicionario['email'])
print(chama.imprime())


#2
def dicionario2(dicionario1):
    return len(dicionario)
print(dicionario2(dicionario))
#3
def dic (dici):
    
