import java.util.Scanner;
public class trabalho{
    public static void main(String[] args) {
        char tema, p1,p2,p3,p4,p5;
        int acerto=0,erro=0;

        Scanner leia = new Scanner (System.in);

        do{
            System.out.println("a) Futebol");
            System.out.println("b) Filmes");
            System.out.println("c) Sair");
            System.out.println("Qual opeção você deseja:");
            tema = leia.next().charAt(0);                         //Aqui a opção desejada será guardada na variável "TEMA".

            if (tema!='a' && tema!='A' && tema!='b' && tema!='B' && tema!='c' && tema!='C') {  //Aqui ocorre a validação da variável "TEMA", para caso seja informado uma opção inválida.
                System.out.println("Opção Inválida! Escolha a opção a, b ou c");
            }else{
                
            switch (tema) {                                            //Nesse switch será guardada o conteúdo da variável "TEMA", para logo em seguida ser saber opção foi //vou fazer o kahoot agora, tá
   
                case 'a': case 'A':
                
                        System.out.println("Pergunta");
                        System.out.println("a) Resposta 1");
                        System.out.println("b) Resposta 2");
                        System.out.println("c) Resposta 3");
                        System.out.println("d) Resposta 4");
                        System.out.println("e) Sair");
                        p1 = leia.next().charAt(0);
                        
                        if (p1=='a' || p1=='A'){
                            System.out.println("Você acertou a questão");
                            acerto++;
                        } else if (p1!='a' && p1!='A' && p1!='b' && p1!='B' && p1!='c' && p1!='C' && p1!='d' && p1!='D') {
                          System.out.println("Resposta Inválida! Escolha a letra a, b, c ou d");  
                        } else{
                            System.out.println("Resposta Errada! ...");
                            erro++;
                        }

                        System.out.println("Pergunta 2");
                        System.out.println("a) Resposta 1");
                        System.out.println("b) Resposta 2");
                        System.out.println("c) Resposta 3");
                        System.out.println("d) Resposta 4");
                        p2 = leia.next().charAt(0);

                        if (p2=='b' || p2=='B'){
                            System.out.println("Você acertou a questão");
                            acerto++;
                        }else if (p2!='a' && p2!='A' && p2!='b' && p2!='B' && p2!='c' && p2!='C' && p2!='d' && p2!='D') {
                          System.out.println("Resposta Inválida! Escolha a letra a, b, c ou d");  
                        } else{
                            System.out.println("Resposta Errada! ...");
                            erro++;
                        }

                        System.out.println("Pergunta 3");
                        System.out.println("a) Resposta 1");
                        System.out.println("b) Resposta 2");
                        System.out.println("c) Resposta 3");
                        System.out.println("d) Resposta 4");
                        p3 = leia.next().charAt(0);

                        if (p3=='c' || p3=='C'){
                            System.out.println("Você acertou a questão");
                            acerto++;
                        }else if (p3!='a' && p3!='A' && p3!='b' && p3!='B' && p3!='c' && p3!='C' && p3!='d' && p3!='D') {
                          System.out.println("Resposta Inválida! Escolha a letra a, b, c ou d");  
                        } else{
                            System.out.println("Resposta Errada! ...");
                            erro++;
                        }

                        System.out.println("Pergunta 4");
                        System.out.println("a) Resposta 1");
                        System.out.println("b) Resposta 2");
                        System.out.println("c) Resposta 3");
                        System.out.println("d) Resposta 4");
                        p4 = leia.next().charAt(0);

                        if (p4=='d' || p4=='D'){
                            System.out.println("Você acertou a questão");
                            acerto++;
                        }else if (p4!='a' && p4!='A' && p4!='b' && p4!='B' && p4!='c' && p4!='C' && p4!='d' && p4!='D') {
                          System.out.println("Resposta Inválida! Escolha a letra a, b, c ou d");  
                        } else{
                            System.out.println("Resposta Errada! ...");
                            erro++;
                        }

                        System.out.println("Pergunta 5");
                        System.out.println("a) Resposta 1");
                        System.out.println("b) Resposta 2");
                        System.out.println("c) Resposta 3");
                        System.out.println("d) Resposta 4");
                        p5 = leia.next().charAt(0);

                         if (p5=='a' || p5=='A'){
                            System.out.println("Você acertou a questão");
                            acerto++;
                        }else if (p5!='a' && p5!='A' && p5!='b' && p5!='B' && p5!='c' && p5!='C' && p5!='d' && p5!='D') {
                          System.out.println("Resposta Inválida! Escolha a letra a, b, c ou d");  
                        } else{
                            System.out.println("Resposta Errada! ...");
                            erro++;
                        }

                        System.out.println("Total de Acertos: "+acerto);
                        System.out.println("Total de Erros: "+erro);

                    break;
            
                case 'b': case 'B':
                    
                    System.out.println("Pergunta");
                        System.out.println("a) Resposta 1");
                        System.out.println("b) Resposta 2");
                        System.out.println("c) Resposta 3");
                        System.out.println("d) Resposta 4");
                        System.out.println("e) Sair");
                        p1 = leia.next().charAt(0);
                        
                        if (p1=='a' || p1=='A'){
                            System.out.println("Você acertou a questão");
                            acerto++;
                        }else if (p1!='a' && p1!='A' && p1!='b' && p1!='B' && p1!='c' && p1!='C' && p1!='d' && p1!='D') {
                          System.out.println("Resposta Inválida! Escolha a letra a, b, c ou d");  
                        } else{
                            System.out.println("Resposta Errada! ...");
                            erro++;
                        }

                        System.out.println("Pergunta 2");
                        System.out.println("a) Resposta 1");
                        System.out.println("b) Resposta 2");
                        System.out.println("c) Resposta 3");
                        System.out.println("d) Resposta 4");
                        p2 = leia.next().charAt(0);

                        if (p2=='b' || p2=='B'){
                            System.out.println("Você acertou a questão");
                            acerto++;
                        }else if (p2!='a' && p2!='A' && p2!='b' && p2!='B' && p2!='c' && p2!='C' && p2!='d' && p2!='D') {
                          System.out.println("Resposta Inválida! Escolha a letra a, b, c ou d");  
                        } else{
                            System.out.println("Resposta Errada! ...");
                            erro++;
                        }

                        System.out.println("Pergunta 3");
                        System.out.println("a) Resposta 1");
                        System.out.println("b) Resposta 2");
                        System.out.println("c) Resposta 3");
                        System.out.println("d) Resposta 4");
                        p3 = leia.next().charAt(0);

                        if (p3=='c' || p3=='C'){
                            System.out.println("Você acertou a questão");
                            acerto++;
                        }else if (p3!='a' && p3!='A' && p3!='b' && p3!='B' && p3!='c' && p3!='C' && p3!='d' && p3!='D') {
                          System.out.println("Resposta Inválida! Escolha a letra a, b, c ou d");  
                        } else{
                            System.out.println("Resposta Errada! ...");
                            erro++;
                        }

                        System.out.println("Pergunta 4");
                        System.out.println("a) Resposta 1");
                        System.out.println("b) Resposta 2");
                        System.out.println("c) Resposta 3");
                        System.out.println("d) Resposta 4");
                        p4 = leia.next().charAt(0);

                        if (p4=='d' || p4=='D'){
                            System.out.println("Você acertou a questão");
                            acerto++;
                        }else if (p4!='a' && p4!='A' && p4!='b' && p4!='B' && p4!='c' && p4!='C' && p4!='d' && p4!='D') {
                          System.out.println("Resposta Inválida! Escolha a letra a, b, c ou d");  
                        } else{
                            System.out.println("Resposta Errada! ...");
                            erro++;
                        }

                        System.out.println("Pergunta 5");
                        System.out.println("a) Resposta 1");
                        System.out.println("b) Resposta 2");
                        System.out.println("c) Resposta 3");
                        System.out.println("d) Resposta 4");
                        p5 = leia.next().charAt(0);

                         if (p5=='a' || p5=='A'){
                            System.out.println("Você acertou a questão");
                            acerto++;
                        }else if (p5!='a' && p5!='A' && p5!='b' && p5!='B' && p5!='c' && p5!='C' && p5!='d' && p5!='D') {
                          System.out.println("Resposta Inválida! Escolha a letra a, b, c ou d");  
                        } else{
                            System.out.println("Resposta Errada! ...");
                            erro++;
                        }

                        System.out.println("Total de Acertos: "+acerto);
                        System.out.println("Total de Erros: "+erro);

                    break;
            }
            }

        } while (tema!='c' && tema!='C');

                
        }

    }


   //UÉ, FOI 
   //kd 
   //funcionou
   //depois o cara vai pro git 
   //tnm
   //pra mim n apareceu nd
   //vou ler o bagulho, ver oq falta 
   //tem que colocar um if pra cada questão, caso o cara coloque 0 por exemplo
   //sim
   //uma merda, vtnc
   //chatinho
   //porém fácil
   //em casa a gente arruma, muita mão
   //não é mais facil fazer dois switch?
   //onde?
   //na real deixa, depois eu quero ver se vai dar pra fazer um bagulho
   //q bagulho
   //é que eu acho que vai ser mais merda fazer tudo em 1 switch só, 
   //fazer o simples pai
   //tudo, mas bora indo assim, depois o cara ve se vai dar merda 
   //ta
   //tem que ir comentando agora
