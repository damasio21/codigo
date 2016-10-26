# codigo

public static void main(String[] args) {
 
        double nota1, nota2, nota3, media;
 
        System.out.println("Entre com a primeira nota:");
        nota1 = new Scanner(System.in).nextDouble();
        System.out.println("Entre com a segunda nota:");
        nota2 = new Scanner(System.in).nextDouble();
        System.out.println("Entre com a terceira nota:");
        nota3 = new Scanner(System.in).nextDouble();
 
        media = (nota1+nota2+nota3)/3;
 
        if (media >=7){
            System.out.println("Você está aprovado!");
        }
        if (media >=5 & media <7){
            System.out.println("Você está de recuperação");
        }
        else if (media <5){
            System.out.println("Você está reprovado");
        }
 
    }
 
}

*Distância vertical:
 Já tentou ficar se encontrando numa classe, passando de uma função para a próxima,
 subindo e descendo pelo código-fonte, tentando adivinhar como as funções se relacionam e operam.
 Os conceitos intimamente relacionados devem ficar juntos verticalmente.
 Obviamente esta regra não funciona para conceitos em arquivos separados.
 Você está tentando entender o que o sistema faz, enquanto gasta tempo e energia mental
 numa tentativa de localizar e lembrar onde estão as peças.
