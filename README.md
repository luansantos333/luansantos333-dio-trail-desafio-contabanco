# CONTA BANCO | DIO

Projeto básico para imprimir informações digitada pelo usuário no terminal 

`public static void main(String[] args) {

        String nomeCliente, agencia;
        int numero;
        double saldo;

        Scanner input = new Scanner(System.in);

        System.out.println("Digite o seu nome: ");
        nomeCliente = input.nextLine();
        System.out.println("Digite a agência: ");
        agencia = input.nextLine();
        System.out.println("Digite o seu número: ");
        numero = input.nextInt();
        System.out.println("Digite o saldo ");
        saldo = input.nextDouble();

        System.out.println("Olá, " + nomeCliente + ", obrigado por criar uma conta em nosso banco, sua agência " +
                "é " + agencia + ", conta " + numero + " e seu saldo " + saldo + " já está disponível para saque");
    } 
