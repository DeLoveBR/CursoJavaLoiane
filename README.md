    /* Supondo que a população de um pais A seja da ordem de 80000
    habitantes com uma taxa de crescimento de 3% e que a populção de B
    seja 200000 habitantes com uma taxa de crescimento de 1,5%.
    Faça um programa que calcule e escreva o número de anos
    nescessários para que a população do Pais A ultrapasse ou iguale a
    população B, mantidas as taxas de crescimento. */

    public static void main(String[] args) {

        int populacaoA = 80000;
        int populacaoB = 200000;
        int cont = 0;
        while(populacaoA < populacaoB){

            populacaoA += (populacaoA/100) *3;
            populacaoB += (populacaoB/100) *1.5;
            cont++;
        }
        System.out.println(" População A " + populacaoA);
        System.out.println(" População B " + populacaoB);
        System.out.println("Quantidade de Anos " + cont);
    }

}



