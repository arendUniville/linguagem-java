<h2>Métodos estáticos</h2> <br>


<h3>Estrutura de declaração de um método estático</h3>

```java

  public static void main(String[] args){
  
    System.out.print("Este é um método estático");
  
  }

```


<br>

<h3>Nomes válidos e boas práticas</h3>



<br>

<h3>Parâmetros</h3>

```java
    
  public static double valorSalario(double valorHora, double horasTrabalhadas){
  
  }    
  
```

<br>

<h3>Retorno</h3>

```java
    
  public static double valorSalario(double valorHora, double horasTrabalhadas){
  
    return horasTrabalhadas * valorHora;
  
  }    
  
```

<br>

<h3>Utilização de métodos estáticos</h3>

```java

  public class CalculadoraSalario{

    public static double valorSalario(double valorHora, double horasTrabalhadas){

      return horasTrabalhadas * valorHora;

    }    
  
  }
  
  public class PagamentoFuncionarios{
  
    double resultado = CalculadoraSalario.valorSalario(40.50, 5);
  
  }
  
```

<br>

<h3>Disponíveis na mesma classe</h3>

<br>

<h3>Disponíveis em outra classe/arquivo.</h3>

<br>

<h3>Recursão</h3>
