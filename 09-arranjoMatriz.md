<h2>Arranjos e Matrizes</h2>

<h3>Definição matemática</h3>
Essa estrutura de dados também é conhecida como variável indexada, vetor (para arranjos unidimensionais) e matriz (para arranjos bidimensionais). Os arranjos mantêm uma série de elementos de dados, geralmente do mesmo tamanho e tipo de dados. Elementos individuais são acessados por sua posição no arranjo.

<br>

<li><b>Declaração de arranjos</b></li>

    String[] marcasCarro = {"Volvo", "BMW", "Ford", "Mazda"};

<br>

    int[] numeros = {10, 20, 30, 40};

<li><b>Declaração de matrizes</b></li>

    const matriz = [ [1,2],[3,4],[5,6] ];

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

<li><b>Coluna a coluna</b></li>

<li><b>Em diagonal</b></li>

<li><b>Utilizar arranjos e matrizes como parâmetros de métodos</b></li>

<li><b>Utilizar arranjos e matrizes como retorno de métodos</b></li>
