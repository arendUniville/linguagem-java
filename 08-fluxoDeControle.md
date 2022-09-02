<h2>Fluxo de Controle</h2>

<h3>Estruturas de Decisões</h3>

<li><b>if-else-then</b></li>

    verdadeiro = True;

    if(verdadeiro == True){

      System.out.println("Retorno caso a condição seja VERDADEIRA.");

    }else{

      System.out.println("Retorno caso a condição seja diferente de VERDADEIRA.");

    }

<li><b>switch</b></li>

    int dia = 4;
     
    switch (dia) {
    
      case 1:
        System.out.println("Segunda");
        break;
        
      case 2:
        System.out.println("Terça");
        break;
        
      case 3:
        System.out.println("Quarta");
        break;
        
      case 4:
        System.out.println("Quinta");
        break;
        
      case 5:
        System.out.println("Sexta");
        break;
        
      case 6:
        System.out.println("Sábado");
        break;
        
      case 7:
        System.out.println("Domingo");
        break;

<h3>Estruturas de Repetições</h3>
  
<li>for</li>

    for(int i = 0; i < 5; i++){
        
        System.out.println(i);
        
     }
  
<li>while</li>

    boolean trigger = true;

    while(trigger){

        System.out.println("Entrou uma vez");
        System.out.println(trigger);

        trigger = false;

        System.out.println("Mudou estado");
        System.out.println(trigger);
        
    }
  
<li>do-while</li>

        int i = 5;
        
		do {
        
			System.out.println(i);
            
			i++;
            
		} while (i <= 10);
  
  
<li>Comando break</li> 

    for (int i = 0; i < 10; i++) {
      if (i == 4) {
        break;
      }
      System.out.println(i);
    }
  
  
<li>Comando continue</li>

    for (int i = 0; i < 10; i++) {
      if (i == 4) {
        continue;
      }
      System.out.println(i);
    }
