# Backup-Code
codigos da aula de fundamentos de programação
/*
     Exercício do volume:

        double raio;
        double raiocubico;
        double pi = M_PI;

        printf("Digite um numero para o raio: ");
        scanf("%lf", &raio);

        raiocubico = pow(raio,3);
        printf("o volume da esfera é: %0.2lf ", 3.0/4.0 * pi * raiocubico);

    */

    /*
           Exercício 2: Base do trapézio
       float b1,b2,altura, area;

       printf("Digite um numero para a base maior:");
       scanf("%f", &b1);

       printf("Digite um numero para base menor: ");
       scanf("%f", &b2);

       printf("Digite um numero para altura: ");
       scanf("%f", &altura);

       area = (b1 + b2) * altura/2;
       printf("O valor de area do trapezio e: %f", area);
   */

    /* Exercício 1: Lista
    float n1,n2, res;

    printf("Digite o primeiro numero: ");
    scanf("%f", &n1);

    printf("Digite o segundo numero: ");
    scanf("%f", &n2);
    res = (n1 - n2);

    printf("O resultado e: %0.2f", res);
    */


    /*Exercício 2 - Lista

      float n1,n2,n3,res;

     printf("Digite o primeiro numero: ");
     scanf("%f",&n1);
     printf("Digite o segundo numero: ");
     scanf("%f", &n2);
     printf("Digite o terceiro numero: ");
     scanf("%f", &n3);

     res = (n1 * n2 * n3);
     printf("O resultado eh: %f", res);
     */

    /* Exercício 3 - Lista
     float n1,n2;
    printf("Digite os dois numeros: ");
    scanf("%f%f",&n1,&n2);
    printf("o resultado da divisao e:%f", n1 / n2);
    */

    /* Exercício 4 - Lista
     float nota1,nota2,media;

     printf("Digite as duas notas: ");
     scanf("%f%f", &nota1, &nota2);

     media = (nota1 * 2 + nota2 * 3)/5;
     printf("a media ponderada das notas e: %0.2f\n", media);*/


    /* Exercício 5 - Lista
    float preco, precodescontado;
    const float desconto = 0.10;

    printf("O preco do produto e: ");
    scanf("%f", &preco);

    precodescontado = preco * (1 - desconto);
    printf(" O produto com desconto e: %0.2f\n", precodescontado);

*/
    /* Exercício Aula
    float n1,n2;
    printf("Escreva dois numeros:%0.2f & %0.2f");
    scanf("%f%f",&n1,&n2);
    if (n1>n2) {
        printf("o n2 e menor que n1");
    }
    else {
        printf("n1 e menor que n2");
    }
    */
    /*Exercício 2
    float n1,n2,n3;
    printf("Escreva 3 numeros: ");
    scanf("%f%f%f", &n1,&n2,&n3);

    if (n1>n2 && n1>n3) {
        printf("n1 e o maior!");
    }
    if (n2>n1 && n2>n3) {
        printf("n2 e o maior!");

    }
    if (n3>n1 && n3>n2)
        {
        printf("n3 e o maior!");
        }
    */
    /* Exercício 3
    int numero;

    printf("Digite um numero: ");
    scanf("%d", &numero);

    if (numero % 2 == 0) {
        printf("o numero e par!");
    }else {
        printf("o numero e impar!");
    }
    */
    /* float  nota1,nota2;
    float media;

    printf("Digite a primeira nota: ");
    scanf("%f", &nota1);
    printf("Digite a segunda nota: ");
    scanf("%f", &nota2);

    media =(nota1+nota2)/2;
    if (media >= 0 && media < 3)
    {
        printf("reprovado!");
    }
    if (media >= 3 && media <6) {
        printf("exame! ");
    }
    if (media >= 6 && media <= 10) {
        printf("aprovado!");
    }*/
    /*
     *Exercício 4:
    int nascimento, idade;
    int anoatual = 2025;

    printf("Digite sua data de nascimento: ");
    scanf("%d", &nascimento);

    idade = (anoatual - nascimento);
    if (12 <= idade && idade <= 15)
        {
        printf("pode participar do campeonato");
    }
    else {
        printf("nao pode participar do campeonato");
    }


   /* float  nota1,nota2;
    float media;

    printf("Digite a primeira nota: ");
    scanf("%f", &nota1);
    printf("Digite a segunda nota: ");
    scanf("%f", &nota2);

    media =(nota1+nota2)/2;
    if (media >= 0 && media < 3)
    {
        printf("reprovado!");
    }
    if (media >= 3 && media <6) {
        printf("exame! ");
    }
    if (media >= 6 && media <= 10) {
        printf("aprovado!");
    }*/
    /*
    int codigo;
    printf("Digite seu codigo: ");
    scanf("%d", &codigo);

    if (codigo == 1 || codigo == 2) {
        printf(" Acesso permitido");
    }else {
        printf(" Acesso negado");
    }
*/
    /*float peso;
    printf("Digite o peso: ");
    scanf("%f", &peso);

    printf("Aumento de peso, peso atual:%0.2f\n ", peso + peso* 0.15);

    printf("Decrescimo de peso, peso atual: %0.2f\n ", peso - peso* 0.20);

    */

    /* int idade;
     printf("Digite sua idade: ");
     scanf("%d", &idade);

     if (idade < 16)
         {
             printf("nao pode votar");
         }
         else {
             if(idade <18)
                 {
                 printf("facultativo");
                 }else
                     {
                     printf("deve votar");
                 }
         }
 */
    /*
        int opc;

        printf("1, Saque\n");
        printf("2, Extrato\n");
        printf("3. Transferencia\n");
        printf("4. Deposito\n");
        printf("Digite um numero: ");

        scanf("%d", &opc);

        if (opc == 1) {
            printf("Saque\n");

        }
        if (opc == 2) {
            printf("Extrato\n");
        }
        if (opc == 3) {
            printf("Transferencia\n");

        }
        if (opc == 4) {
            printf("Deposito\n");
        }
        if (opc > 4 ) {
            printf("Opcao invalida\n");
        }
        if (opc < 1) {
            printf("Opcao invalida\n");
        }*/

    /* int preco;
     float preco1 = 100;


     printf("1, MG\n");
     printf("2, SP\n");
     printf("3. Rj\n" );
     printf("4. Ms\n");
     printf("Digite o estado:");
     scanf("%d",&preco);

     switch (preco)
     {
         case 1:
             printf("Mg o produto fica:%0.2f", preco1 * 0.7);
         break;
         case 2:
             printf(" Sp o produto fica:%0.2f ", preco1 * 0.12);
         break;
         case 3:
             printf("Rj o produto fica:%0.2f",preco1 * 0.15);
         break;
         case 4:
             printf("Ms o produto fica:%0.2f", preco1 * 0.18);
         break;
         default:
             printf("Produto invalido");
     }
 */
    /*
        int a,b;

        printf("digite um numero: ");
        scanf("%d",&a);
        printf("digite um numero: ");
        scanf("%d",&b);

        for (int i = a; i <= b; i++) {
            printf("%d", i);
        }

    */
    /* Exercicio Repeticao 2
    int n;

    printf("digite um numero: ");
    scanf("%d", &n);

    for (int i = 1; i <= n; i++)
    {
        if (n % i == 0)
        {
            printf("%d \n ", i);
        }
        else {
            continue;
        }
    }
    */
    /*float idade, altura, peso, media;
    printf("Digite a idade do jogador1: ");
    printf("Digite a altura do jogador: ");
    printf("Digite o peso do jogador: ");
    scanf("%f" "%f" "f", &idade, &altura, &peso);

    for (int i = 0; i <= 5; i++)
    {
        if (idade < 18) {
            printf("%f,Jogador é menor de idade \n", idade);
        }

    }
    float peso,altura;
    char sexo;
    float pesoideal, pesoperder,Imc, Imcideal;


    printf("Homem eh H, mulher M", sexo);
    scanf("%c", &sexo);

    printf("A altura em metros:", altura);
    scanf("%f", &altura);

    printf("O peso em Kg");
    scanf("%f", &peso);


    // Deu certo Item A
    if (sexo == 'H') {
        printf("%.2f", (72.7 * altura) - 58);
    }else {
        if (sexo == 'M') {
            printf("%.2f", (62.1 * altura) - 44.7);
        }
    }

    //Item B





    Imc = peso/(altura*altura);

    printf("%.2f", Imc);
    printf("%.2f",pesoideal);

    if(Imc < 18.5) {
        printf(" Abaixo do peso");
    }
    else {
        if (Imc > 18.5 && peso < 25)
        {
            printf(" Peso Normal");
        }
        else {
            if (Imc > 25 && peso < 30)
            {
                printf("Acima do peso");
                pesoperder = peso - pesoideal;
                Imcideal = pesoideal / (altura * altura);
                printf("%.2f\n", pesoperder);
                printf("%.2f\n", Imcideal);
            }
            else {
                if (Imc > 30)
                {
                    printf(" Obeso");
                    pesoperder = peso - pesoideal;
                    Imcideal = pesoideal / (altura * altura);
                    printf("%.2f\n", pesoperder);
                    printf("%.2f\n", Imcideal);
                }
            }
        }



    }
*/


    /*
      int a,b;

      printf("Digite o primeiro numero: ");
      scanf("%d",&a);
      printf("Digite o segundo numero: ");
      scanf("%d",&b);


      for (int n = a + 1; n < b; n++ )
      {
          printf("%d\n", n);
      }


      */
    /*int jogadores, jogador;
    float idade,peso,altura, mediaidade,mediaaltura,Maioraltura = 0, Pesosacima = 0;
    float somaidade = 0, somaaltura = 0, somapeso = 0, menores = 0, Menoraltura = 0;
    mediaaltura = (somaaltura/ 5);
    mediaidade = (somaidade / 5);
    for (int n = 0; n < 5; n++) {
        printf("Digite sua idade:\n ");
        scanf("%f",&idade);
        somaidade += idade ;

        //Menores de Idade
        if (idade < 18) {
            menores ++;
        }

        printf("Digite sua altura:\n ");
        scanf("%f",&altura);
        somaaltura += altura;
        if (n == 0) {
            Menoraltura = altura;
        }
        if (altura > Maioraltura)
        {
            Maioraltura = altura;
        }
        if (altura < Menoraltura) {
            Menoraltura = altura;
        }
        printf("Digite sua peso:\n ");
        scanf("%f",&peso);
        somapeso += peso;
        if (peso > 80) {
            Pesosacima ++;
        }

    }
    printf("A maior altura eh: %0.2f\n", Maioraltura);
    printf("A menor altura eh: %0.2f\n",Menoraltura);
    printf("menores de idade:%0.2f\n ", menores);
    printf("media das idades:%0.2f\n", mediaidade);
    printf("media das alturas: %.2f\n", mediaaltura);
    printf("a porcentagem de pessoas acima de 80kgs:%0.2f", (Pesosacima/5)*100);*/


    /* int numerosneg, a;
     numerosneg = 0;
     for (int n = 0; n < 5; n++ )
         {
         printf("Digite um numero: ");
         scanf("%d", &a);
         if (a < 0)
         {
              numerosneg++;
         }

     }
     printf("%d",numerosneg);*/

    /*int n;
    int fatorial = 1;
    printf("Enter a number: ");
    scanf("%d", &n);

    if (n < 0) {
        printf("Invalido");
    }
       for (int i = 1; i <= n; i++)
           {
            fatorial = fatorial * i;

        }
        printf("o fatorial h: %d", fatorial);*/

    /* float produto;
     int estado;


     printf("Mg: 1\n");
     printf("Sp: 2\n");
     printf("Rj: 3\n");
     printf("Ms: 4\n");

     printf("diga o preço o estado: ");
     scanf("%d", &estado);
     printf("o preço do produto: ");
     scanf("%f", &produto);

     switch (estado) {
         case 1:
             printf("Produto 1: %f",produto * 0.7);
             break;
         case 2:
             printf("Produto 2: %f",produto * 0.12);
         break;
         case 3:
             printf("Produto 3: %f", produto * 0.18);
         break;
         case 4:
             printf("Produto 4: %f", produto * 0.22);
         break;
         default:
             printf("Produto unrecognizado");*/

    /*   int n;
       float valorembaixo = 0;

       printf("Digite um numero: ");
       scanf("%d", &n);

       if (n <= 0) {
           printf("Produto negativo");
       }
       for (int i=1 ; i<= n; i++)
       {
           valorembaixo +=  (1.0/i);

       }
   printf("A soma eh: %0.2f", valorembaixo);*/

   
