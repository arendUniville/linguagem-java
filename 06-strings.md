<h2>String</h2>
  
  <h3>Concatenação de String</h3>
  
    public class concatenar {
      public static void main(String[] args) {

        String frase1 = "frase 1";
        String frase2 = "frase 2";

        System.out.println("Estou concatenando a "+frase1+" com a "+frase2);

      }
    }

  <h3>Principais operações sobre String</h3>

  <li><b>[Java String]</b> - Uma variável String contém uma coleção de caracteres entre aspas duplas:</li>
  
    String texto = "Ola";
    
  <li><b>[String Length]</b> - Uma String em Java é na verdade um objeto, que contém métodos que podem realizar certas operações em strings. Por exemplo, o               comprimento de uma string pode ser encontrado com o método length():</li>

    String tamanhoString = "Paralelepipedo";
    System.out.println("O comprimento da String tamanhoString é: " + tamanhoString.length());
    
  <li><b>[Maiúsculos e minúsculos]</b> - Para transformar as letras de uma String em maiúscula usamos .toUpperCase() e para transformar em minúscula usamos               .toLowerCase:</li>
  
    String texto = "Ola Mundo";
    System.out.println(texto.toUpperCase());
    System.out.println(texto.toLowerCase());
  
  <h3>Comparação de String</h3>
  
  <h3>Diferença entre String e caracter</h3>
