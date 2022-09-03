<h2>Arranjos e Matrizes</h2>

<h3>Definição matemática</h3>
Essa estrutura de dados também é conhecida como variável indexada, vetor (para arranjos unidimensionais) e matriz (para arranjos bidimensionais). Os arranjos mantêm uma série de elementos de dados, geralmente do mesmo tamanho e tipo de dados. Elementos individuais são acessados por sua posição no arranjo.

<br>

<li><b>Declaração de arranjos</b></li>

    String[] marcasCarro = {"Volvo", "BMW", "Ford", "Mazda"};

<br>

    int[] numeros = {10, 20, 30, 40};

<li><b>Declaração de matrizes</b></li>

    int[][] matriz = new int[2][2];

<li><b>Percorrer arranjos</b></li>

    ArrayList lista = new ArrayList();]
    
    String[] array = {"true", "true", "true", "false", "false"};
    
    for(int x = 0; x < array.length; x++){
      
        if(array[x].equals("true")){

            lista.add(x);

         }
     }

<li><b>Percorrer matrizes</b></li>

        int quantDisciplina = 2;
        int quantAlunos = 2;
        String nomeDisciplina = "";

        Disciplina disciplina[] = new Disciplina[quantDisciplina];
        Aluno aluno[] = new Aluno[quantAlunos];

        //Disciplina
        for(int i = 0;  i < quantDisciplina; i++){

            if(i == 0){

                nomeDisciplina = "Portugês";

            }else if(i == 1){

                nomeDisciplina = "Matemática";

            }else if(i == 2){

                nomeDisciplina = "História";

            }else if(i == 3){
                
                nomeDisciplina = "Geografia";

            }else if(i == 4){

                nomeDisciplina = "Física";

            }else if(i == 5){

                nomeDisciplina = "Química";
                
            }else if(i == 6){
                
                nomeDisciplina = "Inglês";

            }else{

                nomeDisciplina = "Matéria inválida";

            }


<li><b>Linha a linha</b></li>

    public static char[][] bidArray = new char[][]{{'1', '2', '3'}, {'4', '5', '6'}, {'7', '8', '9'}};

    public static void main(String[] args) {
  
      for(int i = 0; i < bidArray.length; i++){            
         System.out.println("linha " + i + ": " +Arrays.toString(bidArray[i]));
         
     }

<li><b>Coluna a coluna</b></li>

    for (int linha = 0; linha < suatabela.getRowCount(); linha++) {
          
          for (int coluna = inicio; coluna <= fim; coluna++) {//dependendo do entendimento, pode ser usado coluna < fim, dentro deste for
              System.out.print(suatabela.getValueAt(linha, coluna) + " ");
              
          }
          
          System.out.println("");
      }


<li><b>Em diagonal</b></li>

   public static void main(String[] args) {
      Scanner ler = new Scanner(System.in);

      int n = ler.nextInt();

      int matriz[][] = new int[n][n];

      for (int i = 0; i < n; i++) {
          // Informa a linha.
          System.out.printf("Informe os elementos %da. linha:\n", (i + 1));
          for (int j = 0; j < n; j++) {
              // Informa qual número deve se colocar.
              System.out.printf("m[%d][%d] = ", i, j);
              matriz[i][j] = ler.nextInt();
          }
          
      }

      // Obtém a soma das diagonais.
      int somaDiagonal1 = 0, somaDiagonal2 = 0;
      for (int i = 0; i < n; i++) {
          somaDiagonal1 += matriz[i][i];
          somaDiagonal2 += matriz[n - 1 - i][i];
      }

      // Calcula a diferença das somas.
      int diferenca = somaDiagonal1 - somaDiagonal2;
      if (diferenca < 0) diferenca *= -1;

      // Exibe o resultado.
      System.out.printf("A difereça da soma das diagonais é %d.", diferenca);
  }


<li><b>Utilizar arranjos e matrizes como parâmetros de métodos</b></li>

    public class Main{
      public static void addArrays(int[] arr1, int[] arr2){ // Passando dois arrays na declaração do método i[] demonstra que é um array
      
          for(int i = 0; i < arr1.length; i++){
          
              int sum = arr1[i] + arr2[i];
              System.out.print(sum + " ");
          }
      }
    }

<li><b>Utilizar arranjos e matrizes como retorno de métodos</b></li>

    public class Main{
        public static void main(String[] args){
            int[] arr1 = {1, 2, 3, 4, 5};
            int[] arr2 = {2, 4, 6, 8, 10};
            addArrays(arr1, arr2);// Passando dois arrays declarados como parâmetros para chamar o método
        }
    }
