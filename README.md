# ordena-o
Meu código de ordenação

inteiro vetor [5] 
inteiro  m

para (inteiro i=0; i<5; i++) {
escreva ("Digite um valor para o"," ", +i+ "º número \n")
leia (vetor [i])}

faca  {
se (vetor [0] > vetor [1]) {
m = vetor [0]
vetor [0] = vetor [1]
vetor [1] = m

}

se (vetor [0] > vetor [2]) {
m = vetor [0]
vetor [0] = vetor [2]
vetor [2] = m		
}

se (vetor [1] > vetor[2]) {
m = vetor [1]
vetor [1] = vetor [2]
vetor [2] = m
}

se (vetor [1] > vetor [3]) {
m = vetor [1]
vetor [1] = vetor [3]
vetor [3] = m
}

se (vetor [2] > vetor [3]) {
m = vetor [2]
vetor [2] = vetor [3]
vetor [3] = m
}


se (vetor [2] > vetor [4]) {
m = vetor [2]
vetor [2] = vetor [4]
vetor [4] = m
}


se (vetor [3] > vetor [4]) {
m = vetor [3]
vetor [3] = vetor [4]
vetor [4] = m
}



} enquanto (vetor [0] > vetor [1] ou vetor [0] > vetor [2] ou vetor[1] > vetor [2] ou vetor [1] > vetor [3] ou vetor [2] > vetor [3] ou vetor [2] > vetor [4] ou vetor [3] > vetor [4]) 


escreva ("A ordem é:", " ", vetor [0], vetor [1], vetor [2], vetor [3], vetor [4])