float Expoente(float x, int y)
{
    float exponenciacao = 1;
    for(int i = 1; i <= y; i++)
    {
        exponenciacao *= x;

    }
    return exponenciacao;

}
int main()
{

    int y;
    float x, result;
    printf("Enter number: ");
    scanf("%f", &x);
    printf("Enter number: ");
    scanf("%d", &y);
    result = Expoente(x,y);
    printf("%f", result);

    return 0;
 }
 int SomaDobro (int *a, int *b, int soma);

int main()
{
    int a, b, soma;
    int somaDobro;

    printf("Digite um numero: ");
    scanf("%d", &a);
    printf("Digite um numero: ");
    scanf("%d", &b);
    printf("antes da funcao: %d e %d\n", a, b);

    somaDobro = SomaDobro (&a, &b,soma);

    printf("Depois da funcao: %d e %d\n", a, b);
    printf("Soma do dobro: %d", somaDobro);

    return 0;
}
int SomaDobro (int *a, int *b, int soma)
{
    int a2 = (2 * *a);
    int b2 = (2 * *b);

    *a = a2;
    *b = b2;

    soma = a2 + b2;
    return soma;
}
#include <stdio.h>
#include <math.h>
//Escreva um programa em C que lê 5 valores para a
// um de cada vez, e conta quantos destes valores são negativos, escrevendo esta informação na tela

