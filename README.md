# Pr-ximo-estagi-rio-
Respostas 
1 ) consigo em python e em Java script

Em pythin 👇
def fibonacci(n):
    # Inicia a sequência de Fibonacci com 0 e 1
    fib_sequence = [0, 1]
    
    # Gera a sequência até que o próximo número seja maior que n
    while fib_sequence[-1] < n:
        next_value = fib_sequence[-1] + fib_sequence[-2]
        fib_sequence.append(next_value)
    
    return fib_sequence

def is_fibonacci(number):
    # Obtém a sequência de Fibonacci até o número informado
    fib_sequence = fibonacci(number)
    
    # Verifica se o número está na sequência
    if number in fib_sequence:
        return f"O número {number} pertence à sequência de Fibonacci."
    else:
        return f"O número {number} NÃO pertence à sequência de Fibonacci."

# Solicita ao usuário para informar um número
number = int(input("Informe um número para verificar se pertence à sequência de Fibonacci: "))

# Exibe o resultado
print(is_fibonacci(number))

Em Java scpt 👇👇👇👇
function fibonacci(n) {
    // Inicia a sequência de Fibonacci com 0 e 1
    let fibSequence = [0, 1];

    // Gera a sequência até que o próximo número seja maior que n
    while (fibSequence[fibSequence.length - 1] < n) {
        let nextValue = fibSequence[fibSequence.length - 1] + fibSequence[fibSequence.length - 2];
        fibSequence.push(nextValue);
    }

    return fibSequence;
}

function isFibonacci(number) {
    // Obtém a sequência de Fibonacci até o número informado
    let fibSequence = fibonacci(number);

    // Verifica se o número está na sequência
    if (fibSequence.includes(number)) {
        return `O número ${number} pertence à sequência de Fibonacci.`;
    } else {
        return `O número ${number} NÃO pertence à sequência de Fibonacci.`;
    }
}

// Solicita ao usuário para informar um número
let number = parseInt(prompt("Informe um número para verificar se pertence à sequência de Fibonacci:"));

// Exibe o resultado
alert(isFibonacci(number));


testado e funcionando os dois códigos acima 🤩
________________

2) 
def count_letter_a(text):
    # Converte o texto para minúsculas e conta as ocorrências da letra 'a'
    count = text.lower().count('a')
    return count

# Solicita ao usuário para informar uma string
input_string = input("Informe uma string para verificar a existência da letra 'a': ")

# Conta as ocorrências de 'a' e 'A' na string
count = count_letter_a(input_string)

# Exibe o resultado
if count > 0:
    print(f"A letra 'a' aparece {count} vez(es) na string.")
else:
    print("A letra 'a' não aparece na string.")


__________________

3) valor final: 77

_________________

4) a= 9
    B = 128 
    C = 49 
     D= 100
     E = 13 
     F = 21 

5 ) eu ligaria o primeiro interruptor,  deixaria ligado por 5 minutos , depois sairia da sala , e ligaria o segundo interruptor.  
Então para descobrir qual lâmpada é de cada interruptor seria simples.  
Porque a lâmpada que estiver quente é do primeiro interruptor,  a que eu deixei acessa é do segundo interruptor e a que está fria é do terceiro interruptor que não foi ligada 
