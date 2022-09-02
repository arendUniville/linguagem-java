<h2>Entrada de Dados</h2>
 
<h3>Classe Scanner</h3>

Primeiramente para poder fazer o uso da classe Scanner, é necessário fazer a importação da seguinte forma:

    import java.util.Scanner;
    
Em seguida, devemos criar nosso objeto Scanner atribuindo ele a uma variável, como o exemplo a seguir:

    Scanner teclado = new Scanner(System.in);

<li>Obter um valor inteiro</li>

    int entradaTeclado = teclado.nextInt();

<li>Obter um valor decimal</li>

<h5><b>Forma 1:</b></h5>

    double entradaTeclado = teclado.nextDouble()();
    
<h5><b>Forma 2:</b></h5>

    float entradaTeclado = teclado.nextFloat()();

<li>Obter um valor de texto</li>

<h5><b>Forma 1:</b></h5>

    String entradaTeclado = teclado.next()();
    
<h5><b>Forma 2:</b></h5>

    float entradaTeclado = teclado.nextLine()();