int Somar(int *a, int *b, int soma);

int main()
{
    int a, b, soma;

    printf("Digite o primeiro numero: ");
    scanf("%d", &a);
    printf("Digite o segundo numero: ");
    scanf("%d", &b);

    printf("numeros antes da funcao: %d e %d\n", a,b);

    Somar(&a, &b, soma);

    printf("numeros depois da funcao: %d e %d\n", a,b);



    return 0;
}
int Somar(int *a, int *b, int soma) {

    soma = *a + *b;
    *a = soma;
}
#include <stdio.h>

#include <stdio.h>



int main()
{   int tam = 5;
    int posicoes[tam];
    int somar = 0, qtd = 0, maior, menor;
    float media;

    maior = posicoes[0];
    menor = posicoes[0];

    for (int i = 1; i < tam; i++) {

        if (posicoes[i] > maior) {
            maior = posicoes[i];
        }
        if (posicoes[i] < menor) {
            menor = posicoes[i];
        }
    }
   for (int i = 0; i < tam; i++) {
        printf("Digite um valor para posicao %d : ", i);
        scanf("%d", &posicoes[i]);
        //soma dos vetores
       somar += posicoes[i];
        // media
       media = (somar / tam);

       if (posicoes[i] >  5) {
           qtd++;
       }

    }
    
    printf("Posicao : %d \n", posicoes[tam]);
    printf("Somar : %d \n", somar);
    printf("Media : %.2f \n", media);
    printf("Posicoes maiores que 5: %d\n", qtd);




    return 0;
}
#include <stdio.h>
#include <string.h>

/* Elabore um programa no qual o usuário informe o
nome de um arquivo texto e uma palavra, e o
programa informe o número de vezes que aquela palavra aparece dentro do arquivo.
 Considere que o arquivo texto contenha uma palavra
por linha
*/

int main()
{
    FILE *Arquivo;
    char palavra[30];
    char palavralida[30];
    char nomedoArquivo[30];
    int count = 0;

    //Nome do arquivo
    printf("Nome do Arquivo : ");
    scanf("%s", &nomedoArquivo);



    Arquivo = fopen(nomedoArquivo, "r");
    if (Arquivo == NULL)
    {
        return 1;
    }
    //Ler a palavra desejada
    printf("Digite uma palavra qualquer: ");
    scanf("%s", palavra);

    while (!feof(Arquivo))
    {
        fscanf(Arquivo, "%s", palavralida);
        if (strcmp(palavra, palavralida) == 0) {
            count++;
        }
    }
    fclose(Arquivo);

    printf("Total de palavras: %d\n", count);
    
    fclose(Arquivo);
    printf("Numero da palavra %s repetida: %d\n",  palavra, count);



    return 0;
}









