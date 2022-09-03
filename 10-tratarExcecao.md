<h2>Tratamento de Exceções</h2>

<h3>Definição</h3>
As exceções ocorrem quando algo imprevisto acontece, elas podem ser provenientes de erros de lógica ou acesso a recursos que talvez não estejam disponíveis.
Quando se cria programas de computador, há possibilidade de ocorrer erros imprevistos durante sua execução, esses erros são conhecidos como exceções e podem ser provenientes de erros de lógica ou acesso a dispositivos ou arquivos externos.

<br>

<h3>Exceções comuns</h3>

<li>Divisão por zero</li>

    int dez = 10;
    int zero = 0;
    
    int divisaoZero = dez / zero;
    
    System.out.println(divisaoZero); 

<br>

    Error:
    Exception in thread "main" java.lang.ArithmeticException: / by zero
            at theException.main(theException.java:9)

<li>Conversão de tipos de dados inválidos</li>

<li>Acessar uma posição inválida em um arranjo</li>

<li>Acessar uma String nula</li>



<h3>Bloco para capturar uma exceção</h3>

<h3>Bloco para capturar diferentes exceções</h3> 

<h3>Bloco finally</h3>

<h3>Lançar uma exceção</h3>
