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
  
  <h5><b>Forma 1:</b></h5>
    
    public class CompareToCode {
        public static void main(String args[]) {
        
            String string1 = "now";
            String string2 = "now";
            
            int result = string1.compareTo(string2);
            
            System.out.println(result);
            
       }
    }
  
  <h5><b>Forma 2:</b></h5>
    
    public class CompareTo {
        public static void main(String args[]) {
        
            String string1 = "now";
            
            int result = string1.compareTo("now");
            
            System.out.println(result);
            
        }
    }
 
   <h5><b>Forma 3:</b></h5>
    
    public class CompareTo {
        public static void main(String args[]) {
        
            String string1= "hello";
            String string2 ="HELLO";
            
            int result= string1.compareTo(string2);
            
            System.out.println(result);
            
       }
    }
 
   <h5><b>Forma 4:</b></h5>
    
    public class CompareToIgnoreCase {
        public static void main(String args[]) {
        
            String string1= "hello";
            String string2 ="HELLO";
            
            int result= string1.compareToIgnoreCase(string2);
            
            System.out.println(result);
            
       }
    }
    
   <h5><b>Forma 5:</b></h5>
    
    public class EqualityOperator {
        public static void main(String args[]) {
        
            String oneS = new String("Wow");
            String twoS = new String("Wow");
            
            System.out.println(oneS == twoS);
            
        }
    }
    
   <h5><b>Forma 6:</b></h5>
    
    public class Equals {
      public static void main(String args[]) {

          String oneS = new String("Wow");
          String twoS = new String("Wow");

          System.out.println(oneS.equals(twoS));
      }
    }
    
   <h5><b>Forma 7:</b></h5>
    
    public class Equals {
      public static void main(String args[]) {
      
          String oneS = new String("Wow");
          String twoS = new String("WOW");
          
          System.out.println(oneS.equals(twoS));
          
      }
    }
    
   <h5><b>Forma 8:</b></h5>
    
    public class EqualsIgnorecase {
        public static void main(String args[]) {
        
            String oneS = new String("Wow");
            String twoS = new String("WOW");
            
            System.out.println(oneS.equalsIgnoreCase(twoS));
            
        }
    }
    
   <h5><b>Forma 8:</b></h5>
   
    public class ContentEquals {
      public static void main(String args[]) {
      
          String firstS = new String("Here we are");
          
          StringBuffer secondS = new StringBuffer("Here we are");
          
          System.out.println(firstS.contentEquals(secondS));
          
      }
    }
    
  <h3>Diferença entre String e caracter</h3>
  
  Em Java, char é um tipo de dados primitivo usado para conter um único caractere. Significa um único caractere do conjunto de caracteres UTF-16. Em comparação, String   é uma classe que contém uma sequência de caracteres e pode ser considerada uma matriz de caracteres.
  
  
  
  
  
  
